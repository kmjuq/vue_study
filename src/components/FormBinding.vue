<template>
    <span class="p-0.5">{{ message }}</span>
    <input class="border-2 border-blue-400" type="text" v-model="message" />
    <br />
</template>
<script>
export default {
    data() {
        return {
            message: ''
        }
    }
}
</script>