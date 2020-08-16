<template>
  <div>
    <div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#160c28" fill-opacity="1" d="M0,256L48,229.3C96,203,192,149,288,154.7C384,160,480,224,576,218.7C672,213,768,139,864,128C960,117,1056,171,1152,197.3C1248,224,1344,224,1392,224L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
      </svg>
    </div>
    <div class="about-body">
      <b-container>
        <b-row>
          <b-col cols="12">
            <div class="about-title">About Us</div>
            <div class="about-subtitle">We are two-man indie game studio based on Jakarta, Indonesia</div>
            <div class="about-subtitle">that strives to make great games for awesome people!</div>
          </b-col>
        </b-row>
        <b-row style="margin-top: 60px">
          <b-col class="about-col mb-4 mb-md-0" cols="12" md="6">
            <img class="about-illustration" src="@/assets/images/illustration-programmer.png">
            <div class="about-subtitle">Programmer</div>
            <div class="about-person">Cliffen Allen</div>
          </b-col>
          <b-col class="about-col" cols="12" md="6">
            <img class="about-illustration" src="@/assets/images/illustration-designer.png">
            <div class="about-subtitle">Designer</div>
            <div class="about-person">Edy</div>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#160c28" fill-opacity="1" d="M0,64L48,85.3C96,107,192,149,288,181.3C384,213,480,235,576,213.3C672,192,768,128,864,90.7C960,53,1056,43,1152,74.7C1248,107,1344,181,1392,218.7L1440,256L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path>
      </svg>
    </div>
  </div>
</template>

<script>

export default {
  name: 'AboutUsSection',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
.about-body {
  padding: 30px;
  background: #160c28;
  margin-top: -20px;
}
.about-title {
  font-size: 40px;
  text-align: center;
  color: #efcb68;
}
.about-subtitle {
  font-size: 18px;
  text-align: center;
  font-weight: 300;
  color: #efcb68;
}

.about-person {
  font-size: 22px;
  font-weight: bold;
  color: #efcb68;
}

.about-illustration {
  width: 250px;
  height: 250px;
  border-radius: 20px;
  margin-bottom: 10px;
}

.about-col {
  text-align: center
}
</style>