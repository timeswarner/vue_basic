<template>
    <!-- 组件的结构 -->
    <div >
        <div>{{ name }}</div>
        <div>{{ age }} </div>
    </div>
</template>

<script>
// 组件交互相关的代码（数据，方法等等）

export default {
    name: 'Student',
    data() {
        return {
            name: 'tom',
            age: 18
        }
    },
}
</script>


<style>
/* 组件的样 */

</style>