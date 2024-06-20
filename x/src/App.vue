<script setup>
  import SideBar from '@/components/SideBar.vue';
  import HeroSection from '@/components/HeroSection.vue';
</script>

<template>
	<div class="main">
		<SideBar />
		<HeroSection/>
	</div>
  
</template>
<style  scoped>
.main{
	display: flex;
	flex-wrap: wrap;
}
::-webkit-scrollbar{
	background: black;
}
::-webkit-scrollbar-thumb{
	background: gray;
}
</style>>