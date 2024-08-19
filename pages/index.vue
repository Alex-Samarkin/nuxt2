<template>
    <div>
        <h1>Index Page</h1>
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/about">About</NuxtLink>
        <NuxtPage />
        <NuxtRouteAnnouncer />

        
        <Comp1 />

        <MyH1 msg="Hello1" lvl="100"/>
        <Counter />
    </div>
</template>