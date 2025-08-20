<script setup lang="ts">


const position = ref('center');
const visible = ref(false);

const openPosition = (pos) => {
    position.value = pos;
    visible.value = true;
}
</script>
<template>
    <div class="navbar-container">
        <div class="navbar-logo">
            <NuxtImg src="/images/logo3.png" />
        </div>

        <div class="navbar-links">
            <ul class="links-list">
                <NuxtLink to="/">
                    <li class="link">Home</li>
                </NuxtLink>
                <NuxtLink to="/">
                    <li class="link">About</li>
                </NuxtLink>
                <NuxtLink to="/">
                    <li class="link">Projects</li>
                </NuxtLink>
                <NuxtLink to="/">
                    <li class="link">Experience</li>
                </NuxtLink>
            </ul>
        </div>

        <div class="sidebar">
            <LayoutSidebarDialog />
        </div>
    </div>
</template>

<style scoped lang="scss">

</style>