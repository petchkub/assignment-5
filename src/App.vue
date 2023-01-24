<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Countlikesad from "./components/likesad.vue"
</script>

<template>


  <header>
  <div class="collapse bg-dark" id="navbarHeader">
    <div class="container">
      <div class="row">
        <div class="col-sm-8 col-md-7 py-4">
          <h4 class="text-white">About</h4>
          <p class="text-muted">Add some information about the album below, the author, or any other background context. Make it a few sentences long so folks can pick up some informative tidbits. Then, link them off to some social networking sites or contact information.</p>
        </div>
        <div class="col-sm-4 offset-md-1 py-4">
          <h4 class="text-white">Contact</h4>
          <ul class="list-unstyled">
            <li><a href="#" class="text-white">Follow on Twitter</a></li>
            <li><a href="#" class="text-white">Like on Facebook</a></li>
            <li><a href="#" class="text-white">Email me</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <div class="navbar navbar-dark bg-dark shadow-sm">
    <div class="container">
      <a href="#" class="navbar-brand d-flex align-items-center">
        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" aria-hidden="true" class="me-2" viewBox="0 0 24 24"><path d="M23 19a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4l2-3h6l2 3h4a2 2 0 0 1 2 2z"/><circle cx="12" cy="13" r="4"/></svg>
        <strong>Album</strong>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarHeader" aria-controls="navbarHeader" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
    </div>
  </div>
</header>

<main>
  <section class="py-5 text-center container">
    <div class="row py-lg-5">
      <div class="col-lg-6 col-md-8 mx-auto">
        <h1 class="fw-light">OPZ TV</h1>
        <p class="lead text-muted">รวมคลิป OPZ TV โดยสามารถกดที่ชื่อคลิปเพื่อไปสู่คลิปบน Youtube ได้</p>
        <p>
          <a href="https://www.youtube.com/@OPZTV">
            <button type="button" class="btn btn-outline-danger">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-youtube" viewBox="0 0 16 16">
  <path d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z"/>
</svg>
                Youtube
              </button>
          </a>   
          <a href="https://www.facebook.com/fanpageopztv">  
            <button type="button" class="btn btn-primary">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
  <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
</svg>
                Facebook
              </button>
            </a> 
        </p>
      </div>
    </div>
  </section>

  <div class="album py-5 bg-light">
    <div class="container">

      <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz1.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=vk39MO8QOWY&t=29s"><p class="card-text">ไหน จะโผล่มาตอนไหน</p></a>
              <div class="d-flex justify-content-between align-items-center">
                <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz2.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=LygcNEOgqRg&t=1s"><p class="card-text">GTA ที่พวกเอ็งอยากดูไง</p></a>
              <div class="d-flex justify-content-between align-items-center">
                                             <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz3.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=G7-5iDsvFAI&t=76s"><p class="card-text">เบ้ก OF DARKNESS</p></a>
              <div class="d-flex justify-content-between align-items-center">
                                <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz4.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=Z_kOAxcfiw4&t=65s"><p class="card-text">ZEEDZAD ล่าข้ามศตวรรษ</p></a>
              <div class="d-flex justify-content-between align-items-center">
                              <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz5.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=-IFudCDS4Qg"><p class="card-text">ชั้นรักเธอ คิริซี๊ด</p></a>
              <div class="d-flex justify-content-between align-items-center">
                             <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz6.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=3Ap4a6SNbi4&t=52s"><p class="card-text">อ้าปากกว้าง ปากมึงจะเหม็น</p></a>
              <div class="d-flex justify-content-between align-items-center">
                                             <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>

        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz7.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=2HJanB6ikqU&t=53s"><p class="card-text">มันถึงเวลาแล้ว</p></a>
              <div class="d-flex justify-content-between align-items-center">
                                             <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz8.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=P-LaRTKmMWkt=47s"><p class="card-text">ฮาคิของแก ยอดเยี่ยมจริงๆ</p></a>
              <div class="d-flex justify-content-between align-items-center">
                                             <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card shadow-sm">
            <img src="/img/opz9.jpg" alt="">
            <div class="card-body">
              <a class="yt" href="https://www.youtube.com/watch?v=P-LaRTKmMWk&t=47s"><p class="card-text">ไอพวกลิงจากทะเลสีฟ้า</p></a>
              <div class="d-flex justify-content-between align-items-center">
                                             <Countlikesad></Countlikesad>
                <small class="text-muted">9 mins</small>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

</main>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
<style>
      .bd-placeholder-img {
        font-size: 1.125rem;
        text-anchor: middle;
        -webkit-user-select: none;
        -moz-user-select: none;
        user-select: none;
      }

      @media (min-width: 768px) {
        .bd-placeholder-img-lg {
          font-size: 3.5rem;
        }
      }

      .b-example-divider {
        height: 3rem;
        background-color: rgba(0, 0, 0, .1);
        border: solid rgba(0, 0, 0, .15);
        border-width: 1px 0;
        box-shadow: inset 0 .5em 1.5em rgba(0, 0, 0, .1), inset 0 .125em .5em rgba(0, 0, 0, .15);
      }

      .b-example-vr {
        flex-shrink: 0;
        width: 1.5rem;
        height: 100vh;
      }

      .bi {
        vertical-align: -.125em;
        fill: currentColor;
      }

      .nav-scroller {
        position: relative;
        z-index: 2;
        height: 2.75rem;
        overflow-y: hidden;
      }

      .nav-scroller .nav {
        display: flex;
        flex-wrap: nowrap;
        padding-bottom: 1rem;
        margin-top: -1px;
        overflow-x: auto;
        text-align: center;
        white-space: nowrap;
        -webkit-overflow-scrolling: touch;
      }
    </style>