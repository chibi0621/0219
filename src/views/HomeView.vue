<template>
  <div class="container">
    <header>
      <!-- bc:007979 -->
      <div class="dashboard">
        <strong>｜</strong>
        <h6>
          <a href="#">administrator
            <span class="material-symbols-outlined">
            arrow_drop_down
            </span>
          </a>
        </h6>
      </div>
      <nav>
      <!-- bc:019090 -->
        <ul>
          <li><router-link to="/">HOME</router-link></li>
          <li>｜</li>
          <li><router-link to="/login">LOGIN</router-link></li>
        </ul>
      </nav>
    </header>
    <main>
      <!-- bc:fff / bootstrap-card*10 上5下5 -->
      <CardBox></CardBox>
    </main>
  </div>
</template>

<script>
import CardBox from '@/components/CardBox.vue';
import '@/assets/home.css';

export default {
  name: 'HomeView',
  components: {
    CardBox,
  },
  created() {
    console.log('hello home-page!');
  },
};
</script>
