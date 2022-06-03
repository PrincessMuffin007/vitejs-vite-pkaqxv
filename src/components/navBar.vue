<template>
<!-- Header -->
  <header class="header">
    <!-- Nav  -->
    <nav class="nav">
      <!-- UL  -->
      <ul class="ul">
        <!-- Logo -->
        <li class="logo"><router-link to="/">STUDY TODAY!</router-link></li>
        <li class="registerLog">
          <router-link to="/register">REGISTER</router-link>
        </li>
      </ul>
    </nav>
  </header>
  <!-- Header -->

</template>

<script>
import { ref } from "@vue/reactivity";

export default {
  name: "Navbar",
 
  .header {
  .nav {
    background: #fff;
    border-bottom: 2px solid #2222;
    .ul {
      display: flex;
      justify-content: space-around;
      align-items: center;
      flex-wrap: wrap;
      gap: 5px;
      padding: 15px;
      list-style: none;
      .logo {
        a {
          font-size: clamp(0.9rem, 1vw + 1rem, 2rem);
          text-transform: uppercase;
          color: crimson;
          font-weight: 700;
          text-decoration: none;
        }
      }
      .registerLog {
        a {
          font-size: 1.2rem;
          color: #222;
          text-transform: capitalize;
          text-decoration: none;
          border: 2px solid crimson;
          padding: 5px 20px;
          border-radius: 5px;
        }
      }
    }
  }
}
};
</script>

<style>


</style>