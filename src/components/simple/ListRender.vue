<template>
    <ol>
        <li v-for="todo in todos">{{ todo.text }}</li>
    </ol>
</template>
<script>
export default {
    data() {
        return {
            todos: [
                { id: 1, text: 'fruit' },
                { id: 2, text: 'vegetables' },
                { id: 3, text: 'food' },
            ]
        }
    }
}
</script>