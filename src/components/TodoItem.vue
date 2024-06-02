    <script setup>
    const props = defineProps({
        todo :{
            type : Object ,
            required : true,
        },
    });
    </script>
<template>
    <li>
        <input type="checkbox"  :checked="todo.isCompleted">
        <div class="todo">
            <input type="text" :value="todo.todo">
            <span>
                {{ todo.todo }}
            </span>
        </div>
        <div class="todo-actions"></div>
    </li>
</template>


<style lang="scss" scoped>

</style>