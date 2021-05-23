<template>
  <div>
    <div class="banner">
      <div class="container">
        <h3 class="banner-name">行业动态</h3>
        <p>
          <a href="javascript:;">首页</a>
          <span>&gt;</span>
          <a href="javascript:;">资讯动态</a>
          <span>&gt;</span>
          <a href="javascript:;">行业动态</a>
        </p>
      </div>
    </div>
    <div class="tab ">
      <ul class="clearfix container">
        <li>
          <a href="javascript:;">行业动态</a>
        </li>
        <li>
          <a href="javascript:;" class="active">朗朗动态</a>
        </li>
        <li>
          <a href="javascript:;" class="active">媒体报道</a>
        </li>
        <li>
          <a href="javascript:;">公益活动</a>
        </li>
      </ul>
    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.banner {
  background: url('../assets/bg.jpg') no-repeat center;
  background-size: 100% 100%;
  color: #ffffff;
  padding: 86px 0;
  .banner-name {
    font-size: 30px;
    font-weight: 300;
    padding-bottom: 16px;
  }
  p {
    font-size: 0;
    a {
      font-size: 12px;
      color: #ffffff;
    }
    span {
      display: inline-block;
      font-size: 12px;
      color: #ffffff;
      margin: 0 5px;
    }
  }
}
.tab {
  border-bottom: 1px solid #f1f1f1;
  ul {
    li {
      float: left;
      margin-right: 4px;
      a {
        display: block;
        font-size: 14px;
        font-weight: bold;
        line-height: 49px;
        padding: 0 17px;
        &.active {
          color: #21b8c6;
          border-bottom: 1px solid #21b8c6;
          margin-bottom: -1px;
        }
      }
    }
  }
}
</style>