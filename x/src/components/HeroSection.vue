<script setup>

</script>
<template>
    <div class="top">
		<div class="top2">
			<span class="spn">For you</span>
			<span class="spn">Following</span>
		</div>
		<div class="div"></div>
		<div class="wrap">
			<span class="post">Show 100 posts</span>
		</div>
		<div class="remind">
			<h1 class="h1">Help make X more accessible</h1>
			<p class="p">Did you know that adding descriptions to your images makes them accessible to people who are blind, have low vision, or use assistive technology? Turn on the reminder so you remember to include everyone.</p>
			<button class="bttn">Turn On Riminder</button>
		</div>
	</div>
</template>
<style  scoped>
.top{
	width: 50%;
	background: black;
	height: 100vh;
	overflow: auto;
}
.top2{
	color: aliceblue;
	display: flex;
	flex-wrap: wrap;
	justify-content: space-around;
	align-items: center;
	background: rgba( 255, 255, 255, 0 );
	box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
	backdrop-filter: blur( 4px );
	-webkit-backdrop-filter: blur( 4px );
	border: 1px solid rgba( 255, 255, 255, 0.18 );
	position: fixed;
	width: 50%;
	font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
	}
	.spn{
		width: 50%;
		padding: 20px;
		transition: 0.4s ease-in;
	}
	.spn:hover{
		background: rgb(65, 61, 61);
	}
	.post{
		color: rgb(21, 21, 192);
		padding: 20px;
		font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
	}
	.wrap{
		text-align: center;
		border: 1px solid rgba( 255, 255, 255, 0.18 );
		padding: 20px;
	}
	.div{
		padding: 30px;
	}
	.remind{
		padding: 15px;
		color: aliceblue;
		border: 1px solid rgba( 255, 255, 255, 0.18 );
		font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
	}
	.h1{
		margin-top: 10px;
		margin-bottom: 7px;
	}
	.p{
		color: gray;
		margin-bottom: 30px;
	}
	.bttn{
		border: none;
		padding: 10px;
		color: black;
		background: aliceblue;
		border-radius: 30px;
		font-size: 15px
	}
</style>