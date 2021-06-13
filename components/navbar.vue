<template>
  <div>
    <v-app-bar flat color="white" fixed>
      <v-col cols="4">
        <v-img
          max-width="268"
          src="https://s3-alpha-sig.figma.com/img/f3a8/828d/c89176f9a2b21f7594514cf37464f3f2?Expires=1623628800&Signature=NdzZeaTiSbe7tYByVABtpyOxGVceW2S-suXc5MB~oYy8xTm5Em5faWRA7KSGaecO661tbOIw2Bu9oBy4getfCVcWTTlMLl9rpmEfe3e1m5CpoSzqlVrFFqJlHM22vqKjYoC473cOhPnZqyEHPhxoPvmJCSK6Mexr-XV3fRAhz-Ra4YJz7DMQpy1K0Kl1F-XPDpjfxSpTNWJ97cmRpGD6WJxLPxUJkM92ai6XDNJPnCw-my4VYRlJPqhE-VgaO8KsmP-NyN3LFcXBIkP6XmdqKhl30E~PxBTlqrWa3TyXcKw6CdMDKnUX~giEPS4YbzZOG2U48DYXyCJbsTdiTRtwjg__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
        ></v-img>
      </v-col>
      <v-col cols="4" class="text-center">
        <a href="" class="ml-5 nuxt-link-active">คุณสมบัติ</a>
        <a href="" class="ml-5">แพคเกจ</a>
        <a href="" class="ml-5">ติดต่อเรา</a>
      </v-col>
      <v-col cols="4">
        <div class="float-right">
          <a href="" class="mr-5">เข้าสู่ระบบ</a>
          <v-btn class="green">สมัครใช้งาน</v-btn>
        </div>
      </v-col>
    </v-app-bar>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* @import './assets/index.css'; */
a {
  text-decoration: none;
  color: black;
}
.nuxt-link-active {
  color: black;
}

.green {
  color: #198754;
}
</style>
