<template>
    <footer>
        <p>Copyright &copy; {{ year }}</p>
        <a href="/about">About</a>
    </footer>
</template>

<script>
export default {
    name: 'Footer',
    data() {
        return {
            year: new Date().getFullYear()
        }
    }
}
</script>

<style scoped>
    a {
        color: #333;
    }

    footer {
        margin-top: 30px;
        text-align: center;
    }
</style>