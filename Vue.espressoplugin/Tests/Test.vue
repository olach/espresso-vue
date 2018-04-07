<template>
	<p>{{greeting}} World!</p>
</template>

<script>
module.exports = {
	data: function () {
		return {
			greeting: 'Hello'
		}
	}
}
</script>

<style lang="scss" scoped>
p {
	font-size: 2em;
	text-align: center;
	
	& .green {
		color: green;
	}
}
</style>
