<template>
  <div id="app">
    <b-container>
      <b-row>
        <b-col></b-col>
        <b-col cols="10"><headline2 class="section-title text-center" text="Hallo meine kleine liebe welt Hallo meine kleine liebe welt Hallo meine kleine liebe welt Hallo meine kleine liebe welt"></headline2></b-col>
        <b-col></b-col>
      </b-row>

      <b-row>
        <b-col></b-col>
        <b-col cols="10"><List></List></b-col>
        <b-col></b-col>
      </b-row>

      <BuyButton text="hallo welt" url="http://www.google.com"></BuyButton>
      <headline2 class="section-title txt-center white" text="hallo"></headline2>
      </b-container>
  </div>
</template>

<script>
import Headline2 from "@/components/Headline2";
import BuyButton from "@/components/BuyButton";
import List from "@/components/List";

export default {
  name: 'app',
  components: {
    Headline2,
    BuyButton,
    List,
  }
}
</script>

<style>

</style>
