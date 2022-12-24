<script>
	var image1="/nature/nature (1).jpg",image2="/nature/nature (2).jpg",image3="/nature/nature (3).jpg";
	let generateImage = function(){
		var i = Math.floor(Math.random()*56);
		image1 = `/nature/nature (${i}).jpg`;
		image2 = `/nature/nature (${i+1}).jpg`;
		image3 = `/nature/nature (${i-1}).jpg`;
		
	}
</script>

<div>
		<div class="images">
			<img src={image1} alt="">
			<img src={image2} alt="">
			<img src={image3} alt="">
		</div>
		<div class="submit">
			<div on:click={generateImage} class="button">
				Generate Random Images
			</div>
		</div>
		
</div>

<style>
.images{
	padding-top: 20px;
	display: flex;
	justify-content: space-evenly;
}
.images img{
	height: 300px;
	width: 450px;
	border-radius: 10px;
}
.submit{
		margin-top: 20px;
		display: flex;
		justify-content: center;
	}
	ul{
		display: flex;
		justify-content: center;
		color:whitesmoke;
		opacity: 0.6;
		font-size: 20px;
	}
	li{
		list-style: none;
		padding: 0 30px 30px ;
	}
	li:hover{
		cursor: pointer;
	}
	.button{
		font-size: x-large;
		font-weight: 500;
		font-style: italic;
		color: #ffffff;
		background: rgba(59, 180, 127, 0.8);
		margin-top: 10px;
		padding: 5px 10px;
		border-radius: 5px;
	}
	.button:hover{
		cursor: pointer;
		color: rgba(59, 180, 127, 0.8);
		background:rgba(255, 255, 255, 0.9);
	}

</style>

