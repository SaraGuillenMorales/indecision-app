<script setup lang="ts">
import MeusNumerator from './components/MeusNumerator.vue';
import MeusNumeratorScript from './components/MeusNumeratorScript.vue';

</script>

<template>
    <h1>Mi primera app de Vue</h1>
    <h1>Hello world</h1>

    <MeusNumerator :valorem="7" />
    <MeusNumeratorScript :valorem="10" />
    <MeusNumeratorScript2 :valorem="2" />

</template>

<script lang="ts" setup>
import MeusNumerator from './components/MeusNumerator.vue';
import MeusNumeratorScript from './componets/MeusNumeratorScript.vue';
import MeusNumeratorScript2 from './components/MeusNumeratorScript2.vue';

</script>