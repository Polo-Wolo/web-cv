<template>
    <div id="app">


      <i data-feather="circle"></i>

      
    </div>
</template>

<script>
import feather from "feather-icons";
export default {
	mounted() {
		feather.replace()
	}
}
</script>

<style lang="scss">
#app {
  font-family: 'Roboto', 'Ubuntu', Arial, sans-serif;
}
</style>
