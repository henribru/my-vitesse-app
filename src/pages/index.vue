<script setup lang="ts">
import { defineProps } from 'vue'
import { Popover, PopoverPanel, PopoverButton } from '@headlessui/vue'

defineProps({
  message: String,
})
</script>

<template>
  <div>
    <Popover>
      <PopoverButton>Click me</PopoverButton>
      <PopoverPanel>Foo</PopoverPanel>
    </Popover>
  </div>
</template>

<route lang="yaml">
meta:
  layout: home
</route>
