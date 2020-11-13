<template>
    <div class="items-center justify-center w-12 sm:w-20 fixed h-full flex flex-col bg-gray-900 py-6">
        <a :href="home_link">
            <div class="w-6 sm:w-8 text-cultured-100 leading-3 sm:leading-4 flex flex-col">
                <h1 class="text-left">P</h1>
                <h1  class="hidden text-center sm:block">-</h1>
                <h1 class="text-right">W</h1>
            </div>
        </a>

        <div class="burger-icon mt-12">
			<span></span>
		</div>

        <div class="h-full"></div>
        
        <ul class="nav-list space-y-6">
            <li><a>EDUCATION</a></li>
            <li><a>FORMATIONS</a></li>
            <li><a>COMPÉTENCES</a></li>
            <li><a>PROJETS</a></li>
            <li><a>LOISIRS</a></li>
        </ul>

        <div class="h-full"></div>

        <div class="burger-icon mb-12">
			<span class="block h-0.4 bg-ocean-900 w-8 transform rotate-90 rounded-full"></span>
		</div>

        <a href="#"><i data-feather="instagram" color="white" stroke-width="1.1px" class="w-4 h-4"></i></a>
        <a href="#"><i data-feather="github" color="white" stroke-width="1.1px" class="w-4 h-4 my-2"></i></a>
        <a href="#"><i data-feather="linkedin" color="white" stroke-width="1.1px" class="w-4 h-4"></i></a>
    </div>
</template>

<script>
    import feather from "feather-icons";


    export default {
        mounted() {
                feather.replace()
        },
        props: {
            "logo": String,
            "home_link": String,
        },
    }
</script>

<style lang="scss">

</style>