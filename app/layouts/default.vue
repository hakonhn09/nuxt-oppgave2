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
            Håkon 2026
        </footer>
    </div>
</template>