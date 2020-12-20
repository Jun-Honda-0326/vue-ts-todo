<template>
  <form>
    <input type="text" v-model="newItem">
    <p>{{ newItem }}</p>
  </form>
</template>

<script lang="ts">
import { Component, Vue} from 'vue-property-decorator';

@Component
export default class TodoForm extends Vue{
    newItem = ''
}
</script>
