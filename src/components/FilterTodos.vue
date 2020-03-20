<template>
    <div>
        Filter Todos:
    </div>
    <select>
        <options value="200">200</options>
        <options value="100">100</options>
        <options value="50">50</options>
        <options value="20">20</options>
        <options value="10">10</options>
        <options value="5">5</options>
    </select>
</template>
<script>
    export default {
      name:"FilterTodos"
    }
</script>
<style>
    select{
        margin-top: 20px;
        padding: 6px;
        border: #41b883 1px solid;
    }
</style>
