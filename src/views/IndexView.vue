<template>
  <div>
    <a-carousel :autoplay="true">
      <div class="carousel-con">
        <div class="pc">
          <img src="../assets/bannerNew.png" alt="" class="img1" />
          <div class="btn">
            <a-button size="large" shape="round" class="btn1"
              >购买软件</a-button
            >
            <a-button size="large" shape="round" class="btn1"
              >购买咨询</a-button
            >
            <a-button size="large" shape="round" class="btn1"
              >下载使用</a-button
            >
          </div>
        </div>
        <div class="mobile">
          <div></div>
          <div>
            <img src="../assets/bannerMobile.png" alt="" class="img2" />
            <div class="mobile-btn">
              <a-button size="large" shape="round" class="btn2"
                >立即下载使用</a-button
              >
              <a-button size="large" shape="round" class="btn2"
                >视频简介</a-button
              >
            </div>
          </div>
        </div>
      </div>
    </a-carousel>
    <div class="overview overview-primary overview-header">
      <h1 class="overview-title">项目成功，从进度开始</h1>
      <div class="horizontal-divide-line"></div>
      <div class="overview-desc">
        快速有效制定合理的进度计划，自动计算最短工期、推演最优项目方案，规避现场冲突
      </div>
      <p class="overview-desc">
        辅助项目计算关键线路变化，及时准确预警风险，指导纠偏，提供索赔依据
      </p>
      <p class="overview-desc">
        辅助项目计算关键线路变化，及时准确预警风险，指导纠偏，提供索赔依据
      </p>
      <p class="overview-desc">
        辅助项目计算关键线路变化，及时准确预警风险，指导纠偏，提供索赔依据
      </p>
    </div>
    <div class="overview overview-wrapper">
      <h1 class="overview-title">
        一表多图（表格\横道图\网络图）编制方式让计划编制效率提高10
      </h1>
      <p class="overview-desc">
        会用Excel就会用斑马进度计划！可以在表格中做计划，双代号网络图和横道图同步生成，也可以直接绘制双代号网络图\横道图
      </p>
      <p class="overview-desc">
        一种输入多种输出，通过双代号网络计划保证计划逻辑关系和关键线路完整性和正确性，指导项目时刻抓住主要矛盾！
      </p>
      <div class="img">
        <img class="img1" src="../assets/overview-edit.2a7078f1.png" alt="" />
        <a-button size="large" type="primary" class="img-res" style="padding: 0 30px" shape="round">立即下载使用</a-button>
      </div>
    </div>
    <div class="overview">
      <h1 class="overview-title">导入PROJECT计划，横道图秒变双代号网络图</h1>
      <p class="overview-desc" style='color: black'>将Project编制的计划导入到斑马进度计划软件中，可以自动生成双代号网络图，直观发现Project计划的逻辑关系错漏问题，</p>
      <p class="overview-desc" v-bind="animation" style='color: black'>
        检查关键路径和工期是否正确，为编制高质量进度计划保驾护航！
      </p>
      <div class="img">
        <img class="img1" src="../assets/overview-edit.2a7078f1.png" alt="" />
        <a-button size="large" type="primary" class="img-res" style="padding: 0 30px" shape="round">立即下载使用</a-button>
      </div>
    </div>

    <div class="overview overview-primary overview-visual">
      <h1 class="overview-title" v-bind="animation">
        全新一代形象进度计划，穿插施工方案分析与优化的必备神器！
      </h1>
      <p class="overview-desc" v-bind="animation">
        时间+空间+逻辑关系三位一体，直观易懂，是工程多方案比选的必备神器！尤其适用于穿插施工方案分析与优化！
      </p>
      <div class="overview-desc">
        <div style="max-width: 644px; margin: auto;">
          <p class="overview-desc-box"> 投标时，真实反映您高超的管理水平和技术创新能力</p>
          <p class="overview-desc-box">
            施工时，是给领导汇报和队伍交底的好帮手！是施工方案设计与优化的必备神器
          </p>
        </div>
        <img
        src="../assets/overview-edit.2a7078f1.png"
        class="img-responsive"
      />
      </div>
      <div class=""></div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.mobile-btn {
  position: absolute;
  top: 88%;
  width: 100vw;
  /* left: 22%; */
  z-index: 999;
  padding: 0 30px;
  text-align: center;
  z-index: 999;
}
.pc {
  display: block;
}
.carousel-con {
  position: relative;
  min-width: 375px;
  margin-bottom: -6px;
}
.btn {
  position: absolute;
  top: 75%;
  left: 22%;
  z-index: 999;
  padding: 0 30px;
}
.btn .btn1 {
  margin: 0 15px;
  color: #fff;
  background-color: #ff9832;
  background-image: linear-gradient(to bottom, #f7a152 0%, #ec821f 100%);
}
.btn .btn1:hover {
  margin: 0 15px;
  color: #fff;
  background-color: #ff9832;
  background-image: linear-gradient(to bottom, #f7a152 0%, #ec821f 100%);
}

.img1 {
  width: 100%;
  height: 100%;
  min-height: 100px;
}
.mobile {
  display: none;
}
.img2 {
  width: 100%;
  height: 100%;
  min-height: 100px;
}
.overview {
  display: flex;
  flex-direction: column;
  justify-content: center;

  align-items: center;
  background-repeat: no-repeat;
  background: white;
  background-position: center;
  background-size: auto;
}

.overview-primary {
  background: rgba(16, 120, 252, 1);
}
.overview-header {
  padding: 40px 0;
  background-size: auto;
  background-image: url(../assets/overview-header-bg.png);
  color: white;
}

.overview-primary .overview-title {
  font-size: 32px;
  text-align: center;
  width: 100%;
  color: white;
  font-size: 32px;
}
.horizontal-divide-line {
  width: 60px;
  height: 4px;
  background-color: white;
  margin: 0px auto 20px auto;
}
.overview-desc {
  font-size: 16px;
  text-align: center;
  width: 100%;
  margin-bottom: 15px;
  color: white;
}
.overview-wrapper {
  padding-top: 40px;
}
.overview-wrapper .overview-desc {
  color: black;
}
.img {
  text-align: center;
}
.img1 {
  display: block;
}
.overview-visual {
  padding-top: 40px;
  background-size: contain;
}
.overview-desc-box{
border: 1px solid rgba(255, 255, 255, 1);
opacity: 0.9;
border-radius: 4px;

}
.overview-desc-box{
  background: #0092f7;
  padding: 5px;
  border-radius: 4px;
  opacity: 0.9;
  border: 1px solid rgba(255, 255, 255, 1);
}
.img-responsive {
  display: block;
  max-width: 100%;
  margin: 0 auto;
}

@media (max-width: 1300px) {
}
@media (max-width: 1100px) {
}
@media (min-width: 769px) {
}

@media screen and (max-width: 768px) {
  .mobile {
    display: block;
    width: 100vw;
  }
  .pc {
    display: none;
  }
  .overview-title {
    font-size: 20px;
  }
  .hidden-small {
    display: none;
  }
}
@media (max-width: 600px) {
  .pc {
    display: none;
  }
  .overview-title {
    font-size: 18px;
  }
  .overview-desc {
    font-size: 14px;
  }
}
</style>
