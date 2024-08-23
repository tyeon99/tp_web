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
        <div class="titleSpan">Collaborate on Algorithms</div>
        <div class="sectionTitle">
          <NuxtLink to="/thinkpoolAi/axRassi" class="ko">알고리즘 협업</NuxtLink>
          <NuxtLink to="/thinkpoolAi/axRassi" class="en"
            >Collaborate on Algorithms</NuxtLink
          >
        </div>
        <div class="sectionSubTitle ko">
          AI 시장 예측력, 퀀트의 종목 선별을 통한 알고리즘 간 시너지 도모
        </div>
        <div class="sectionSubTitle en">
          AI Market Prediction & Quant's Stock Picking to Create Synergy Between Algorithms
        </div>
      </div>
      <!-- // -->

      <div class="rassiContent">
        <div class="img">
          <img src="~/assets/img/c_algorithms.png" alt="" width="1093" class="ko">
          <img src="~/assets/img/c_algorithms_en.png" alt="" width="1093" class="en">
        </div>
        <div class="contentTxt mb-[40px]">
          <div class="title">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" width="27" height="27" viewBox="0 0 27 27" fill="none">
                <path d="M13.5 24.75C19.7134 24.75 24.75 19.7134 24.75 13.5C24.75 7.28663 19.7134 2.25 13.5 2.25C7.28663 2.25 2.25 7.28663 2.25 13.5C2.25 19.7134 7.28663 24.75 13.5 24.75Z" fill="#5368FF"/>
              </svg>
            </span>
            <p class="ko">퀀트 알고리즘</p>
            <p class="en">
              Quantitative investment strategies
            </p>
          </div>
          <div class="txt ko">
            자동화된 공시 수집 시스템을 바탕으로 실적과 시장 데이터를 전문가의 통찰력으로 판단하고 데이터로 검증한 투자 알고리즘 <br />
            30년 이상의 연구 경력을 가진 투자 전문가의 투자철학과 실제 시장에서 15년 이상의 투자성과를 가진 안정적인 운영방식
          </div>
          <div class="txt en">
            Investment algorithms that judge performance and market data with expert insights and <br />
            verify them with data based on automated disclosure collection systems
          </div>
        </div>
        <div class="contentTxt">
          <div class="title">
            <span>
              <svg xmlns="http://www.w3.org/2000/svg" width="27" height="27" viewBox="0 0 27 27" fill="none">
                <path d="M13.5 24.75C19.7134 24.75 24.75 19.7134 24.75 13.5C24.75 7.28663 19.7134 2.25 13.5 2.25C7.28663 2.25 2.25 7.28663 2.25 13.5C2.25 19.7134 7.28663 24.75 13.5 24.75Z" fill="#5368FF"/>
              </svg>
            </span>
            <p class="ko">
              AI 알고리즘
            </p>
            <p class="en">
              AI Algorithms
            </p>
          </div>
          <div class="txt ko">
            대용량의 빅데이터를 기반으로 딥러닝, 머신러닝 알고리즘을
            활용하여 사람이 생각하지 못하는 부분을 공략하는 투자 알고리즘 <br />
            당사의 오랜 기간 축적된 정형데이터 및 뉴스, 리포트, 공시 등의
            비정형 데이터를 함께 활용하는 투자 인사이트를 제공
          </div>
          <div class="txt en">
            An investment algorithm that uses deep learning and machine learning algorithms based on large amounts of <br />
            big data to target areas that humans do not think about<br />
            Provides investment insights that combine our long-established structured data and unstructured data such as <br />
            news, reports, and disclosures
          </div>
        </div>
      </div>

      <!-- <div class="rassiContent">
        <img src="~/assets/img/c_algorithms.png" alt="" width="1093" class="ko">
        <img src="~/assets/img/c_algorithms_en.png" alt="" width="1093" class="en">
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
      selectedIndex: 12,
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
.contentTxt .title{
  @apply flex gap-[13px] justify-start items-center text-[#141414] font-normal text-[28px] mb-[15px];
}
.contentTxt .txt{
  @apply text-[#141414] text-[20px] font-normal leading-[30px];
}
</style>
