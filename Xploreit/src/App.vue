<script setup>
//azi maine alt comp

//goo news
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  
  <header>
    <nav>
      <div class="login">
        <a href="#"><img src="../public/imagini/logo.png.png"></a>
        <ul>
          <li><a href="sign.html">Sign in</a></li>
          <li><a href="login.html">Login</a></li>
        </ul>
        <ul>
          <li>RO</li>
          <li><button type="menu"> <img src=""></button></li>
        </ul>
      </div>

    </nav>
  </header>

  <RouterView />
</template>

<style scoped></style>