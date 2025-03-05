<template>

<div class="p-4 flex-1 overflow-auto">
    <div class="flex flex-col space-y-2">

            <ChatBullula: meus-est="true" nuntius=""Salimos luego a dar una vuelta? />

</div>
</div>

</template>

<script lang="ts" setup>
import type { ChatNuntius } from '@/interfaces/chat-nuntius.interface.ts';
import ChatBullula from '@/components/chat/chatBullula.vue';

interface Props {
    nuntii: ChatNuntius[];
}

defineProps<Props>()

</script>