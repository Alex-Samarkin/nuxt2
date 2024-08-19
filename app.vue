<template>
  <div>
    <h1>Index Page</h1>
    <NuxtLink to="/">Home</NuxtLink><br />
    <NuxtLink to="/about">About</NuxtLink>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    <NuxtRouteAnnouncer />
    
  </div>
</template>
