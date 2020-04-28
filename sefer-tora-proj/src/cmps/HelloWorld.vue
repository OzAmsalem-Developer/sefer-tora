<template>
  <div class="hello" v-if="perekA">
    {{perekA}}
  </div>
</template>

<script>
import {pasukService} from '@/services/psukim.service.js'

export default {
data() {
  return {
    perekA: pasukService.txt
  }
},

}
</script>

