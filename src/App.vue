<template>
  <HelloWorld msg="Hello Vue 3 + Vite" />
  <Counter />
  <AttributeBinding />
  <ReverseText />
  <FormBinding />
  <ConditionalRender />
  <ListRender />
  <TodoList />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Counter from './components/simple/Counter.vue'
import AttributeBinding from './components/simple/AttributeBinding.vue'
import ReverseText from './components/simple/ReverseText.vue'
import FormBinding from './components/simple/FormBinding.vue'
import ConditionalRender from './components/simple/ConditionalRender.vue'
import ListRender from './components/simple/ListRender.vue'
import TodoList from './components/complex/todo-list/TodoList.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
/*! @import */
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
