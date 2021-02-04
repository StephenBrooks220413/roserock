<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <div class="bg-image">
      <img
        src="../assets/roserock.jpg"
        width="80%"
        class="w-100 max-img"
        alt="Sample"
      />
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="text-white">
            For the Affordable Insurance
            <br />
            555-555-5555
          </h1>
        </div>
      </div>
    </div>
    <HelloWorld />
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1>Contact Us</h1>
          <form>
            <!-- Name input -->
            <div class="form-outline mb-4">
              <input type="text" id="form4Example1" class="form-control" />
              <label class="form-label" for="form4Example1">Name</label>
            </div>

            <!-- Email input -->
            <div class="form-outline mb-4">
              <input type="email" id="form4Example2" class="form-control" />
              <label class="form-label" for="form4Example2"
                >Email address</label
              >
            </div>

            <!-- Message input -->
            <div class="form-outline mb-4">
              <textarea
                class="form-control"
                id="form4Example3"
                rows="4"
              ></textarea>
              <label class="form-label" for="form4Example3">Message</label>
            </div>

            <!-- Submit button -->
            <button type="submit" class="btn btn-primary btn-block mb-4">
              Send
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style lang="scss">
.max-img {
  max-height: 550px;
}
form {
  max-width: 950px !important;
  margin-left: auto;
  margin-right: auto;
}
input,
textarea {
  background-color: rgb(206, 197, 197) !important;
  opacity: 0.4;
}
</style>
