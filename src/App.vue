<template>
	<div id="app">

		<button class="m-4 btn btn-magenta">CONTACT ME</button>
		<button class="m-4 btn btn-ocean">CONTACT ME</button>
		<button class="m-4 btn btn-peach">CONTACT ME</button>
		<button class="m-4 btn btn-gradient-m-o">CONTACT ME</button>
		<button class="m-4 btn btn-gradient-m-p">CONTACT ME</button>
		<button class="m-4 btn btn-transparent">CONTACT ME</button>
	
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
font-family: 'Roboto', 'Montserrat', 'Ubuntu', Arial, sans-serif;
}
</style>
