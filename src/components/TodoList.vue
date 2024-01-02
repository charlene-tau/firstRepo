<template>
    <div>
        <h1>My To Do List</h1>
        <input type="text" v-model="newTodo" placeholder="Enter your task" @keyup.enter="addTodo">
    </div>
</template>
<script>
export default {
    data(){
        return {
            newTodo:'',
            todos:[]
        }
    },
    methods:{
        addTodo(){
console.log("enter key pressed")
console.log(this.newTodo)
        }
    }
}
</script>
<styles>
</styles>