<template>
  <div id="app" class="Home">
    <div class="centered-text">开心的木瓜</div>

    <aside>
      <!-- 侧边栏内容 -->
    </aside>

    <footer>
      <div class="footer-content">
        <a href="https://beian.miit.gov.cn/" target="_blank">
          京ICP备2024041881号-1
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  position: fixed; /* 固定在底部 */
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #fff; /* 背景颜色，可根据需要修改 */
  border-top: 1px solid #ccc; /* 顶部的分隔线 */
}

.footer-content {
  padding: 10px 0; /* 上下内边距 */
  text-align: center; /* 文本居中 */
  background: url("@/assets/background.png");
}

#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;

  /* 设置背景图片 */
  background-image: url("@/assets/background.png"); /* 确保路径与您的图片文件匹配 */
  background-size: contain; /* 覆盖整个容器 */
  background-position: center; /* 居中显示 */
  min-height: 100vh; /* 最小高度为视口高度 */
  width: 100%; /* 设置宽度为100% */
}

.centered-text {
  font-family: "Cursive", sans-serif; /* 更艺术的字体 */
  font-size: 50px; /* 增大字体大小 */
  color: #4a7c59; /* 艺术字体颜色 */
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); /* 添加文本阴影 */
  position: absolute;
  font-weight: lighter;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

/* 可以添加更多样式来美化footer */
</style>
