<template>
    <ol>
        <TodoItem v-for="todo in todos" :item="todo.text" :key="todo.id" />
    </ol>
</template>
<script>
import TodoItem from './TodoItem.vue'

export default {
    components: { TodoItem },
    data() {
        return {
            todos: [
                { id: 1, text: 'fruit--' },
                { id: 2, text: 'vegetables--' },
                { id: 3, text: 'food--' },
            ]
        }
    }
}
</script>