<template>
	<div class="container">
		<div>
			<div>
				<b-card
					title="Card Title"
					img-src="https://picsum.photos/600/300/?image=25"
					img-alt="Image"
					img-top
					tag="article"
					style="max-width: 20rem"
					class="mb-2"
				>
					<b-card-text>
						Some quick example text to build on the card
						title and make up the bulk of the card's
						content.
					</b-card-text>

					<b-button href="#" variant="primary"
						>Go somewhere</b-button
					>
				</b-card>
			</div>
		</div>
	</div>
</template>

<script>
export default {}
</script>

<style>
.container {
	margin: 0 auto;
	min-height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
	text-align: center;
}

.title {
	font-family: 'Quicksand', 'Source Sans Pro', -apple-system,
		BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial,
		sans-serif;
	display: block;
	font-weight: 300;
	font-size: 100px;
	color: #35495e;
	letter-spacing: 1px;
}

.subtitle {
	font-weight: 300;
	font-size: 42px;
	color: #526488;
	word-spacing: 5px;
	padding-bottom: 15px;
}

.links {
	padding-top: 15px;
}
</style>
