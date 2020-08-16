<template>
  <div>
    <div class="footer-body">
      <b-container>
        <b-row>
          <b-col style="text-align: center;">
            <div class="footer-title">Come &amp; say hello!</div>
            <span>
              <a href="https://www.facebook.com/pg/locos.creative/"><img src="@/assets/images/facebook.png" class="footer-image"></a>
              <a href="https://play.google.com/store/apps/developer?id=LOCOS"><img src="@/assets/images/playstore.png" class="footer-image"></a>
              <a href="mailto:now.locos@gmail.com"><img src="@/assets/images/mail.png" class="footer-image"></a>
            </span>
            <div class="footer-description">&copy; 2017 Locos Creative</div>
          </b-col>
        </b-row>
      </b-container>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style style="scss">
.footer-body {
  background: #160c28;
  padding: 20px 0px;
}
.footer-title{
  color: #fff;
  font-size: 20px;
  margin-bottom: 12px;
}
.footer-description{
  color: #fff;
  margin-top: 12px;
}
.footer-image{
  height: 50px;
  width: 50px;
  margin: 0px 10px;
}
</style>