<template>
  <header class="header">
    <div class="c-head">
      <div class="c-wrapper">
        <div class="wrapper">
          <div class="title">中标金融</div>
          <div class="nav">
            <ul>
             <li data-hash="home" class="active">
                        <a href="#/home">首&nbsp;&nbsp;页</a>
                    </li>
                    <li data-hash="1">
                        <a href="#/list/1">产品中心</a>
                        <div class="c-nav-2nd">
                            <span>
                                <a href="#/detail/1-0">EID</a>/
                                <a href="#/detail/1-1">臻收银</a>/
                                <a href="#/detail/1-2">臻车贷</a>/
                                <a href="#/detail/1-3">臻e贷</a>
                            </span>
                        </div>
                    </li>
                    <li data-hash="2">
                        <a href="#/list/2">新闻动态</a>
                        <div class="c-nav-2nd">
                            <span>
                                <a href="#/detail/2-0">公司动态</a>
                                <a href="#/detail/2-0">行业新闻</a>
                            </span>
                        </div>
                    </li>
                    <li data-hash="3">
                        <a href="#/list/3">关于我们</a>
                        <div class="c-nav-2nd">
                            <span>
                                <a href="#/detail/3-0">公司介绍</a>
                                <a href="#/detail/3-0">联系我们</a>
                            </span>
                        </div>
                    </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>
<script>

export default {
}
</script>
<style scoped>
  .header {
    background-attachment: scroll;
    background-position: center 0;
    background-size: auto 820px;
    height: 127px;
    /* filter: blur(5px); */
  }
  .c-header {
    height: 122px;
    z-index: 99;
    border-bottom: 1px solid #ead4cf;
    border-bottom-color: hsla(0,0%,100%,.2);
    box-shadow: 0 0 15px rgba(0,0,0,.2);
    position: absolute;
    width: 100%;
    min-width: 1190px;
  }
  .c-wrapper {
    width: 1190px;
    margin: 0 auto;
    overflow: hidden;
  }
  .title {
     width: 238px;
    height: 53px;
    font-size: 26px;
    color: #fff;
    margin: 39px 0 32px;
  }
 .nav {
    font-size: 19px;
    line-height: 1.5;
    color: #fff;
    margin: 59px 0 0 515px;
 }
 .nav li.active, .nav li.hover {
    border-bottom: 3px solid #4bcfc0;
}
.nav li {
    float: left;
    margin: 0 31px;
}
</style>
