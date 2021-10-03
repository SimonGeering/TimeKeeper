<template>
  <div class="time-log">
    <h1>{{ msg }}</h1>
    <h3>Installed CLI Plugins</h3>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class TimeLog extends Vue {
  @Prop() private msg!: string;
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
}
</style>
