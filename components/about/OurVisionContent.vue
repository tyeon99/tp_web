<template>
  <div class="ourVisionContent">
    <div class="categoryContent">
      <div class="contentHead ko">
        <em>[</em> <span>AI 투자금융 테크기업</span> <em>]</em>
      </div>
      <div class="contentHead en">
        <em>[</em> <span>AI Investment Finance Tech Company</span> <em>]</em>
      </div>

      <div class="visionImg">
        <img src="~/assets/img/n_vision.png" alt="" width="366" class="ko">
        <img src="~/assets/img/vision_en.png" alt="" width="366" class="en">
      </div>

      <div class="contentTitle ko">
        데이터와 AI시대, 초지능형 과학적 의사결정을 지원하는 지식기업
      </div>
      <div class="contentTitle en">
        Data and AI Era, Knowledge Companies Support <br />
        Superintelligent Scientific Decision-Making
      </div>

      <div class="subContent">
        <div class="subTitle ko">철학</div>
        <div class="subTitle en">Philosophy</div>
        <div class="subBoxGroup">
          <div class="box">
            <div class="title ko">직원</div>
            <div class="txt ko">'직원의 자아 성장을 위한 <br /> 즐거운 삶의 장'</div>
            <div class="title en">Employee</div>
            <div class="txt en">‘A fun place to live for the <br /> self-growth of employees’</div>
          </div>
          <div class="box">
            <div class="title ko">고객</div>
            <div class="txt ko">'고객의 만족이 <br />곧 씽크풀의 가치'</div>
            <div class="title en">Customer</div>
            <div class="txt en">‘Customer satisfaction is<br /> the value of Thinkpool’</div>
          </div>
          <div class="box">
            <div class="title ko">사회</div>
            <div class="txt ko">'사회적 상상력을 키우고 실현, <br />인재 육성, 봉사를 통한<br /> 사회 환원'</div>
            <div class="title en">Society</div>
            <div class="txt en">‘Developing and realizing social<br /> imagination, fostering human<br /> resources, and returning to society<br /> through service’</div>
          </div>
        </div>
      </div>

      <!-- <div>
        <img src="~/assets/img/n_vision.png" alt="" width="885" class="ko">
        <img src="~/assets/img/vision_en.png" alt="" width="885" class="en">
      </div> -->
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  .categoryContent{
    @apply flex-col gap-[60px] pt-0 items-center;
  }

  .contentHead{
    @apply text-black text-[48px] font-light flex justify-start items-center gap-[14px];
  }

  .contentHead em{
    @apply font-bold text-[#d9d9d9];
  }

  .contentTitle::before{
    @apply left-[-20px] top-[-12px];
  }

  .contentTitle::after{
    @apply bottom-[-10px] right-[-20px];
  }

  .contentTitle.en::after{
    @apply right-[40px];
  }

  .subTitle{
    @apply text-[#141414] text-[28px] font-bold leading-[36px] mb-[20px] text-center;
  }

  .subBoxGroup{
    @apply flex justify-center items-center gap-[30px];
  }

  .subBoxGroup .box{
    @apply w-[275px] h-[188px] p-[28px_0px] rounded-[5px] bg-[#eff2fb] text-center flex flex-col justify-center items-center gap-[20px];
  }

  .subBoxGroup .box .title{
    @apply text-[#141414] text-[24px] font-bold leading-[18px];
  }

  .subBoxGroup .box .txt{
    @apply text-[#444] text-[16px] font-normal leading-[25px];
  }
</style>
