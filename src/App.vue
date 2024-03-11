<template>
  <main>
    <div class="flex" >
		<div class="md:w-1/2 hidden md:block" >
			<img class="w-full" alt="" src="assets/image30.png">
			<img alt="" src="assets/image31.png"> 
		</div>
		<div class="md:w-1/2 w-full" ></div>
    </div>
  </main>
</template>
<script>
	import image from "./assets/logo.png"


	export default {
		data: function () {
			return {
				image: image
			}
		}
	}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

</style>
