<template>
  <div class="slide-container">
    
    <div class="self-content">
      <v-clicks>
        <div class="section" > </div>
        <div class="section">
          <h2>轉職前經歷</h2>
          <ul>
            <li>會計系</li>
            <li>一名爆肝審計查帳員</li>
            <li>對程式有熱情但沒有架構的學著 / 可以自稱excel界小天才ＸＤ</li>
          </ul>
        </div>
        <div class="section">
          <h2>轉職後</h2>
          <ul>
            <li>進入恩沛科技即將任滿一年</li>
            <li>默默會分享兩次</li>
            <li>熱衷於參與社群活動</li>
          </ul>
        </div>

        <div class="section">
          <h2>然後...</h2>
          <ul>
            <li>依然每天學習著</li>
          </ul>
        </div>
        

      </v-clicks>
    </div>

    <img src="/pika2.jpeg" alt="圖片描述" class="slide-image">
    
  </div>
</template>

<script>
export default {
  name: "SimpleIntroduction"
  // 在此處可以添加其他 Vue 的選項和邏輯
}
</script>

<style scoped>
@keyframes gradientBackground {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  background-size: 200% 200%;
  animation: gradientBackground 3s ease infinite;
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.1);
}
li:hover {
  transform: scale(1.05);
  transition: transform 0.2s;
}
h2, li {
  transition: all 0.3s;
}
h2:hover, li:hover {
  color: #2B90B6;
  text-shadow: 0px 0px 5px rgba(43, 144, 182, 0.8);
}
.slide-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.slide-image {
  height: auto;
  margin-left: 2rem;
}
.self-content {
  display: flex;
  
}
v-clicks {
  flex: 1;
}
v-clicks {
  display: flex;
  justify-content: space-between; /* 可以適當調整以達到想要的間隔效果 */
}


</style>
