<template>
	<div class="restaurant-row">
		<h2 class="title">Nos Restaurants</h2>
		<div class="wrapper-card">
			<RestaurantCard v-for="(card, index) in 3" :key="index" />
		</div>
	</div>
</template>

<script>
import RestaurantCard from './RestaurantCard.vue';
export default {
	name: 'RestaurantRow',
	components: {
		RestaurantCard,
	},
};
</script>

<style lang="scss">
.restaurant-row {
	.title {
		font-size: 2rem;
	}
	.wrapper-card {
		display: flex;
		align-items: center;
		justify-content: space-between;
	}
}
</style>
