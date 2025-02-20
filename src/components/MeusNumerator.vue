
<template>
    <section>
        <h3>Counter: {{ numerus }}</h3>
        <h3>Square: {{ quadrataNumerus }}</h3>

    <div>
        <button @click="numerus++">+1</button>
        <button @click="numerus--">-1</button>
    </div>

    </section>
</template>

<script lang="ts" setup>
import { computed, ref } from 'vue';

const props = defineProps<{ valorem: number }>();

const numerus = ref(2)
const quadrataNumerus = computed(()=> numerus.value * numerus.value);

</script>
