<template>
    <div class="lab">
        <!-- <h1>This is a lab page</h1> -->
        <div class="w-11/12 mx-auto rounded-xl shadow-lg mb-20 mt-20">
            <router-link to="/pokeAPI">
                <h1 class="font-black md:text-3xl text-xt green mb-2">Pokemon API</h1>
                <img src="../assets/img/poke_API.png" alt="thumbnail of project">
            </router-link>
        </div>
        <div class="w-11/12 mx-auto rounded-xl shadow-lg mb-20">
            <router-link to="todoLIST">
                <h1 class="font-black md:text-3xl text-xt green mb-2">ToDo List</h1>
                <img src="../assets/img/todo_list.png" alt="thumbnail of project">
            </router-link>
        </div>
    </div>
  </template>
  
  <style>
  @media (min-width: 1024px) {
    .lab {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
  }
  </style>