    <script setup>
        import { defineComponent } from 'vue';

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
        <div class="todo-actions">
            <svg xmlns="http://www.w3.org/2000/svg" width="22px" height="22px" viewBox="0 0 256 256">
		<path fill="#41b080" d="M173.66 98.34a8 8 0 0 1 0 11.32l-56 56a8 8 0 0 1-11.32 0l-24-24a8 8 0 0 1 11.32-11.32L112 148.69l50.34-50.35a8 8 0 0 1 11.32 0M232 128A104 104 0 1 1 128 24a104.11 104.11 0 0 1 104 104m-16 0a88 88 0 1 0-88 88a88.1 88.1 0 0 0 88-88" />
	</svg>
        </div>
    </li>
</template>


<style lang="scss" scoped>

</style>