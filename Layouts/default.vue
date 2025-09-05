<script setup lang="ts">
import { LayoutNavbar } from '#components';

</script>
<template>
    <div class="page-layout">
        <LayoutNavbar />
        <slot />
        <!-- <LayoutFooter /> -->
    </div>
</template>

<style scoped lang="scss">

</style>