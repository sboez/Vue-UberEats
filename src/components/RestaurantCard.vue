<template>
	<div class="restaurant-card">
		<div class="restaurant-image"></div>
		<div class="restaurant-information">
			<div class="top">
				<p class="name">Subway</p>
				<p class="note">
					<span>4,5</span>
				</p>
			</div>
			<div class="time">20-30mn</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'RestaurantCard',
	props: {
		msg: String,
	},
};
</script>

<style lang="scss">
.restaurant-card {
	width: 32%;
	height: 30vh;
	p {
		margin: 0px;
	}
	.restaurant-image {
		background-image: url('https://cn-geo1.uber.com/image-proc/resize/eats/format=webp/width=550/height=440/quality=70/srcb64=aHR0cHM6Ly9kMXJhbHNvZ25qbmczNy5jbG91ZGZyb250Lm5ldC8zNzg4MDJiMC1jNTI4LTQ4MjktYjBiNS0wY2M2NDBkZjYzY2QuanBlZw==');
		height: 70%;
		background-size: cover;
		background-position: center;
	}
	.restaurant-information {
		.top {
			display: flex;
			margin: 10px 0;
			align-items: center;
			justify-content: space-between;
		}
		.note {
			background-color: #eeeeee;
			height: 30px;
			width: 30px;
			display: flex;
			justify-content: center;
			align-items: center;
			font-size: 0.8rem;
			border-radius: 50%;
		}
		.time {
			font-size: 0.9rem;
		}
	}
}
</style>
