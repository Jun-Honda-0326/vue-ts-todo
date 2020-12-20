<template>
  <div class="home">
    <p>{{ greetText }}</p>
    <TodoForm></TodoForm>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import TodoForm from "@/components/TodoForm.vue";

@Component({
  components: {
    TodoForm
  }
})
export default class Home extends Vue {
  public greetText = "Hello Vue.js";
}
</script>
