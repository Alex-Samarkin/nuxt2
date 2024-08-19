<script setup>

const props = defineProps(['msg', 'lvl'])
props.msg = 'Hello World'
props.lvl = 1
</script>

<template>
    <span>
        <h1> >>> {{ msg }} {{ lvl }}<<< </h1>
    </span>
</template>