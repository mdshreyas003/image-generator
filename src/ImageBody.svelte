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
				Generate Images
			</div>
		</div>
		
</div>

<style>
.images{
	display: flex;
	justify-content: space-evenly;
}
.images img{
	height: 350px;
	width: 350px;
	border-radius: 20px;
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
		color: #161618;
		background: rgba(98, 255, 147, 0.8);
		padding: 10px 20px;
		border-radius: 5px;
	}
	.button:hover{
		cursor: pointer;
		background:rgba(107, 244, 150, 0.578);
	}

</style>

