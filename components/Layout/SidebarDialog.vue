<script setup lang="ts">

const visible = ref(false);
</script>
<template>
    <div class="sidebar">
        <Drawer v-model:visible="visible" :dismissable="true" position="right" style="width: 50%;" class="">
            <template #closebutton>
                    <IconsCloseIcon @click="visible = false" style="width: 20%;cursor: pointer;" />
            </template>
        </Drawer>
        <IconsBarsIcon class="sidebar-btn" @click=" visible = true" />
    </div>
</template>
