<template>
  <section>
    <Caption/>
    <Card/>
  </section>
</template>
<script>
import Caption from '@/components/servicesComp/Caption.vue'
import Card from '@/components/servicesComp/Card.vue'
export default {
  name : "Services",
  components :{
    Caption,
    Card
  }
}
</script>
