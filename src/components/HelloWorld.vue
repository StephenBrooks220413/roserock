<template>
  <br />
  <br />
  <div class="container">
    <div class="jumbotron">
      <h1>Services Offered</h1>
    </div>
    <br />
    <br />
    <div class="row">
      <div class="col-md-4">
        <div class="card hover-shadow">
          <div class="card-body">
            <h3 class="card-title">Life & Health</h3>
            <i class="fas text-info icon fa-heartbeat"></i>
            <h6 class="card-text">
              Life insurance for any event in life & <br />
              health insurance to keep you strong.
            </h6>
            <button type="button" class="btn btn-primary">Button</button>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card hover-shadow">
          <div class="card-body">
            <h3 class="card-title">Auto Insurance</h3>
            <i class="fas text-info icon fa-car"></i>
            <h6 class="card-text">
              Compare competitive auto quotes and select <br />
              the plan that fits you best.
            </h6>
            <button type="button" class="btn btn-primary">Button</button>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card hover-shadow">
          <div class="card-body">
            <h3 class="card-title">Home & Renter</h3>
            <i class="fas text-info icon fa-home"></i>
            <h6 class="card-text">
              You worked hard for your family home, and we <br />
              have the carriers to insure that you keep it.
            </h6>
            <button type="button" class="btn btn-primary">Button</button>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br /><div class="container">
      <h1>Our Underwriting Carriers</h1>
      <br />
      <div class="row">
        <div class="col-md-12">
          <img src="https://1000logos.net/wp-content/uploads/2018/08/Hartford-Insurance-Logo.png"
            alt="hartford"
            width="140px"
          />
          <img src="https://clipartart.com/images/mutual-of-omaha-logo-clipart-7.jpg"
            alt="hartford"
            width="140px"
          />
          <img src="https://focuslitigation.com/wp-content/uploads/2013/08/Progressive-Insurance.jpg"
            alt="hartford"
            width="140px"
          />
          <img src="https://media.consumeraffairs.com/files/logos/allstate-business-insurance_logo_3652.JPG"
            alt="hartford"
            width="140px"
          />
          <img src="https://1000logos.net/wp-content/uploads/2018/08/Hartford-Insurance-Logo.png"
            alt="hartford"
            width="140px"
          />
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="jumbotron">
      <h2>I already have coverage, do I really need a quote?</h2>
      <h5>
        Although you may have been with the same agent for years,
        <br />
        you may actually be over or under covered. And there's nothing
        <br />
        like finding out at the wrong time.
      </h5>
      <h5>
        People often find by getting a quote they save money,
        <br />
        get a rate cheaper because of rate increases,
        <br />
        and sometimes you may need a new agent to cover you.
      </h5>
    </div>
    <br />
    <br />
    <br />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.icon {
  font-size: 3em !important;
}
</style>
