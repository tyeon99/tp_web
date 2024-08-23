<template>
  <div class="content">
    <CategoryNav
      :categoryIndex="categoryIndex"
      :activeIndex="selectedIndex"
      class="rassiBg"
    ></CategoryNav>
    <!-- // -->

    <div class="section rassiBg">
      <div class="landingRassi">
        <div class="titleSpan">RASSI Trading Assistant</div>
        <div class="sectionTitle">
          <NuxtLink to="/thinkpoolAi/axRassi" class="ko">라씨매매비서</NuxtLink>
          <NuxtLink to="/thinkpoolAi/axRassi" class="en"
            >RASSI Trading Assistant</NuxtLink
          >
        </div>
        <div class="sectionSubTitle ko">
          수익은 극대화, 손실은 최소화 ‘AI매매신호’
        </div>
        <div class="sectionSubTitle en">
          'AI trading signal' to maximize profits and minimize losses
        </div>
      </div>
      <!-- // -->

      <div class="rassiContent">
        <div class="mainImg">
          <img src="~/assets/img/rassiAss.png" alt="" width="946">
        </div>
        <div class="txtBox box01">
          <div class="title ko">우수한 매매 성과</div>
          <div class="title en">Excellent trading performance</div>
          <div class="txt ko">
            승률 83%, 종목 당 연 평균 수익률 18.7% 기록 <br />
            5년 10억건 이상의 빅데이터 기반 <br />
            10만번 이상의 매매로 데이터 신뢰성 확보 <br />
            상승구간 집중 매매로 수익 극대화 <br />
            하락구간 포지션 미보유로 위험 우선 관리
          </div>
          <div class="txt en">
            83% Winning Rate and 18.7% Average Annual Return Per Stock<br />
            Secure data reliability with more than 100,000 sales based <br />
            on over 1 billion big data over 5 years<br />
            Maximize profits through intensive selling of rising sections<br />
            Risk-first management without holding a falling section position
          </div>
        </div>
        <div class="txtBox box02">
          <div class="title ko">금융부분 최고 매출</div>
          <div class="title en">The highest sales in the financial sector</div>
          <div class="txt ko">
            구글 플레이스토어 주식 정보 앱 중 압도적 매출 1위<br />
            구글플레이스토어 + 애플앱스토어 25만 다운로드<br />
            평균 별점 4점대, 리뷰 500여건 이상
          </div>
          <div class="txt en">
            The overwhelming number of Google Play Store stock information apps<br />
            Google Play Store, Apple App Store Downloads a Total of 250,000<br />
            Average 4-star rating, more than 500 reviews<br />
          </div>
        </div>
        <div class="txtBox box03">
          <div class="title ko">개인화된 종목관리</div>
          <div class="title en">Personalized stock management</div>
          <div class="txt ko">
            개인별 매수가에 맞춘 맞춤형 AI매도신호 제공 <br />
            개인별 종목 포켓 제공 및 다양한 AI정보 제공
          </div>
          <div class="txt en">
            Provides customized AI selling signals tailored to individual purchase prices <br />
            Provide personal item pockets and various AI information
          </div>
        </div>
      </div>

      <!-- <div class="rassiContent">
        <img src="~/assets/img/rassiAss.png" alt="" width="1369" class="ko">
        <img src="~/assets/img/rassiAss_en.png" alt="" width="1369" class="en">
      </div> -->
    </div>
  </div>
</template>
<script>
export default {
  layout: 'default',
  data() {
    return {
      categoryIndex: 1,
      selectedIndex: 11,
    }
  }
}
</script>
<style scoped>
.rassiBg{
  @apply bg-[#EFF2FB];
}
.landingRassi {
  @apply w-full text-center;
}
.sectionTitle{
  @apply mt-2
}
.section{
  @apply flex-col justify-between gap-[50px] py-[90px];
}
.rassiContent{
  @apply relative mt-[100px] flex justify-center;
}
.txtBox{
  @apply absolute;
}
.txtBox.box01{
  @apply text-right left-[-210px] top-[-45px];
}
.txtBox.box02{
  @apply text-left right-[-243px] top-[-54px];
}
.txtBox.box03{
  @apply text-left right-[-243px] bottom-[39px];
}
.txtBox .title{
  @apply text-[#5368ff] text-[36px] font-bold mb-[20px];
}
.txtBox .txt{
  @apply text-[#444] text-[20px] font-normal;
}
.txtBox .title.en{
  @apply text-[24px];
}
.txtBox .txt.en{
  @apply text-[16px];
}
</style>
