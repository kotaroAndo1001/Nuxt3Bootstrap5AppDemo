<template>
    <div>
      <h1 class="title">Ballon D'or 2023年ランキング</h1>
      <h2>【欧州・海外サッカー】</h2>
      <p>10月30日にフランス・パリで行われた2023年バロンドールセレモニーでバロンドール受賞者が発表された。</p>
      <h2>1位　リオネル・メッシ（アルゼンチン／パリ・サンジェルマン→インテル・マイアミ）</h2>
      <div class="media">
        <div class="media-image">
          <img src="images/メッシ.jpg" alt="メッシ">
        </div>
        <div class="media-content">
          <h3>メッシは2022-23シーズン、当時所属していたパリ・サンジェルマンで公式戦21ゴール20アシストを記録してリーグアン優勝に貢献。さらに、2022年W杯では、ゴールデンボール（大会最優秀賞）に輝く活躍を見せて主将として36年ぶりとなる優勝を母国にもたらした。</h3>
        </div>
      </div>
      <h2>2位　アーリング・ハーランド（ノルウェー／マンチェスター・シティ）</h2>
      <div class="media">
        <div class="media-image">
          <img src="images/ハーランド.webp" alt="ハーランド">
          <div class="media-content">
            <h3>昨シーズン、シティで52ゴールを挙げたハーランドは、最優秀賞を逃したことを悔やんでいるかもしれない。彼は、どうにか調子を上げてきたチームに変化をもたらした才能だった。そして、その勢いは衰えることを知らない。</h3>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .title {
    text-align: center;
  }
  .media {
    display: flex;
    align-items: center;
  }
  .media-image {
    flex: 0 0 300px; /* 画像のベースサイズを300pxに設定 */
    margin-right: 20px;
    max-width: 300px; /* 画像の最大幅を300pxに設定 */
  }
  .media-image img {
    width: 100%; /* 画像の幅をコンテナに合わせて調整 */
    height: auto; /* 画像の高さを自動調整してアスペクト比を維持 */
    object-fit: cover; /* 画像がコンテナのサイズに合わせて切り取られる */
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
      flex-basis: auto; /* モバイルビューでは画像のサイズを自動に戻す */
      max-width: 100%; /* モバイルビューでは画像の最大幅を100%に設定 */
    }
  }
  </style>
  
  