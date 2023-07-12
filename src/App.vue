<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div>
      <nav><ul>
       <li> <RouterLink to="/">Home</RouterLink></li>
        <li><RouterLink to="/LessionOne">LessionOne</RouterLink></li>
        </ul>
      </nav>
    </div>
  </header>
  <RouterView />
</template>
