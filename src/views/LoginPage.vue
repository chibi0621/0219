<template>
  <div class="container">
    <Nav></Nav>
    <h1>
        LOGIN <span class="material-symbols-outlined">login</span>
      </h1>
    <form>
      <div class="loginWords">
        <h2>帳號 account number</h2>
        <input type="email" placeholder="輸入電子郵件" requiredsudo
        aria-label="Input" />
      </div>
      <div class="loginWords">
        <h2>密碼 password</h2>
        <input type="password" placeholder="輸入密碼" required
        aria-label="Input" />
      </div>
      <button>
        <div>登入</div>
        <div>LOGIN</div>
      </button>
      <div class="ulBox">
        <ul>
          <li><a href="#">忘記密碼 forget password</a></li>
          <li>｜</li>
          <li><a href="#">需要幫助 help</a></li>
        </ul>
      </div>
    </form>
  </div>
</template>

<script>
import '@/assets/login.css';

export default {
  created() {
    console.log('hello login-page!');
  },
};
</script>
