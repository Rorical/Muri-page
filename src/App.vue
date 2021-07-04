<template>
	<div id="app">
		<router-view />
	</div>
</template>

<script>
	export default {
		name: 'App',
	}
</script>

<style lang="scss">
	#app {
		flex: 1 1 auto;
	}

	::-webkit-scrollbar-thumb {
		background: #8c8c8c;
		border-radius: 5px;
	}

	::-webkit-scrollbar-track {
		background: #ededed;
	}

	::-webkit-scrollbar {
		width: 5px;
		height: 5px;
		display: block;
		background: #fff;
	}

	body,
	html {
		margin: 0;
	}

	@font-face {
		font-family: 'Time Machine';
		src: url('./assets/fonts/timemachine-wa.ttf');
	}
</style>
