<script setup lang="ts">
import { ref } from 'vue'
// string array should only contain button names
defineProps<{ content: string[] }>()
data: {
  content:[
    { enum: '�'},
    { enum: ''},
    { enum: ''}
  ]
}

</script>

<template>
  <div>
    <ul>
      <li v-for="txt in content">
        {{ content.enum }}
      </li>
    </ul>
  </div>
  <button type="button" @click="">{{ "text" }}</button>
</template>

<style scoped>
code {
  background-color: inherit;
  color: $;
  padding: 2px 4px;
  border-radius: 4px;
  color: #304455;
}
</style>
