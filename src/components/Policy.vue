<template>
  <div class="policy-body">
    <b-container>
      <b-row>
        <b-col cols="12" style="text-align: center;">
          <div class="policy-title">Privacy Policy</div>
          <div class="policy-subtitle">Important notes regarding Locos Games Policy</div>
          <b-button pill class="policy-button" v-b-modal="'policy-modal'">Read User Policy</b-button>
        </b-col>
      </b-row>
    </b-container>
    <PolicyModal/>
  </div>
</template>

<script>
import PolicyModal from './sub-components/Policy-Modal';
export default {
  name: 'PolicySection',
  components: {
    PolicyModal,
  },
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
.policy-body {
  padding: 30px;
  margin-top: -40px;
  margin-bottom: 30px;
}
.policy-title {
  font-size: 40px;
}
.policy-subtitle {
  font-size: 18px;
  font-weight: 300;
}
.policy-button {
  margin-top: 20px;
  padding: 8px 30px !important;
  color: #efcb68 !important;
  background: #160c28 !important;
  text-align: center;
}
</style>