<template>
    <span class="p-0.5">{{ message }}</span>
    <button @click="reverseText">reverse</button>
    <br />
</template>
<script>
export default {
    data() {
        return {
            message: 'vue vuex vue-router vite'
        }
    },
    methods: {
        reverseText() {
            this.message = this.message.split("").reverse().join("");
        }
    }
}
</script>