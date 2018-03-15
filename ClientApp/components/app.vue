<template lang="pug">
div
    span.orange Counter: {{ counter }}
    div 
        button(@click="inc") Increase
</template>
<script>
export default {
    data() {
        return {
            counter: 0
        }
    },
    methods: {
        inc() {
            this.counter++;
        }
    }
}
</script>
<style lang="scss" scoped>
$color: blue;

.orange {
    background-color: $color;
    color: white;
    font-size: 16vmin;
}
</style>
