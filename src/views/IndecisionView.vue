<template>

<div class="bg-gray-100 h-screen flex flex-col max-w-lg mx-auto">
<div class="bg-blue-500 p-4 text-white flex justify-between items-center">
    <span>Mi esposo</span>
</div>

<ChatNuntii />

<textusArca />

</div>

</template>


<script lang="ts" setup>
import ChatNuntii from '@/components/chat/chatNuntii.vue';
import textusArca from '@/components/chat/textusArca.vue';

</script>