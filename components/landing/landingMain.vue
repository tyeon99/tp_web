<template>
  <div class="section">
    <div class="landingSection">
      <div class="landingMainBg">
        <video :src="videoSrc" type="video/mp4" autoplay muted loop>배경비디오</video>
      </div>
      <div class="landingMain">
        <div class="mainTitle ko">
          AI 투자금융 테크기업 씽크풀
        </div>
        <div class="mainTitle en">
          AI Investment Finance Tech Company THINKPOOL
        </div>
        <div class="mainTxt ko">
          씽크풀은 데이터와 AI시대, 초지능형 과학적 의사결정을 지원하는 지식기업입니다.
        </div>
        <div class="mainTxt en">
          ThinkPool is a knowledge company that supports super-intelligent scientific decision-making in the era of data
          and AI
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return{
      videoSrc: '/tp_web/video/landingMainBg.mp4',
    }
  },
}
</script>

<style scoped>
  .landingSection{
    @apply relative;
  }

  .landingMainBg{
    @apply w-full;
  }

  .landingMainBg video{
    @apply w-full h-[1080px];
  }

  .landingMain{
    @apply w-full text-center absolute top-[45%];
  }

  .mainTitle{
    @apply text-[#fff] text-[64px] font-bold leading-[96px] mb-[9px];
  }

  .mainTxt{
    @apply text-[#fff] text-[20px] font-medium leading-[30px];
  }
</style>
