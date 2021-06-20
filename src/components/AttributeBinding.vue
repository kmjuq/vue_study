<template>
    <span :title="message">鼠标悬停几秒钟查看此处动态绑定的提示信息！</span>
    <br />
</template>
<script>
export default {
    data() {
        return {
            message: new Date().toLocaleString()
        }
    }
}
</script>