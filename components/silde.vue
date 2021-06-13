<template>
  <div class="app">
    <v-container fluid>
      <v-row class="bg">
        <v-col cols="6" class="bg-1">
          <div class="mr-5 mt-4">
            <v-col class="mt-4">
              <h1 class="text1 float-right">ระบบเว็บไซต์หน่วยงานสำเร็จรูป</h1>
            </v-col>
            <v-col class="mt-4">
              <h5 class="text1 float-right">
                สร้างไซต์หน่วยงานท่านได้ตัวเอง ง่าย เร็ว สวยงาม
              </h5>
            </v-col>
            <v-col class="mt-2">
              <h5 class="text1 float-right">
                MANAGE YOUR ORGANIZATION , EASY , FAST , BEAUTIFUL
              </h5>
            </v-col>
            <v-col class="float-right">
              <v-btn class="float-right" color="success">ทดลองใช้งาน</v-btn>
            </v-col>
            <v-col class="day">
              <h5 class="text1 float-right">
                * สมัครใช้งานวันนี้ทดลองใช้ฟรี 30วัน
              </h5>
            </v-col>
          </div>
        </v-col>
        <v-col cols="6">
          <div class="d-flex justify-center">
            <v-img
              max-height="370"
              max-width="450"
              src="https://s3-alpha-sig.figma.com/img/7c09/860c/b2e58571d299b656d2dd3e81a8baaf4e?Expires=1623628800&Signature=BYoPt-Y11sss1Vk1INGZYDb6w35yb3EztKOXTBHs8-VuBEOpFypLJNd~miF7o2kRn6a9oucqonJ0UKKSb1kkTfPWorbHODUbnH~1CUOvtuXhLTt37nVRjaFM4rUpYS-fDnJyZiGKE5WEazIBDQvhyIGQvpTlAtjYy~SoLcGw3tXSqiZ2MDDDpPrAMFlatRVJB9U2LazZcVVNP-UfJVWB4dD954RZG6QPClI3N2kbepr~WK3C1wkvLRvgcXsO1oMGAmhCjXf9XY0s~wEBL40R07oWFb~sHlRQCX46r9DTK1FDCDQ26HfRoT5F-Rh4C6XgY5VN1CiSG-u288wJ7FZEGA__&Key-Pair-Id=APKAINTVSUGEWH5XD5UA"
            ></v-img>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Kanit:wght@300&display=swap');
.app {
  font-family: 'Kanit', sans-serif;
}
.bg {
  background-color: #f1f1f1;
}
.bg-1 {
  background-color: #e0e0e0;
  border-radius: 0px 84px 84px 0px;
}
.day {
  color: rgb(255, 0, 0);
}
</style>
