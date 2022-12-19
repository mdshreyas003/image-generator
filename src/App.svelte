<script>
  import ImageBody from './ImageBody.svelte';

  import Navbar from './Navbar.svelte';
</script>

<main>
<Navbar/>
<div>
	<div class="heading">
		LOREM PICSUM
	</div>
	<div class="subheading">
		Generate Image you want of any category you like, with one click only 🚀🚀🚀
	</div>
	<ImageBody/>
</div>



</main>

<style>
	main{
		overflow: hidden;
	}
	.subheading {
		padding: 10px 0 0 0 ;
		font-style: normal;
		font-weight: 600;
		font-size: 25px;
		line-height: 36px;
		text-align: center;
		color: #FFFFFF;
		opacity: 0.7;
		margin-bottom: 50px;
	}
	.heading{
		margin-top: 40px;
		padding-top: 20px;
		font-style: normal;
		font-weight: 600;
		font-size: 45px;
		line-height: 50px;
		text-align: center;
		background: linear-gradient(269.52deg, rgba(16, 254, 240, 0.94) -2.24%, rgba(60, 255, 67, 0.71) 99.82%);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
		opacity: 0.9;
	}

</style>