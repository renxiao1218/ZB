<template>
	<div>
		<home-header/>
    <home-main/>
		<home-footer/>
	</div>
</template>

<script>
import HeaderComponent from "./components/Header";
import FooterComponent from "./components/Footer";
import MainComponent from "./components/Main";
	export default {
		components: {
		"home-header": HeaderComponent,
    "home-footer": FooterComponent,
    "home-main": MainComponent
	}
	}

</script>

<style></style>
