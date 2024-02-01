<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-dark shadow" style="background: #2F4F4F;">
  <div class="container-fluid">
    <router-link :to="{name: 'home'}" class="navbar-brand" href="#">นายดนุเดช</router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <router-link :to="{name: 'home'}" class="nav-link active" aria-current="page">Home</router-link>
        </li>
        <li class="nav-item">
          <a class="nav-link">บุคลากร</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            เกี่ยวกับเรา
          </a>
          <ul class="dropdown-menu">
            <li><router-link :to="{name: 'about'}" class="dropdown-item">ประวัติความเป็นมา</router-link></li>
            <li><a class="dropdown-item">วิสัยทัศน์</a></li>
            <li><a class="dropdown-item">บุคลากร</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item">เเผนที่</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            หลักสูตร
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item">ระดับประกาศนียบัตรวิชาชีพ(ปวช.)</a></li>
            <li><a class="dropdown-item">ระดับประกาศนียบัตรวิชาชีพชั้นสูง(ปวส.)</a></li>
            <li><a class="dropdown-item">ระดับปริญญาตรี</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item">หลักสูตรอื่นๆ</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            เผยเเพร่ผลงาน
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item">ผลงานนักเรียน-นักศึกษา</a></li>
            <li><a class="dropdown-item">ผลงานครู-อาจารย์</a></li>
            <li><a class="dropdown-item">ระดับปริญญาตรี</a></li>
          </ul>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            ระบบบริการ
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item">ระบบฐานข้อมูล นักเรียน-นักศึกษา</a></li>
            <li><a class="dropdown-item">ระบบสมัคร นักเรียน-นักศึกษา</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">เว็ปอื่นๆ</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>


<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Sarabun&display=swap');
  
  .navbar{
    font-family: 'Sarabun', sans-serif;
  }
</style>
