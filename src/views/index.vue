<template>
    <div>
        Home
        {{title}}
    </div>
</template>
<script lang="ts">
import { defineComponent, reactive } from 'vue'
export default defineComponent({
    setup(){
        const title=reactive<String>("标题")
        return {title}
    }
})
</script>

