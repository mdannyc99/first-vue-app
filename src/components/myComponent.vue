<template>
<div id="my-component">
    <hr/>
    <h1>This is my new component</h1>
    <h2>{{ subtitle }}</h2>
    <hr/>
</div>
    
</template>

<script>
export default {
    name: 'myComponent',
    data(){
        return {
            subtitle: "I'm the subtitle of myComponent"
        }
    }
}
</script>