<template>
  <div class="bluetooth-api">

    <MainBlock title="Web Bluetooth API">

      <DefinitionBlock :description="description"/>

      <Example1/>

    </MainBlock>

  </div>
</template>

<script>
import MainBlock from '@/components/MainBlock.vue'
import DefinitionBlock from '@/components/DefinitionBlock'
import Example1 from './Example1'

import data from './data'

export default {
  name: 'AudioAPI',
  components: {
    MainBlock,
    DefinitionBlock,
    Example1
  },
  data () {
    return {
      description: data.description
    }
  }

}
</script>

<style scoped>

</style>
