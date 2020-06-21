<template>
  <b-container>
    <b-row>
      <b-col cols="9" sm="6">
        <b-jumbotron header="Static Routes" header-level="5" class="m-2">
          <b-tabs content-class="mt-3">
            <b-tab title="One" active>
              <one></one>
            </b-tab>
            <b-tab title="Two">
              <two></two>
            </b-tab>
            <b-tab title="Three">
              <three></three>
            </b-tab>
          </b-tabs>
        </b-jumbotron>
      </b-col>
      <b-col cols="9" sm="6">
        <b-jumbotron header="Dynamic Routes" header-level="5" class="m-2">
          <b-tabs content-class="mt-3">
            <b-tab title="One" active>
              <one></one>
            </b-tab>
            <b-tab title="Two">
              <two></two>
            </b-tab>
            <b-tab title="Three">
              <three></three>
            </b-tab>
          </b-tabs>
        </b-jumbotron>
      </b-col>
    </b-row>

  </b-container>
</template>

<script>
import One from './one'
import Two from './two'
import Three from './three'

export default {
  components: {
    Three,
    Two,
    One
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
