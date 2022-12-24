<script>
  import ImageBody from './ImageBody.svelte';

  import Navbar from './Navbar.svelte';

  import Footer from './Footer.svelte';
</script>

<main>
<Navbar/>
<div>
	<div class="heading">
	<strong>LOREM PICSUM</strong>
	</div>
	<div class="subheading">
		Generate Image you want of any category you like, with one click only 🚀🚀🚀
	</div>
	<ImageBody/>
</div>
<Footer/>


</main>

<style>
	main{
		overflow: hidden;
	}
	.subheading {
		padding: 8px 0 0 0 ;
		font-style: normal;
		font-weight: 600;
		font-size: 16px;
		line-height: 15px;
		text-align: center;
		color: #FFFFFF;
		opacity: 0.9;
		margin-bottom: 50px;
	}
	.heading{
		margin-top: 40px;
		padding-top: 60px;
		font-style: normal;
		font-weight: 600;
		font-size: 40px;
		line-height: 50px;
		text-align: center;
		background: linear-gradient(269.52deg, rgba(16, 254, 240, 0.94) -2.24%, rgba(60, 255, 67, 0.71) 99.82%);
		-webkit-background-clip: text;
		-webkit-text-fill-color: transparent;
		background-clip: text;
		opacity: 1;
	}

</style>