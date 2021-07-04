<template>
	<section class="section is-large hero full-screen background" :class="{'picbg': bgshow}">
		<div class="container">
			<div class="title-container">
				<Typeing class="title" text="MURIDATA" />
			</div>
		</div>
	</section>
</template>

<script>
	import Typeing from '@/components/typing.vue'
	
	export default {
		name: "Landing",
		components:{
			Typeing
		},
		data: () => ({
			bgshow: false
		}),
		methods:{
			
		},
		mounted() {
			
		}
	}
</script>

<style lang="scss">
	.full-screen {
		min-height: 100vh;
	}

	.title-container {
		.title {
			color: white;
			font: {
				family: "Time Machine";
				size: 5rem;
				weight: 100;
			}
		}
		
		padding: {
			top: 6rem;
			bottom: 6rem;
		}

		margin: auto;
	}

	.background {
		background: black;
	}
</style>
