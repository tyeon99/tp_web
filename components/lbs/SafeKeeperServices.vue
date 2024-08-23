<template>
  <div class="SafeKeeperServices">
    <div class="lbsWrap">
        <div class="lbsTitle">
          <strong class="ko">안심키퍼서비스</strong>
          <strong class="en">Safe Keeper Service</strong>
        </div>
        <!-- // -->

      <div class="lbsContent">
        <div class="lbsImg">
          <img src="~/assets/img/safeKeeper.png" alt="안심키퍼서비스" width="462" class="ko">
          <img src="~/assets/img/safeKeeper_en.png" alt="안심키퍼서비스" width="462" class="en">
        </div>
        <div class="lbsTxtBox ko">
          <p>
            안심키퍼 서비스는 타인이 나의 PC로 접속을 시도할 경우 <br />
            SMS 문자를 통해 알람을 주고 이용자가 즉시 차단 또는 예약 <br />
            종료를 할 수 있는 개인정보 보호서비스 입니다.
          </p>
          <p>
            <strong>부정접속 즉시알림</strong>
            PC가 켜지면 안심키퍼가 내 휴대폰으로 SMS 알람을 주고 즉<br />
            시 접속을 차단 할 수 있습니다.
          </p>
          <p>
            <strong>회사/자녀PC 원격통제</strong>
            우리 아이의 게임, 인터넷 등 과다 PC사용이 걱정되는 부모라<br />
            면 PC 예약종료 기능으로 약속한 시간만큼만 
            이용할 수 있습니다.
          </p>
          <p>
            <strong>보상보험으로 한번 더 안심</strong>
            안심키퍼 서비스 가입 고객님께 피싱, 해킹, 스미싱 등 금융사<br />
            기로 인한 금전적 손해 발생 시 보상보험을 제공합니다.
          </p>
        </div>
        <div class="lbsTxtBox en">
          <p>
            The Safe Keeper service is a personal information <br />
            protection service that allows users to immediately block or <br />
            terminate their reservation by giving an alarm through SMS <br />
            text messages when someone else tries to access my PC
          </p>
          <p>
            <strong>Notification immediately of fraudulent connection</strong>
            When your PC turns on, the Safekeeper can give you an <br />
            SMS alarm on your phone and immediately block your access.
          </p>
          <p>
            <strong>Company/Child PC Remote Control</strong>
            Parents who are worried about our child's excessive use of <br />
            PC, such as games and the Internet, can only use it for the <br />
            promised time with the PC reservation termination function.
          </p>
          <p>
            <strong>Reimbursement insurance gives you one more <br />peace of mind</strong>
            In the event of financial damage caused by financial fraud <br />
            such as phishing, hacking, and smishing, we provide <br />
            compensation insurance to customers who subscribe to <br />
            the Safekeeper service.
          </p>
        </div>
      </div>
      
      <!-- <div class="lbsContent">
        <img src="~/assets/img/safeKeeper.png" alt="안심키퍼서비스" width="1213" class="ko">
        <img src="~/assets/img/safeKeeper_en.png" alt="안심키퍼서비스" width="1213" class="en">
      </div> -->
    </div>
  </div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
  
.lbsTitle{
  @apply flex w-full flex-col items-center gap-2 pt-[54px]
}
.lbsTitle em{
  @apply text-[#9395a1] text-[16px] leading-5
}
.lbsTitle strong{
  @apply text-[#141414] text-[48px] leading-[60px]
}
.lbsContent{
  @apply p-[80px_0_120px] flex w-full justify-center gap-[220px]
}
.lbsTxtBox{
  @apply flex flex-col gap-[50px];
}
.lbsTxtBox p{
  @apply text-[#444] text-[20px] font-normal leading-[25px];
}
.lbsTxtBox p strong{
  @apply block text-[36px] font-bold text-[#536eff] leading-[45px] mb-[10px];
}
.lbsTxtBox.en p{
  @apply text-[18px] leading-[22px];
}
.lbsTxtBox.en p strong{
  @apply text-[24px] leading-[24px];
}
</style>
