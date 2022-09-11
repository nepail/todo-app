<template>
    <div class="todo-list">
        <TodoListItem v-for="n in 3" :key="n"></TodoListItem>
    </div>
</template>

<script setup>
import TodoListItem from './TodoListItem.vue'
</script>

<style scoped>
.todo-list {
    display: grid;
    row-gap: 14px;
}
</style>