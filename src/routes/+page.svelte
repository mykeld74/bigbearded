<script>
	import Mike from '$lib/images/md.png';
</script>

<div class="container">
	<img src={Mike} alt="Mike" />
	<p>This is to test the image optimization via netlify and cloudinary.</p>
</div>

<style>
	.container {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		height: 100vh;
		background: url('$lib/images/background.jpg') 50% 50% / cover no-repeat;
	}
</style>
