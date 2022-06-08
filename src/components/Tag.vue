<script>
export default {
    props: {
        text_item: String
    }
}

</script>


<template>
    <div
        style="display: flex; align-content: center; justify-content: center; background-color: #b294f8;">
        <text style="color: white; font-style: bold;">{{ text_item }}</text>
    </div>

</template>

