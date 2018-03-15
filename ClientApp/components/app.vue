<template>
    <div>
        <span class="orange">Counter: {{ counter }} </span> 
        <button @click="inc">Inc</button>
    </div>
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
<style scoped>
.orange {
    color: orange;
}
</style>
