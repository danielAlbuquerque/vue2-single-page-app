<template>
	<div class="col-md-4">
		<div class="thumbnail">
			<img src="https://mir-s3-cdn-cf.behance.net/project_modules/disp/ce54bf11889067.562541ef7cde4.png">

			<div class="caption">
				<h3>{{ product.name }}</h3>
				<p>{{ product.price }}</p>

				<hr>

				<p>
					<a href="#" class="btn btn-default">
						Wish List
					</a>

					<a href="#" class="btn btn-success">
						Buy
					</a>
				</p>
			</div>
		</div>
	</div>
</template>

<script>
	export default {
		props: ['product', 'authenticatedUser']
	}
</script>

