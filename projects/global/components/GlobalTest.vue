<template>
    <div class="global-test">
        Test. {{ label }}
    </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
    name: 'GlobalTest',
    props: {
        label: {
            type: String,
            default: '',
        },
    },
});
</script>

<style scoped>
</style>
