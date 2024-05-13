<template>
  <div class="NationalRd">
    <div class="swiper rdSwiper">
      <div class="rdWrap swiper-wrapper">
        <div class="swiper-slide">
          <div class="titleSpan ko">국가R&D</div>
          <div class="titleSpan en">National R&D</div>
          <div class="title ko">서비스 산업융합 고도화 사업</div>
          <div class="title en">Svc Industry Convergence Advancement Project</div>
          <div class="rdContent">
            <div class="imgWrap">
              <div class="img">
                <img src="~/assets/img/nationalRdImg01.png" alt="">
              </div>
            </div>
            <div class="txtWrap">
              <div>
                <div class="title ko">
                  2023 <br>
                  지식서비스 <br>
                  서비스산업융합고도화 과제
                </div>
                <div class="title en">
                  2023<br>
                  Challenges of Advancing <br>
                  Convergence in the Knowledge <br>
                  Services Industry
                </div>
                <div class="subTitle ko">
                  액티브 시니어 생애설계와 <br>
                  자기계발 지원을 위한
                  런케이션서비스 개발
                </div>
                <div class="subTitle en">
                  Developed Launch Svc for Active Senior <br>
                  Life Planning & Self-Dev
                </div>
              </div>
              <div>
                <div class="txt ko">
                  <strong>개발기간</strong> <br>
                  2023년 월 ~ 2025년 11월<br><br>

                  <strong>개발예산</strong><br>
                  30억원 투자<br><br>

                  <strong>주관기관</strong><br>
                  ㈜씽크풀<br><br>

                  <strong>참여기관</strong><br>
                  (사)금융과 행복 네트워크<br>
                  (주)프로눔<br>
                  한국전기통신연구원<br>
                  상명대 (시니어 휴먼 팩터 연구기관)
                </div>
                <div class="txt en">
                  <strong>Development Period</strong> <br>
                  2023 to 2025<br><br>

                  <strong>Development budget</strong><br>
                  30 billion KRW<br><br>

                  <strong>Organizing Authority </strong><br>
                  Thinkpool.co.,ltd<br><br>

                  <strong>Participating organizations </strong><br>
                  Finance and Happiness Network <br>
                  Pronum.co.,ltd<br>
                  ETRI <br>
                  Sangmyung Univ <br>
                  (Senior Human Factors Research Institute )
                </div>
                <div class="icon">
                  <img src="~/assets/img/nationalRdIcon01.png" alt="">
                </div>
              </div>
            </div>
          </div>
        </div>
        <NationalRd02></NationalRd02>
        <NationalRd03></NationalRd03>
        <NationalRd04></NationalRd04>
      </div>
      <div class="swiper-button-next"></div>
      <div class="swiper-button-prev"></div>
    </div>
  </div>

</template>

<script>
export default {
  mounted() {
    new window.Swiper(".rdSwiper",{
      slidesPerView: '1',
      spaceBetween: 100,
      loop: true,
      navigation: {
        nextEl: '.swiper-button-next',
        prevEl: '.swiper-button-prev',
      }
    });
  }
}
</script>

<style scoped>
  .NationalRd{
    @apply flex justify-center items-center px-[100px];
  }

  .swiper-button-prev, .swiper-button-next{
    @apply text-[#ccc] w-[109px] h-[109px];
  }
</style>
