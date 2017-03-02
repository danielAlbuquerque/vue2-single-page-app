<template>
<div class="header clearfix">
     <h1>Feed</h1>

     <my-products></my-products>
</div>
</template>

<script>
	import Products from './product/Products.vue'

	export default {
		components: {
			'my-products': Products
		}
	}
</script>

<style>
	
</style>