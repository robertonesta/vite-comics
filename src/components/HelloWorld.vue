<script>
export default {
    name: "HelloWorld",
    data() {
        return {
            message: "Hello world"
        }
    }
}
</script>

<template>
  <h1>{{ message }}</h1>
  <ul>
    <li>Ciao</li>
    <li>Ciao</li>
    <li>Ciao</li>
  </ul>
</template>

<style scoped lang="scss">
ul {
    background-color: red;

    li {
        background-color: blue;
    }
}
</style>