<template>
  <!-- bootstrap-card*10 上5下5 -->
  <!-- 信用卡申辦、產險即時保、客戶意見、貸款、理財資訊、證券、投資、基金、信用卡及簽帳金融卡、存款、繳費、資產負債、個人服務、 -->
  <div class="cardBox">
    <div class="card">
      <img src="@/assets/img/線上申辦信用卡.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">線上申辦信用卡</h5>
        <a href="#" class="card-link">立即申辦</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/理財資訊.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">理財資訊</h5>
        <a href="#" class="card-link">立即查看</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/投資.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">投資</h5>
        <a href="#" class="card-link">立即前往</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/貸款.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">貸款</h5>
        <a href="#" class="card-link">立即查看</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/客戶意見.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">客戶意見</h5>
        <a href="#" class="card-link">立即查看</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/產險即時保.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">產險即時保</h5>
        <a href="#" class="card-link">立即查看</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/繳費.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">繳費</h5>
        <a href="#" class="card-link">立即前往</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/存款.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">存款</h5>
        <a href="#" class="card-link">立即查詢</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/負債.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">資產負債</h5>
        <a href="#" class="card-link">立即查詢</a>
      </div>
    </div>
    <div class="card">
      <img src="@/assets/img/個人服務.png"  alt="...">
      <div class="card-body">
        <h5 class="card-title">個人服務</h5>
        <a href="#" class="card-link">立即前往</a>
      </div>
    </div>
  </div>
</template>

<script>
import '@/assets/components/cardbox.css';

export default {
  created() {
    console.log('hello card-box!');
  },
};
</script>
