<template>
  <div>
  <h1 class="title">Ballon D'or 2023年ランキング</h1>
  <h1>＜11~15位＞</h1>
    <!-- 11th Player -->
    <h2>11位 モハメド・サラー（エジプト/リヴァプール）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/サラー.jpg" alt="サラー">
      </div>
      <div class="media-content">
        <h3>サラーは2020年以降で最低のゴール数を記録したが、それでもこのポジションでネットを揺らすことにかけてはトップクラスだった。昨季は全コンペティションで30ゴールを挙げ、苦戦を強いられていたリヴァプールをヨーロッパの舞台から遠ざけなかった。</h3>
      </div>
    </div>

    <!-- 12th Player -->
    <h2>12位 ロベルト・レヴァンドフスキ（ポーランド/バルセロナ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/レヴァンドフスキ.webp" alt="レヴァンドフスキ">
      </div>
      <div class="media-content">
        <h3>他に何を期待した？レヴァンドフスキは昨年、ベストの状態ではなかったが、それでもリーグ戦で23ゴールを決め、バルサを3年ぶりのリーグ優勝に導いた。彼は素晴らしい形で年齢を重ねている。</h3>
      </div>
    </div>

    <!-- 13th Player -->
    <h2>13位 ヤシン・ボヌ（モロッコ/アル・ヒラル）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/ブヌ.jpg" alt="ブヌ">
      </div>
      <div class="media-content">
        <h3>モロッコは2022年ワールドカップでサプライズとなったが、ボヌはその大きな理由だった。彼のヨーロッパリーグ決勝での活躍は、セビージャのタイトル獲得に大きく貢献した。</h3>
      </div>
    </div>

    <h2>14位 イルカイ・ギュンドアン（ドイツ/バルセロナ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/ギュンドアン.jpg" alt="ギュンドアン">
      </div>
      <div class="media-content">
        <h3>昨シーズンの終盤、ハーランドが稀に見る冷え込みに見舞われたとき、ギュンドアンがその穴を埋めてくれた。数年間、グアルディオラにとって絶大な存在だったギュンドアンは、33歳にしてようやく称賛を浴びるようになった。バルセロナは彼の獲得を喜んでいるだろう。</h3>
      </div>
    </div>

    
    <h2>15位 エミリアーノ・マルティネス（アルゼンチン/アストン・ヴィラ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/マルティネス.jpg" alt="マルティネス">
      </div>
      <div class="media-content">
        <h3>アルゼンチンのワールドカップ優勝はメッシのおかげだが、2度のPK戦で決定的なセーブを見せたマルティネスなしにはありえなかった。決勝戦の後半、コロ・ムアニとの1対1を阻止したシーンは、それだけでノミネートされる価値がある。</h3>
      </div>
    </div>

  </div>
</template>

<style scoped>
.title {
  text-align: center; /* タイトルを中央に配置 */
}

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
  max-height: 400px; /* Adjust the max-height as needed */
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