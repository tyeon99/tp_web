<template>
  <div class="content">
    <CategoryNav
      :categoryIndex="categoryIndex"
      :activeIndex="selectedIndex"
    ></CategoryNav>
    <div class="csr">
      <div class="csrTitle">
        <strong class="en">Corporate Social Responsibility</strong>
        <strong class="ko">사회공헌활동</strong>
      </div>
      <!-- // -->
      <div class="csrContent">
        <div class="visual">
          <img src="~/assets/img/csr.png" alt="" width="989">
        </div>
        <div class="txt">
          <div>
            <strong class="ko">봉사 및 후원</strong>
            <strong class="en">Service and sponsorship</strong>
            <span><em>2023년 5월</em> 노을공원 나무심기 봉사 및 후원</span>
            <span><em>2022년 3월</em> ‘나의 걸음’이 기부가 되는 &lt;만보걷기 챌린지&gt;로 봉사단체 후원<br>
            <span class="line">(이태석재단, 다일 밥퍼사랑운동본부, 도산아카데미)</span></span>
            <span><em>2019년  7월</em> 밥퍼 나눔봉사 및 후원 (다일 밥퍼운동본부)</span>
            <span><em>2018년  9월</em> 밥퍼 나눔봉사 및 후원 (다일 밥퍼운동본부)</span>
            <span><em>2017년  3월</em> 송편나누기 봉사 및 후원 ((사)함께하는 한숲)</span>
            <span><em>2016년  5월</em> 사랑의 빵나누기 봉사 및 후원(대한적십자사 희망나눔봉사센터) </span>
            <span><em>2015년  3월</em> 밥퍼 나눔봉사 및 후원 (다일 밥퍼운동본부)</span>
            <span><em>2014년  2월</em> 사랑의 빵나누기 봉사 및 후원 (대한적십자사 희망나눔봉사센터)</span>
            <span><em>2013년  7월</em> 탈북청소년 대안학교 후원 ((사)여명학교, 2013.7~2016.9)</span>
          </div>
          <!-- // -->

          <div>
            <strong class="ko">메세나</strong>
            <strong class="en">Messena</strong>
            <span><em>2024년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
            <span><em>2023년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
            <span><em>2022년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
            <span><em>2021년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
            <span><em>2020년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
            <span><em>2018년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
            <span><em>2015년</em> 문화예술활동 후원(앙상블공간, 한국문화예술위원회)</span>
          </div>
        </div>
      </div>
      <!-- // -->
    </div>
  </div>
</template>

<script>
export default {
  layout: 'default',
  data() {
    return {
      categoryIndex: 5,
      selectedIndex: 22
    }
  }
}
</script>

<style scoped>
.rassiBg {
  @apply bg-[#EFF2FB];
}
.csr{
  @apply py-[90px];
}
.csrTitle {
  @apply flex w-full flex-col items-center gap-2;
}
.csrTitle em {
  @apply text-[#9395a1] text-[16px] leading-5;
}
.csrTitle strong {
  @apply text-[#141414] text-[48px] leading-[60px];
}
.csrContent{
  @apply w-full pt-[90px] flex flex-col items-center;
}
.csrContent .txt{
  @apply w-[989px] mx-auto pt-[45px] flex flex-col gap-[56px]
}
.csrContent .txt div{
  @apply flex flex-col gap-4 w-full
}
.csrContent .txt div strong{
  @apply pb-4 text-[18px] leading-6 text-[#141414] font-bold
}
.csrContent .txt div span, .csrContent .txt div a{
  @apply cursor-pointer text-[16px] text-[#444]
}
.csrContent .txt div span em{
  @apply font-medium inline-block mr-[20px];
}
.csrContent .txt div span span.line{
  @apply ml-[107px];
}
</style>
