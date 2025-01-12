<template>
    <div v-if="store.isVisible"
        class="transition ease-in-out delay-500 duration-500 px-6 fixed top-full right-8 rounded-xl shadow-xl"
        :class="store.classes">
        {{ store.message }}
    </div>
</template>

<script setup>
import { useToStore } from '@/stores/toast'
const store = useToastStore()

return {
    store
}
</script>