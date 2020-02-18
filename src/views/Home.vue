<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <RadioButton name="test" value="tester1" />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import RadioButton from '@/components/radio-button.vue';

export default {
  name: 'Home',
  components: {
    HelloWorld,
    RadioButton
  }
}
</script>
