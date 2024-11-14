<script lang="ts">
export default {
    name: "app",
    components: {
        Person,
    },
};

import Person from "./components/Person.vue";
</script>
<template>
    <Person></Person>
</template>
<style>
.app {
    color: red;
}
</style>
