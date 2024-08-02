<template>
	<div class="container">
		<h1>待办事项列表</h1>
		<TodoList/>
	</div>
</template>

<script>
	import TodoList from "@/components/TodoList";
	export default {
		components: {
			TodoList,
		},
	}
</script>

<style>
	.container {
		text-align: center;
		padding: 20px;
	}
</style>
