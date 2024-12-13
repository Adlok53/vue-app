<template>
    <div>
        <h2>Заметка: {{ oneNote.title }}</h2>
        <strong>Прочитано:</strong>
    </div>
</template>

<script>
export default {
    props: ["oneNote"],
    data() {
        return {}
    }
}
</script>