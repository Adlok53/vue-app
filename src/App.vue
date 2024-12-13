<template>
    <div class="container-fluid">
        <h1>App</h1>
        <my-notes v-for='note in notes' v-bind:key="note" v-bind:oneNote="note"></my-notes>
    </div>
</template>

<script>
import MyNotes from "./MyNotes"
export default {
    data() {
        return {
            notes: [
                {title: "Почистить зубы", message: "One"},
                {title: "Покушать", message: "Two"},
                {title: "Сходить на работу", message: "Three"}
            ]
        }
    },
    components: {
        MyNotes
    }
}
</script>

<style>

</style>
