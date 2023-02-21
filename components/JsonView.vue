<template>
    <div>
        <div v-html="impview">
        </div>
    </div>
</template>

<script>
import * as importview from "../assets/html/importview.json";
export default {
    name: 'JsonView',
    data(){
        return {
            impview: importview.imphtml
        }
    }
}
</script>
<style scoped></style>