<template>
    <!-- <div>面包屑组件</div> -->
         <el-breadcrumb separator="/">
           <el-breadcrumb-item>首页</el-breadcrumb-item>
           <el-breadcrumb-item>{{level1}}</el-breadcrumb-item>
           <el-breadcrumb-item>{{level2}}</el-breadcrumb-item>
        </el-breadcrumb>   
</template>
<script>
export default {
    props:['level1','level2']
}
</script>
<style lang="less" scoped>

</style>