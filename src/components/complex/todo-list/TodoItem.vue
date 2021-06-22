<template>
    <li>{{ item }}</li>
</template>
<script>
export default {
    name: 'TodoItem',
    props: {
        item: {
            type: String,
            default: ''
        }
    }
}
</script>