<template>
  <div class="OurValuesContent">
    <div class="categoryContent">
      <div class="contentHead ko">
        <em>[</em> <span>씽크풀 人 </span> <em>]</em>
      </div>
      <div class="contentHead en">
        <em>[</em> <span>Thinkpool Person </span> <em>]</em>
      </div>
      <div class="valueGroup">
        <div class="valueBox">
          <div class="value">
            <span><strong>發</strong>(발)</span>
            <em class="ko">열정을 발하는 人</em>
            <em class="en">A man of passion</em>
          </div>
          <div class="txt ko">
            자신의 삶과 일에 열정을 가지고 <br />
            미래에 도전하며, 그 열정이 동료에게 <br/>
            전달되는 사람
          </div>
          <div class="txt en">
            A person who challenges the future with passion <br />
            for his or her life and work, and whose passion is <br />
            conveyed to his or her colleagues
          </div>
        </div>
        <div class="valueBox">
          <div class="value">
            <span><strong>戰</strong>(전)</span>
            <em class="ko">전략적 사고를 하는 人</em>
            <em class="en">A strategic thinker</em>
          </div>
          <div class="txt ko">
            최고의 성과를 만들기 위해서 <br />
            전략적 요소를 분석하고 모색하여 <br />
            실행하는 사람
          </div>
          <div class="txt en">
            A person who analyzes, seeks and <br />
            executes strategic elements to <br />
            achieve the best performance
          </div>
        </div>
        <div class="valueBox">
          <div class="value">
            <span><strong>疏</strong>(소)</span>
            <em class="ko">소통을 잘하는 人</em>
            <em class="en">A good<br /> communicator</em>
          </div>
          <div class="txt ko">
            동료 간 적극적으로 소통하고 <br />
            서로의 성장과 발전을 위해 <br />
            끊임없이 노력하는 사람
          </div>
          <div class="txt en">
            A person who actively communicates with <br />
            his/her colleagues and constantly strives for <br />
            the growth and development of each other
          </div>
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
.categoryContent{
  @apply w-[1357px] mx-auto gap-[130px] p-[40px_0_200px] flex flex-col items-center
}
.contentHead {
  @apply text-black text-[48px] font-light flex justify-start items-center gap-[14px];
}
.contentHead em {
  @apply font-bold text-[#d9d9d9];
}
.valueGroup{
  @apply w-full flex justify-between items-center;
}
.valueBox{
  @apply flex flex-col gap-[25px] items-center;
}
.value{
  @apply w-[271px] h-[271px] rounded-[271px] bg-[#eff2fb] p-[63px_0_85px];
}
.value span{
  @apply block mb-[25px] text-center text-[#5368ff] text-[20px] font-normal;
}
.value span strong{
  @apply text-[64px] font-bold leading-[80px];
}
.value em{
  @apply block text-[#5368ff] text-[24px] font-bold leading-[24px] text-center;
}
.valueBox .txt{
  @apply text-[#444] text-[20px] font-normal leading-[30px] text-center;
}
</style>
