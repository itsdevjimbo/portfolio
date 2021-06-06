<template>
    <div class="flex justify-center">
        <h1 class="text-2xl uppercase font-light px-12 border-b-4 pb-4 border-black"
            :class="titleClass">
            {{title}}
        </h1>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            required: true
        },
        textClass: {
            type: String,
            default: ''
        },
        borderClass: {
            type: String,
            default: ''
        },
    },
    computed: {
        titleClass() {
            return `${this.textClass} ${this.borderClass}`
        }
    }
}
</script>