<template>
    <!-- 组件的结构 -->
    <div class="demo">
        <div>{{ schoolName }}</div>
        <div>{{ address }} </div>
    </div>
</template>



<script>
// 组件交互相关的代码（数据，方法等等）
//定义school组件
export default {
    name: 'School',
    data() {
        return {
            schoolName: '尚硅谷',
            address: '北京'
        }
    },
}

</script>


<style>
/* 组件的样 */
.demo {
    background-color: orange;
}
</style>