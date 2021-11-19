<template>
    <div class="comp">
        <Content/>
        <Brand/>
    </div>
</template>
<style>
    .comp{
        height: 64vh;
    }
</style>
<script>
import Content from '@/components/clientComp/Content.vue'
import Brand from '@/components/clientComp/Brand.vue'
export default {
    name: "Client",
    components :{
        Content,
        Brand
    }
}
</script>