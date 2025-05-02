<script setup></script>

<template>
    <button v-bind="$attrs" class="button">
        <slot />
    </button>
</template>

<style scoped>
.button {
    padding: 16px 10px;
    border-radius: 100px;
    color: var(--color-bg-content);
    font-size: 24px;
    line-height: 36px;
    border: none;
    background-color: var(--color-accent);
    min-width: 335px;
}
</style>