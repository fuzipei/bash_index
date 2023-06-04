<template>
  <div>关于本站：Bash_index
    原创：YuIndex
  </div>
  
</template>

<script setup lang="ts">
interface InfoBoxProps {
  seconds: string;
}

const props = withDefaults(defineProps<InfoBoxProps>(), {});
</script>

<style scoped></style>
