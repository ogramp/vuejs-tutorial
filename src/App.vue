<template>
	<div>
		<app-header></app-header>
	</div>
</template>

<script>
// Import the component.
import Header from './components/Header.vue'

export default {
	// Register the component locally.
	components: {
		'app-header': Header
	},
	data () {
		return {

		}
	}
}
</script>

<style >

</style>