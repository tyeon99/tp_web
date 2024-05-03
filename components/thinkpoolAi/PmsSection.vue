<template>
  <div class="section">
    <div class="pmsSection">
      <div class="left">
        <div class="img">
          <img src="~/assets/img/pmsImg.png" alt="">
        </div>
        <div class="tag">
          <div class="tagWrap">
            <span>
              <img src="~/assets/img/pmsIcon01.png" alt="현대차증권">
            </span>
            <span>
              <img src="~/assets/img/pmsIcon02.png" alt="키움증권">
            </span>
            <span>
              <img src="~/assets/img/pmsIcon03.png" alt="대신증권">
            </span>
            <span>
              <img src="~/assets/img/pmsIcon04.png" alt="DB금융투자">
            </span>
          </div>
        </div>
      </div>
      <div class="right">
        <span class="num">AXR1</span>
        <div class="title">
          <strong>PMS</strong>(Picking & Portfolio <br> Management System)
        </div>
        <div class="txt ko">
          투자자가 <span>종목 또는 포트폴리오를 선택할 수 있도록 지원하는 시스템</span> <br>
          개인별 투자 성향이나 투자 목표에 따라 다양한 형태로 구성 가능 <br>
          기본적 분석 기반의 알고리즘, 차트/수급 기술적 분석 기반의 알고리즘, <br> 
          다양한 형태의 AI알고리즘까지 수용 가능한 <span>오픈형 시스템</span>
        </div>
        <div class="txt en">
          A system that allows investors to choose <br> 
          stocks or portfolios <br>
          Can be configured in a variety of ways to suit <br>
          individual investment preferences and investment goals <br>
          An open system that can accommodate <br> 
          algorithms based on fundamental analysis, <br>
          algorithms based on technical analysis, <br>
          and various types of AI algorithms.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  .pmsSection {
    @apply flex justify-center items-center gap-[100px];
  }

  .tag {
    @apply w-full flex justify-center items-center;
  }

  .tagWrap {
    @apply w-[322px] grid grid-cols-2 gap-[10px] place-content-center;
  }

  .tag span {
    @apply w-[156px] h-[45px] flex justify-center items-center rounded-[6px] border border-[#f0f0ff];
  }

  .num{
    @apply text-[#9395a1] text-[16px] font-normal leading-[20px] mb-[8px];
  }

  .title{
    @apply mb-[38px] text-[#141414] text-[48px] font-normal leading-[60px];
  }

  .txt{
    @apply text-[#444] text-[20px] font-normal leading-[25px];
  }

  .txt span{
    @apply text-[#5368ff];
  }
</style>
