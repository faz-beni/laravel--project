<template>
    <div class="todoListContainer">
       <div class="heading">
           <h2 id="title">Todo List</h2>
           <add-item-form/>
       </div>
        <list-view/>
    </div>
</template>

<script>
import addItemForm from "./addItemForm";
import listView from "./listView";
export default {
components:{
    addItemForm,
    listView
}

}
</script>

<style scoped>

.todoListContainer{
    width: 350px;
    margin: auto;
}

.heading{
    background: lightgray;
    padding: 10px;
}
#title{
text-align: center;
}
</style>
