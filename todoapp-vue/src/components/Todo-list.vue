<template>
<div class="lista">
    <h1>ToDoList with Vue.js</h1>
    <div class="input-task">
    <input v-model.trim="task" type="text" placeholder="Type your task">
    <button class="add" v-on:click="addTask" type="button">Add Task</button>
    </div>
    
    <ul>
        <li v-for="(task, index) in tasks" :key="task">
            {{task}}
            <button class="remove" v-on:click="removeTask(index)">Remove</button>
        </li>
    </ul>
</div>
    
</template>
<script>

    export default{
        name:"TodoList",
        data(){
            return{
                task:"",
                tasks:[]
            }
        },
        methods: {
            addTask(){
                if(this.task.trim()){
                this.tasks.push(this.task)
                this.task=""
                }
                
            },
            removeTask(index){
                this.tasks.splice(index, 1);
            }
        }
    }
</script>
