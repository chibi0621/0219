<template>
  <nav>
    <ul>
      <li><router-link to="/">HOME</router-link></li>
      <li>｜</li>
      <li><router-link to="/login">LOGIN</router-link></li>
    </ul>
  </nav>
</template>

<script>
import '@/assets/components/navbar.css';

export default {
  created() {
    console.log('hello navbar!');
  },
};
</script>
