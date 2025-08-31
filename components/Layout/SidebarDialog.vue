<script setup lang="ts">

const visible = ref(false);
</script>
<template>
    <div class="sidebar">
        <Drawer v-model:visible="visible" :dismissable="true" position="right" style="width: 50%; background: none; backdrop-filter: blur(5px);border: none;" class="">
            <template #closebutton>
                    <IconsCloseIcon @click="visible = false" style="width: 20%;cursor: pointer;" />
            </template>
            <div class="sidebar-links">
                <ul class="sidebar-links-list">
                    <NuxtLink to="/">
                        <li class="sidebar-link ">Home</li>
                    </NuxtLink>
                    <NuxtLink to="/">
                        <li class="sidebar-link">About</li>
                    </NuxtLink>
                    <NuxtLink to="/">
                        <li class="sidebar-link">Projects</li>
                    </NuxtLink>
                    <NuxtLink to="/">
                        <li class="sidebar-link">Experience</li>
                    </NuxtLink>
                </ul>
            </div>
        </Drawer>
        <IconsBarsIcon class="sidebar-btn" @click=" visible = true" />
    </div>
</template>
