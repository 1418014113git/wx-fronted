<template>
  <div id="app">
    <el-container class="article">
      <el-header class="elheader">
        <div class="logo">
          <a href=""
             class="btn">
            登录
          </a>
          <a href=""
             class="btn">
            注册
          </a>
        </div>
      </el-header>
      <el-main class="main">
        <div class="title">
          <span class="titleSpan">我们的爱情</span>
        </div>
        <div class=heart>♥ ♥</div>
        <div>
          <el-row class="mainImg">
            <el-col :span="11"
                    style="text-align:right">
              <!--主容器-->
              <div class="box">
                <img :src="boyUrl"
                     width="320px"
                     height="320px" />
                <!-- 内容 -->
                <div class="box-inner-content">
                  <h3 class="title">boyName</h3>
                </div>
              </div>
            </el-col>
            <el-col :span="2">
              <span class="and">&</span>
            </el-col>
            <el-col :span="11"
                    style="text-align:left">
              <!--主容器-->
              <div class="box"
                   style="float:left">
                <img :src="girlUrl"
                     width="320px"
                     height="320px" />
                <!-- 内容 -->
                <div class="box-inner-content">
                  <h3 class="title">girlName</h3>
                </div>
              </div>
            </el-col>
          </el-row>
        </div>
        <br>
        <br>
        <!--第二个模块-->
        <div class="title">
          <span class="titleSpan">我们的幸福时刻</span>
        </div>
        <div class="heading">
          <p>爱情时刻是特殊的，它值得被记录下来，将永远铭记！这是我们一些重要和幸福的时刻。爱情时刻是特殊的，它值得被记录下来，将永远铭记！这是我们一些重要和幸福的时刻。爱情时刻是特殊的，它值得被记录下来，将永远铭记！这是我们一些重要和幸福的时刻。</p>
        </div>

      </el-main>
    </el-container>
  </div>
</template>
<script>

export default {
  data () {
    return {
      logoUrl: require('./assets/logo.png'),
      boyUrl: require('./assets/boy.jpeg'),
      girlUrl: require('./assets/girl.jpeg'),
      activeIndex: '1',
      show: 'false'
    }
  },
  methods: {}
}
</script>

<style scoped>
@import "./assets/css/main.css";
</style>
