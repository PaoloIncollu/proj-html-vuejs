<script>
import SectionCounts from './SectionCounts.vue';
import SectionCauses from './SectionCauses.vue';
import SectionValues from './SectionValues.vue';
import SectionArticles from './SectionArticles.vue';
export default {
  data() {
    return { 
      
    }
  },
  components:{

    SectionCounts,
    SectionCauses,
    SectionValues,
    SectionArticles
  }
}
</script>

<template>
 <main>

  <SectionCounts/>
  <SectionValues/>
  <SectionCauses/>
  <SectionArticles/>
  
 </main>
</template>

<style lang="scss" scoped>

main{

  width: 100%;
}
</style>
