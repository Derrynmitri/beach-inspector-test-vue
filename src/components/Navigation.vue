<template>
	<div class="headerContainer">
		<h3 class="logo">Beach-Inspector</h3>
		<div class="links">
			<button class="selected">Home</button class="button">
			<button class="navbutton">Beaches</button class="button">
			<button class="navbutton">Blog</button class="button">
			<button class="navbutton">About</button class="button">
		</div>
	</div>	
</template>

<script>
	export default {
		
	}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto');
	.headerContainer {
		font-family: 'Roboto', sans-serif;
		background : #ffffff;
		width: 100%;
		height: 50px;
		display: block;
		margin: auto;
		top: 0;
		left: 0;
	}
	.logo {
		display: inline-block;
		margin: 10px 0 0 10px;
	}
	.links {
		display: inline-block;
		margin: 10px 10px 0 0;
		float: right;
	}
	.navbutton {
		width: 100px;
		height: 30px;
		border-radius: 2px;
		border: none;
		background-color: #d9d9d9;
	}
	.navbutton:hover {
		width: 100px;
		background-color: #0097d9;
	}
	.selected {
		width: 100px;
		height: 30px;
		border-radius: 2px;
		border: none;
		background-color: #0097d9;
	}
</style>