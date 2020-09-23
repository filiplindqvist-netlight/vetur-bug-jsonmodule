<template>
  <div>
    {{ json }}
  </div>
</template>

<script lang="ts">
import * as _ from 'lodash'
import * as json from './data.json'

export default {
  props: ['foo', 'bar'],
  data() {
    return { json }
  }
}
</script>