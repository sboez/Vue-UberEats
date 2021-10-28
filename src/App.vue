<template>
	<Home />
</template>

<script>
import Home from './pages/Home.vue';

export default {
	name: 'App',
	components: {
		Home,
	},
};
</script>

<style>
@import url('./style/normalize.css');
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
#app {
	font-family: 'Roboto', sans-serif;
	padding: 20px;
}
</style>
