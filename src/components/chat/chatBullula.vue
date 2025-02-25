<template>

     <div v-if="meusEst" class="flex justify-end">
        <div class="bg-blue-200 text-black p-2 m-w-xs rounded-b-lg">
         {{ nuntius }}
        </div>
    </div>

<div v-else class="flex">
    <div class="bg-gray-300 text-black p-2 m-w-xs rounded-b-lg">
        {{ nuntius }}
    </div>
</div>

</template>

<script lang="ts" setup>
interface Props {
    nuntius: string;
    meusEst: boolean;
    imago?: string;
}

defineProps<Props>();

</script>