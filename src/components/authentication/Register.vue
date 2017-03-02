<template>
	<div class="row">
		<div class="col-md-6 col-md-offset-3">
			<div class="panel panel-default">
				<div class="panel-body">
					<div class="form-group">
						<input type="text" class="form-control" placeholder="Name" v-model="name">
					</div>
					<div class="form-group">
						<input type="email" class="form-control" placeholder="Email" v-model="email">
					</div>
					<div class="form-group">
						<input type="password" class="form-control" placeholder="password" v-model="password">
					</div>
					<button class="btn btn-success pull-right">Login</button>
				</div>
			</div>
		</div>
	</div>	
</template>

<script>
	export default {
		data () {
			return {
				'name': '',
				'email': '',
				'password': ''
			}
		}
	}
</script>

<style>

</style>