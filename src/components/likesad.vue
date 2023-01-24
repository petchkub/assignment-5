<template>
    <button type="button" class="btn btn-success" @click="countlike">Like {{like}}</button>
    <button type="button" class="btn btn-danger" @click="countsad">Sad {{sad}}</button>
</template>
<script setup>
import {ref} from "vue";
const like = ref(0);
const sad = ref(0);

function countlike(){
    like.value++;
}

function countsad(){
    sad.value++;
}


</script>
<script>
export default{
    name: "Countlikesad"
}   

</script>