<script setup>
import logo from "@/assets/x.png";
import av from "@/assets/avatar.png";
</script>

<template>
	<div class="all">
		<div class="navbar">
			<img :src="logo" alt="Company Logo" class="img">
			<ul>
				<li class="li">
					<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M575.8 255.5c0 18-15 32.1-32 32.1h-32l.7 160.2c0 2.7-.2 5.4-.5 8.1V472c0 22.1-17.9 40-40 40H456c-1.1 0-2.2 0-3.3-.1c-1.4 .1-2.8 .1-4.2 .1H416 392c-22.1 0-40-17.9-40-40V448 384c0-17.7-14.3-32-32-32H256c-17.7 0-32 14.3-32 32v64 24c0 22.1-17.9 40-40 40H160 128.1c-1.5 0-3-.1-4.5-.2c-1.2 .1-2.4 .2-3.6 .2H104c-22.1 0-40-17.9-40-40V360c0-.9 0-1.9 .1-2.8V287.6H32c-18 0-32-14-32-32.1c0-9 3-17 10-24L266.4 8c7-7 15-8 22-8s15 2 21 7L564.8 231.5c8 7 12 15 11 24z"/></svg>
					<a href="#">Home</a>
				</li>
				<li class="li">
					<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 512 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M416 208c0 45.9-14.9 88.3-40 122.7L502.6 457.4c12.5 12.5 12.5 32.8 0 45.3s-32.8 12.5-45.3 0L330.7 376c-34.4 25.2-76.8 40-122.7 40C93.1 416 0 322.9 0 208S93.1 0 208 0S416 93.1 416 208zM208 352a144 144 0 1 0 0-288 144 144 0 1 0 0 288z"/></svg>
					<a href="#">Explore</a>
				</li>
			<li class="li">
				<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 448 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M224 0c-17.7 0-32 14.3-32 32V51.2C119 66 64 130.6 64 208v25.4c0 45.4-15.5 89.5-43.8 124.9L5.3 377c-5.8 7.2-6.9 17.1-2.9 25.4S14.8 416 24 416H424c9.2 0 17.6-5.3 21.6-13.6s2.9-18.2-2.9-25.4l-14.9-18.6C399.5 322.9 384 278.8 384 233.4V208c0-77.4-55-142-128-156.8V32c0-17.7-14.3-32-32-32zm0 96c61.9 0 112 50.1 112 112v25.4c0 47.9 13.9 94.6 39.7 134.6H72.3C98.1 328 112 281.3 112 233.4V208c0-61.9 50.1-112 112-112zm64 352H224 160c0 17 6.7 33.3 18.7 45.3s28.3 18.7 45.3 18.7s33.3-6.7 45.3-18.7s18.7-28.3 18.7-45.3z"/></svg>
				<a href="#">Notifications</a>
			</li>
			<li class="li">
				<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 512 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M64 112c-8.8 0-16 7.2-16 16v22.1L220.5 291.7c20.7 17 50.4 17 71.1 0L464 150.1V128c0-8.8-7.2-16-16-16H64zM48 212.2V384c0 8.8 7.2 16 16 16H448c8.8 0 16-7.2 16-16V212.2L322 328.8c-38.4 31.5-93.7 31.5-132 0L48 212.2zM0 128C0 92.7 28.7 64 64 64H448c35.3 0 64 28.7 64 64V384c0 35.3-28.7 64-64 64H64c-35.3 0-64-28.7-64-64V128z"/></svg>
				<a href="#">Messages</a>
			</li>
			<li class="li">
