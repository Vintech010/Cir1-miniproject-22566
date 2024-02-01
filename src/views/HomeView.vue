<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("ยินดีต้อนรับ สาขาวิชาเทคโนโลยีสารสนเทศ",{
  autoClose: 2000,
  position:toast.POSITION.TOP_LEFT
});
const notify = () => {
      toast("Wow so easy !", {
        autoClose: 1000,
      }); // ToastOptions
    return { notify };
}
</script>

<template>
<div class ="container my-5">
  <div class="row">
    <div class="col-md-4">
      <div class="card shadow p-0" style="width: 18rem;">
  <img src="https://www.trattc.ac.th/uploads/category/1651913017.jpg" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">เกี่ยวกับเรา</h5>
    <p1 class="card-text">เพือให้สามารถปฏิบัติงานในอาชีพนักพัฒนาซอฟต์แวร์คอมพิวเตอร์ หรือ นักพัฒนาระบบเครือข่าย คอมพิวเตอร์และความปลอดภัย หรือ นักพัฒนาระบบสมองกลฝังตัวและไอโอที หรือ นักพัฒนา คอมพิวเตอร์กราฟิก เกมส์ และแอนิเมชัน ในสถานประกอบการและประกอบอาชีพอิสระ รวมทังการ ใช้ความรู ้และทักษะเป็นพืนฐานในการศึกษาต่อในระดับสูงขึนได้  </p1>
    <a href="https://www.trattc.ac.th/v1/history" target="_blank" class="btn btn-primary" @click="notify">Go somewhere</a>
  </div>
</div>
    </div>
    <div class="col-md-8">
      <div class="card shadow">
        <div class="card-header">

        </div>
        <div class="card-body">
          <div class="class-title">
            Title
          </div>
          <div class="class-text">
            Sup Title
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script setup>

</script>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Sarabun&display=swap');
  
  .h5{
    font-family: 'Sarabun', sans-serif;
  }
  .p1,
  a{
    font-family: 'Sarabun', sans-serif;
    font-size: 15px;
  }
</style>