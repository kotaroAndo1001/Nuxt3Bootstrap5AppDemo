<template>
  <div>
    <h2>6位 ヴィニシウス・ジュニオール（ブラジル／レアル・マドリード）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/ヴィ二シウス.jpg" alt="ヴィ二シウス">
      </div>
      <div class="media-content">
        <h3>ヴィニシウスは昨シーズン、クラブと代表で20ゴール・20アシストの大記録を達成し、今やマドリーの正真正銘の "ギャラクティコ "となった。ロス・ブランコスは今年、彼が連れて行けるところまで行くだろう。</h3>
      </div>
    </div>

    <h2>7位 フリアン・アルバレス（マンチェスター・シティ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/アルバレス.jpg" alt="アルバレス">
      </div>
      <div class="media-content">
        <h3>メッシがアルゼンチン代表のスターなら、アルバレスはワールドカップ優勝チームにとって重要な相棒だった。2023-24シーズン、アルバレスの印象的なスタートは、すでに歴史的な成功を収めているアルゼンチン代表FWにとって、さらなるビッグシーズンとなることを予感させる。</h3>
      </div>
    </div>

    <h2>8位 ヴィクター・オシムヘン（ナポリ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/オシムヘン.png" alt="オシムヘン">
      </div>
      <div class="media-content">
        <h3>彼は常に優秀だったが、オシムヘンは昨年、別のレベルを見出した。セリエAで26ゴール4アシストを記録。チャンピオンズリーグでも5試合に出場して5得点を挙げた。</h3>
      </div>
    </div>
  </div>
</template>

<style scoped>
  /* Add the styles from the Messi, Haaland, and Mbappe sections here */
  .media {
    display: flex;
    align-items: center;
  }
  .media-image {
    flex: 0 0 400px; /* You can adjust the max-width as needed */
    margin-right: 20px;
  }
  .media-image img {
    width: 100%;
    height: auto;
    object-fit: cover;
  }
  .media-content {
    flex: 1;
  }
  @media (max-width: 768px) {
    .media {
      flex-direction: column;
    }
    .media-image {
      margin-right: 0;
      margin-bottom: 20px;
      flex-basis: auto;
      max-width: 100%;
    }
  }
</style>

