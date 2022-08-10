<template>
    <v-app-bar app color="#8B008B" dark flat class="px-8">
     <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('project')">Project</v-btn>
    <v-btn text @click="scroll('contact')"> contact</v-btn>
</v-app-bar>
</template>
<script> 
export default{
    methods: {
        scroll(refName){
            const element =document.getElementById(refName);
            element.scrollIntoView({behavior:"smooth"});
        }
    }

}
</script>
<style>
</style>