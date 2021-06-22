<template>
    <span v-if="seen" class="text-black">条件渲染</span>
    <br />
</template>
<script>
export default {
    data() {
        return {
            seen: true
        }
    }
}
</script>