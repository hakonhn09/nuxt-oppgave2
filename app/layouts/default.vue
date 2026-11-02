<template>
    <div>
        <header>
            <nav>
                <NuxtLink to="/">Hjem</NuxtLink>
                <NuxtLink to="/api">API-data</NuxtLink>
            </nav>
        </header>

        <main>
            <slot />
        </main>

        <footer>
            <!--L -->
        </footer>
    </div>
</template>