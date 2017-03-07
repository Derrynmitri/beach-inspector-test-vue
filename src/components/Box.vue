<template>
	<div class="box">
		<p>
			<slot></slot>
		</p>
	</div>	
</template>

<script>
	export default {
		
	}
</script>

<style>
	.box {
		background : #e3e3e3;
		width: 250px;
		height: 100px;
		padding: 10px;
		display: inline-block;
		margin: 0 10px 0 10px;
	}
</style>