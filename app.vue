<template>
    <div>
      <h1>Welcome to My Nuxt.js App</h1>
      <h2>{{ heading }}</h2>
      <button @click="incrementCounter">Increment</button>
      <p>Counter: {{ counter }}</p>
    </div>
  </template>
  
  <script setup>

  
  const counter = ref(0);
  const heading = 'Counter App';
  
  const incrementCounter = () => {
    counter.value++;
  };
  </script>
  
  <style>

  </style>
  
