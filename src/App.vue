<template>
  <div>
    {{title}}
  </div>
</template>


<script lang="ts">

import { Vue, Component } from 'vue-property-decorator';

@Component
export default class HelloDecorator extends Vue {
  
  public title = "123";
}
</script>
