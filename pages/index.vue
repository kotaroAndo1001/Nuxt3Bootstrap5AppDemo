<template>
  <div>
    <h1 class="title">Ballon D'or 2023年ランキング</h1>
    <h2>〇欧州・海外サッカー</h2>
    <p>10月30日にフランス・パリで行われた2023年バロンドールセレモニーでバロンドール受賞者が発表された。</p>

    <h1>＜1~5位＞</h1>
    
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
      </div>
      <div class="media-content">
        <h3>昨シーズン、シティで52ゴールを挙げたハーランドは、最優秀賞を逃したことを悔やんでいるかもしれない。彼は、どうにか調子を上げてきたチームに変化をもたらした才能だった。そして、その勢いは衰えることを知らない。</h3>
      </div>
    </div>

    <h2>3位　キリアン・エンバペ（フランス／パリ・サンジェルマン）</h2>
    <div class="media">
      <div class="media-image">
        <img src="images/エンバぺ.jpg" alt="エンバぺ">
      </div>
      <div class="media-content">
        <h3>ワールドカップ決勝でのハットトリックはそうそうあるものではない。エンバペはそれをいとも簡単にやってのけた。彼はクラブレベルでも悪くなく、リーグ・アンで29得点を挙げてパリを優勝に導いた。今シーズン、新体制となったPSGで開幕から大活躍しており、来シーズンの受賞も十分に狙えるだろう。</h3>
      </div>
    </div>

    <h2>4位　ケヴィン・デ・ブライネ（ベルギー／マンチェスター・シティ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="images/デブライネ.jpg" alt="デブライネ">
      </div>
      <div class="media-content">
        <h3>ハーランドはシティの見出しを飾ったが、ペップ・グアルディオラのチームを引っ張ったのは、またしてもデ・ブライネだった。彼らは過去6回のプレミアリーグ優勝のうち5回を制し、2022-23シーズンには3冠を達成している。</h3>
      </div>
    </div>

    <h2>5位 ロドリ（スペイン／マンチェスター・シティ）</h2>
    <div class="media">
      <div class="media-image">
        <img src="/images/ロドリ.webp" alt="ロドリ">
      </div>
      <div class="media-content">
        <h3>10番のように攻撃でき、センターバックのように守れる6番のロドリは、昨年のマン・シティで最も重要な選手だったことは間違いない。チャンピオンズリーグ決勝での決勝ゴールも悪くなかった。</h3>
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
    flex: 0 0 400px;
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





  
  