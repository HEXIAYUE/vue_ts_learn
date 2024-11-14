<!-- 组件说明 -->
<template>
    <div class="person">
        <div class="person">age:{{ age }}</div>
        <button @click="addAge">增加年龄</button>
    </div>
</template>

<script lang="ts">
//import x from ''
export default {
    name: "Person",
    // components: {},
    // data() {
    //     return {
    //         age: 10,
    //     };
    // },
    // computed: {},
    // methods: {
    //     addAge() {
    //         this.age++;
    //     },
    // },

    setup() {
        let age = 10;
        function addAge() {
            age++;
        }
        return {
            age,
            addAge,
        };
    },
};
</script>

<style scoped></style>
