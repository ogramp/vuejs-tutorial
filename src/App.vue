<template>
	<div>
		<app-header></app-header>
		<app-footer></app-footer>
	</div>
</template>

<script>
// Import the component.
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';

export default {
	// Register the component locally.
	components: {
		'app-header': Header,
		'app-footer': Footer
	},
	data () {
		return {

		}
	}
}
</script>

<style >

</style>