<template>
    <Body style="min-height:100vh;"></Body>

    <div style="min-height:100vh;">
        <main style="min-height:100vh;">
            <NuxtPage />
        </main>

        <footer style="padding-top: 100px; display: flex; flex-direction: column;">
            <NuxtLink style="padding: 10px 0; font-size: 18px;" to="/">Home</NuxtLink>
            <NuxtLink style="padding: 10px 0; font-size: 18px;" to="/page2">Page 2</NuxtLink>
        </footer>
    </div>

</template>
