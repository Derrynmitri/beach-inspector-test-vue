<template>
  <div id="app">
    <banner />
    <div class="row">
    	<box>This is an example box</box>
    	<box>This is an example box</box>
    	<box>This is an example box</box>
    </div>
    <div class="row" v-if="showMore">
    	<box>This is an example box</box>
    	<box>This is an example box</box>
    	<box>This is an example box</box>
    </div>
    <div class="row">
    	<button class="button" @click="showMore = !showMore">Show More</button>
    </div>
  </div>
</template>

<script>
import Banner from './components/Banner.vue'
import Box from './components/Box.vue'
export default {
  name: 'app',
  components: { Banner, Box },
  data () {
    return {
    	showMore: false
    }
  }
}
</script>

<style>
body {
	margin: 0px;
}
.row {
	margin: 20px auto;
	text-align: center;
	display: block;
}
.button {
	width: 150px;
	height: 30px;
	background-color: #f7b937;
	border-radius: 2px;
	border: none;
}
.button:hover {
	background-color: #dc9909;
}
</style>
