<template>
  <div class="footer-container">
    <a href="#"
      ><v-img
        class="footer-logo"
        src="../assets/main_footer-logo.png"
        alt="footer-logo"
      ></v-img
    ></a>
    <div>
      <span>© BIRDVIEW. ALL RIGHTS RESERVED.</span>
    </div>
    <div class="footer-icon-container">
      <ul class="footer-lists">
        <li>
          <a href="#">
            <v-img
              class="footer-icon"
              src="../assets/icon/youtube_icon.png"
              alt="youtube"
            ></v-img>
          </a>
        </li>
        <li>
          <a href="#">
            <v-img
              class="footer-icon"
              src="../assets/icon/facebook_icon.png"
              alt="facebook"
            ></v-img>
          </a>
        </li>
        <li>
          <a href="#">
            <v-img
              class="footer-icon"
              src="../assets/icon/instagram_icon.png"
              alt="instagram"
            ></v-img>
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.footer-container {
  width: 100%;
  padding: 80px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  background-color: #f9f9f9;
}

.footer-logo {
  width: 80px;
}

.footer-lists {
  display: flex;
  list-style: none;
}
.footer-icon {
  width: 36px;
}
.footer-lists li {
  padding: 0 8px;
}
</style>
