<template>
	<div id="app">

		<nav-bar logo='/img/svg/logo_paper_white.svg' home_link='#'></nav-bar>
		
	</div>
</template>

<script>
	import feather from "feather-icons";
	import NavBar from './views/components/NavBar';

	export default {
		components: {
            NavBar,
        },
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
