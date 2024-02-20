<template>
  <div>
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
      <Navbar></Navbar>
    </header>
    <main>
      <!-- bc:fff / bootstrap-card*10 上5下5 -->
      <CardBox></CardBox>
    </main>
  </div>
</template>

<script>
import Navbar from '@/components/NavBar.vue';
import CardBox from '@/components/CardBox.vue';
import '@/assets/home.css';

export default {
  name: 'HomeView',
  components: {
    Navbar, CardBox,
  },
  created() {
    console.log('hello home-page!');
  },
};
</script>