<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 512 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M201.1 71.9c16.9-5 26.6-22.9 21.5-39.8s-22.9-26.6-39.8-21.5c-21.5 6.4-41.8 15.5-60.6 27C114.3 34 105.4 32 96 32C60.7 32 32 60.7 32 96c0 9.4 2 18.3 5.6 26.3c-11.5 18.7-20.6 39-27 60.6c-5 16.9 4.6 34.8 21.5 39.8s34.8-4.6 39.8-21.5c4.3-14.6 10.4-28.5 17.9-41.4c2 .2 4.1 .3 6.1 .3c35.3 0 64-28.7 64-64c0-2.1-.1-4.1-.3-6.1c12.9-7.5 26.8-13.6 41.4-17.9zm128-61.3c-16.9-5-34.8 4.6-39.8 21.5s4.6 34.8 21.5 39.8c14.6 4.3 28.5 10.4 41.4 17.9c-.2 2-.3 4.1-.3 6.1c0 35.3 28.7 64 64 64c2.1 0 4.1-.1 6.2-.3c7.5 12.9 13.6 26.8 17.9 41.4c5 16.9 22.9 26.6 39.8 21.5s26.6-22.9 21.5-39.8c-6.4-21.5-15.5-41.8-27-60.6c3.6-8 5.6-16.9 5.6-26.3c0-35.3-28.7-64-64-64c-9.4 0-18.3 2-26.3 5.6c-18.7-11.5-39-20.6-60.6-27zM71.9 310.9c-5-16.9-22.9-26.6-39.8-21.5s-26.6 22.9-21.5 39.8c6.4 21.5 15.5 41.8 27 60.6C34 397.7 32 406.6 32 416c0 35.3 28.7 64 64 64c9.4 0 18.3-2 26.3-5.6c18.7 11.5 39 20.6 60.6 27c16.9 5 34.8-4.6 39.8-21.5s-4.6-34.8-21.5-39.8c-14.6-4.3-28.5-10.4-41.4-17.9c.2-2 .3-4.1 .3-6.2c0-35.3-28.7-64-64-64c-2.1 0-4.1 .1-6.2 .3c-7.5-12.9-13.6-26.8-17.9-41.4zm429.4 18.3c5-16.9-4.6-34.8-21.5-39.8s-34.8 4.6-39.8 21.5c-4.3 14.6-10.4 28.5-17.9 41.4c-2-.2-4.1-.3-6.2-.3c-35.3 0-64 28.7-64 64c0 2.1 .1 4.1 .3 6.2c-12.9 7.5-26.8 13.6-41.4 17.9c-16.9 5-26.6 22.9-21.5 39.8s22.9 26.6 39.8 21.5c21.5-6.4 41.8-15.5 60.6-27c8 3.6 16.9 5.6 26.3 5.6c35.3 0 64-28.7 64-64c0-9.4-2-18.3-5.6-26.3c11.5-18.7 20.6-39 27-60.6zM192.8 256.8c0-15.6 5.6-29.9 14.9-41.1L223 231c6.6 6.6 17.8 1.9 17.8-7.4V163.2c0-5.7-4.7-10.4-10.4-10.4H169.9c-9.3 0-13.9 11.2-7.4 17.8l11.2 11.2c-17.9 19.8-28.9 46.2-28.9 75.1c0 43.6 24.9 81.3 61.1 99.8c11.8 6 26.3 1.4 32.3-10.4s1.4-26.3-10.4-32.3c-20.8-10.6-34.9-32.2-34.9-57zm93.1-58.6c20.8 10.6 34.9 32.2 34.9 57c0 15.6-5.6 29.9-14.9 41.1L290.6 281c-6.6-6.6-17.8-1.9-17.8 7.4v60.5c0 5.7 4.7 10.4 10.4 10.4h60.5c9.3 0 13.9-11.2 7.4-17.8l-11.2-11.2c17.9-19.8 28.9-46.2 28.9-75.1c0-43.6-24.9-81.3-61.1-99.8c-11.8-6-26.3-1.4-32.3 10.4s-1.4 26.3 10.4 32.3z"/></svg>
			<a href="#">Grok</a>
			</li>
			<li class="li">
				<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 640 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M96 128a128 128 0 1 1 256 0A128 128 0 1 1 96 128zM0 482.3C0 383.8 79.8 304 178.3 304h91.4C368.2 304 448 383.8 448 482.3c0 16.4-13.3 29.7-29.7 29.7H29.7C13.3 512 0 498.7 0 482.3zM609.3 512H471.4c5.4-9.4 8.6-20.3 8.6-32v-8c0-60.7-27.1-115.2-69.8-151.8c2.4-.1 4.7-.2 7.1-.2h61.4C567.8 320 640 392.2 640 481.3c0 17-13.8 30.7-30.7 30.7zM432 256c-31 0-59-12.6-79.3-32.9C372.4 196.5 384 163.6 384 128c0-26.8-6.6-52.1-18.3-74.3C384.3 40.1 407.2 32 432 32c61.9 0 112 50.1 112 112s-50.1 112-112 112z"/></svg>
				<a href="#">Communities</a>
			</li>
			<li class="li">
				<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 512 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z"/></svg>
			<a href="#">Premium</a>
			</li>
			<li class="li">
				<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 448 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M304 128a80 80 0 1 0 -160 0 80 80 0 1 0 160 0zM96 128a128 128 0 1 1 256 0A128 128 0 1 1 96 128zM49.3 464H398.7c-8.9-63.3-63.3-112-129-112H178.3c-65.7 0-120.1 48.7-129 112zM0 482.3C0 383.8 79.8 304 178.3 304h91.4C368.2 304 448 383.8 448 482.3c0 16.4-13.3 29.7-29.7 29.7H29.7C13.3 512 0 498.7 0 482.3z"/></svg>
				<a href="#">Profile</a>
			</li>
			<li class="li">
				<svg xmlns="http://www.w3.org/2000/svg" height="25px" fill="white" viewBox="0 0 320 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M137.4 374.6c12.5 12.5 32.8 12.5 45.3 0l128-128c9.2-9.2 11.9-22.9 6.9-34.9s-16.6-19.8-29.6-19.8L32 192c-12.9 0-24.6 7.8-29.6 19.8s-2.2 25.7 6.9 34.9l128 128z"/></svg>
				<a href="#">More</a>
			</li>
			<button class="post">Post</button>
			<div class="wrap">
				<img :src="av" alt="Avatar" class="avatar">
				<div>
					<span>Alan Walker<svg xmlns="http://www.w3.org/2000/svg" height="20px" fill="white" viewBox="0 0 576 512"><!--!Font Awesome Free 6.5.2 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free Copyright 2024 Fonticons, Inc.--><path d="M352 144c0-44.2 35.8-80 80-80s80 35.8 80 80v48c0 17.7 14.3 32 32 32s32-14.3 32-32V144C576 64.5 511.5 0 432 0S288 64.5 288 144v48H64c-35.3 0-64 28.7-64 64V448c0 35.3 28.7 64 64 64H384c35.3 0 64-28.7 64-64V256c0-35.3-28.7-64-64-64H352V144z"/></svg></span>
					<br>
					<span>AlanWolker22456@</span>
				</div>
			</div>
			</ul>
		</div>
	</div>
  
</template>

<style scoped>
.all {
	background: black;
	width: 23%;
	height: 100vh;
	padding: 10px;
	overflow: auto;
	border-right: 1px solid rgb(255, 255, 255);
}
.img{
	width: 50px;
	height: 50px;
	margin-left: 30px;
}
.navbar{
	color: white;
}
ul{
	list-style: none;
}
.li{
	margin-left: 30px;
	margin-bottom: 5px;
	font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
	transition: 0.3s ease-in-out;
	padding: 10px;
	border-radius: 30px;
}
a{
	margin-left: 7px;
	text-decoration: none;
	color: aliceblue;
	font-size: 20px;
}
.li:hover{
	background: gray;
}
.post{
	padding: 15px;
	border-radius: 30px;
	background: rgb(0, 183, 255);
	color: aliceblue;
	margin-left: 30px;
	border: none;
	width: 90%;
	font-size: 20px;
}
.avatar{
	width: 50px;
	height: 50px;
}
.wrap{
	display: flex;
	flex-wrap: wrap;
	margin-left: 30px;
	padding: 5px;
	transition: 0.3 ease-in-out;
	border-radius: 30px;
	font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
	margin-top: 2px;
}
.wrap:hover{
	background: gray;
}

</style>
