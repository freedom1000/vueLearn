<template>
    <div>
        <h1>利用URL传参</h1>
        <!-- 将route中path中的Id和name传过来 -->
        <h1>userId: {{ $route.params.userid }}</h1>
        <h1>username: {{ $route.params.username }}</h1>
    </div>

</template>
<script>
export default {
};
</script>
<style lang='' scoped>
</style>
