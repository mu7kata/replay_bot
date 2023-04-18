<template>
    <div>
        <h1>Hello, {{ name }}!</h1>
    </div>
</template>

<script>
export default {
    name: 'example-component',
    data() {
        return {
            name: 'world'
        }
    }
}

</script>

<style scoped>

</style>
