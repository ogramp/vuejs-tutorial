<template>
	<div>
		<form-helper>
			<div slot="form-header">
				<h3>This is the title of the form</h3>
				<p>Information about the form</p>
			</div>
			<div slot="form-fields">
				<input type="text" name="username" placeholder="name" required="" />
				<input type="password" name="password" placeholder="password" required="" />
			</div>
			<div slot="form-controls">
				<button v-on:click="handleSumbit">Submit</button>
			</div>
		</form-helper>
	</div>
</template>

<script>
	// Import the components.
	import formHelper from './components/formHelper.vue';

	export default {
		// Register the component locally.
		components: {
			'form-helper': formHelper
		},
		data () {
			return {
				title: 'I am a dynamic slot title'
			}
		},
		methods: {

		}
	}
</script>

<style >

</style>