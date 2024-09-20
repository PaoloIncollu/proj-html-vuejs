<script>
import SectionCounts from './SectionCounts.vue';
import SectionCauses from './SectionCauses.vue';
import SectionValues from './SectionValues.vue';
import SectionArticles from './SectionArticles.vue';
import SectionChangeLife from './SectionChangeLife.vue';
export default {
  data() {
    return { 
      
    }
  },
  components:{

    SectionCounts,
    SectionCauses,
    SectionValues,
    SectionArticles,
    SectionChangeLife
  }
}
</script>

<template>
 <main>

  <SectionCounts/>
  <SectionValues/>
  <SectionCauses/>
  <SectionArticles/>
  <SectionChangeLife/>
  
 </main>
</template>

<style lang="scss" scoped>

main{

  width: 100%;
}
</style>
