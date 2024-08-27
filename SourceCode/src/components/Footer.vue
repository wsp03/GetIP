<template>

    <n-flex vertical>
        <n-text class="my-center">&copy; {{ url.join('') }}</n-text>
    </n-flex>
</template>

<script setup>
const url = ["S", "u", "i", "c", ".", "c", "n"]
</script>

<style scoped>
.my-center {
    margin-left: auto;
    margin-right: auto;
    padding-top: 24px;
    padding-bottom: 24px;
}
</style>
