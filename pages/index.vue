<template>
  <div>
    <nav>
         <h1><sup></sup>STARFIELD</h1>
    </nav>
    <div class="content">
      <div class="text">
              <h1>STARFIELD</h1>
      <P>《Starfield》是 Bethesda Game Studios 在这 25 年里策划的首个新宇宙。该游戏开发团队创作了多款获奖作品，包括《The Elder Scrolls V: Skyrim》和《Fallout 4》。这款新一代角色扮演游戏将背景设定在茫茫宇宙。在这里，你可以创建任意角色，探索世界并体验前所未有的自由。踏上这趟史诗般的旅程，发掘人类的终极奥秘。</P>
      <p>STARFIELD.CC 是一个粉丝制作的网站 &copy;2022</p>
      <p>STARFIELD.CC IS A FANMADE WEBSITE</p>
      </div>

    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
<style lang="scss">
nav{
  height: 20px;
  background: #fff;
  padding: 40px 30px;

  h1{
    margin: 0;
  }
  sup{
    height: 5px;
    width: 5px;
    display: inline-block;
    border: 4px solid #333;
    margin-right: 5px;
  }
}
.content{
  color: #fff;
  text-align: center;
  
  display: flex;
  justify-content: center;
  .text{
    width: 600px;
 
  }
  p{

    display: inline-block;

  }
  font-size: 20px;
}
body{
  background: #333;
  margin: 0;
  font-family: 'Trade Gothic Bold Condensed No20', 'Arial Narrow', sans-serif;
}
@font-face {
  font-family: 'Trade Gothic Bold Condensed No20';
  src: url('/Trade Gothic Bold Condensed No. 20.otf');
}
</style>
