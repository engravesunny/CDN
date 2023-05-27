<template>
  <div class="stack">
    <div class="top">
      <div class="title">技术栈</div>
    </div>
    <div class="main">
      <div class="left">
        <p>
          1.精通使用<span class="strong">H5+CSS3</span
          >对页面进行布局(成功的页面仔)
        </p>
        <p>
          2.熟悉使用原生 <span class="strong">JavaScript</span> 、<span
            class="strong"
            >ES6</span
          >、<span class="strong">Ajax</span>、
          <span class="strong">Node.js</span>，熟练使用<span class="strong"
            >axios</span
          >、熟悉<span class="strong">Promise</span>
        </p>
        <p>
          3.熟练使用<span class="strong">Vue全家桶</span
          >及其周边生态进行搭建项目，有相关项目经验，了解
          <span class="strong">React</span> 语法，了解<span class="strong"
            >redux</span
          >
        </p>
        <p>
          4.熟练使用 <span class="strong"> Element-plus、Vant</span> 等组件库
        </p>
        <p>
          5.熟悉
          <span class="strong">Webpack、Vite、Rollup、esbuild</span>
          等等打包工具
        </p>
        <p>6.熟练编写前端标准代码，熟悉浏览器兼容问题解决(IE10以下另当别论)</p>
        <p>7.熟悉 <span class="strong">git操作</span> ，有团队合作经验</p>
      </div>
      <div class="right">
        <img src="https://bu.dusays.com/2023/04/09/643291fe62647.jpg" alt="" />
      </div>
    </div>
    <div class="about">
      <div class="top">
        <div class="title">我的人格</div>
      </div>
      <div class="main">
        <div class="left"></div>
        <div class="right"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
.stack {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 0px 10px 10px;
  .top {
    width: 100%;
    height: 10%;
    padding: 0 10px;
    border-radius: 10px;
    display: flex;
    align-items: center;
    .title {
      font-size: 30px;
    }
  }
  .main {
    font-size: 16px;
    font-weight: 100;
    width: 100%;
    display: flex;
    justify-content: space-between;
    .left {
      padding: 20px;
      width: 68%;
      height: 100%;
      display: flex;
      flex-direction: column;
      border-radius: 10px;
      box-shadow: 1px 1px 10px 2px rgba(0, 0, 0, 0.2);
      p {
        line-height: 25px;
        .strong {
          padding: 1px 3px;
          border-radius: 5px;
          background-color: rgb(97, 197, 255);
        }
      }
    }
    .right {
      width: 30%;
      box-shadow: 1px 1px 10px 2px rgba(0, 0, 0, 0.2);
      border-radius: 10px;
      overflow: hidden;
      position: relative;
      img {
        position: absolute;
        top: 0;
        left: 50%;
        height: 100%;
        transform: translate(-50%);
      }
    }
  }
  .about {
    margin-top: 10px;
    width: 100%;
    flex: 1;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    .top {
      width: 100%;
      padding: 20px 0;
      .title {
        font-size: 30px;
      }
    }
    .main {
      width: 100%;
      flex: 1;
      display: flex;
      justify-content: space-between;
      .left {
        width: 30%;
      }
      .right {
        width: 68%;
      }
    }
  }
}
</style>