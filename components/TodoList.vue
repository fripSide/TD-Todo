<template>
	<div class="todo-list">
		<ul>
			<li v-for="(todo, index) in todos" :key="index">
				{{ todo }}
			</li>
		</ul>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				todos: ["任务1", "任务2", "任务3"],
			};
		},
	};
</script>

<style>
	.todo-list {
		margin: 20px;
	}
</style>