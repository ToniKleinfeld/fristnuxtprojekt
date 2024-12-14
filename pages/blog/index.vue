<template>
    <div>
        Index of blog
    </div>
    <div>
        <button @click="enableCustomLayout">Update layout</button>
    </div>
</template>

<script setup>
function enableCustomLayout() {
    setPageLayout('custom')
}
</script>