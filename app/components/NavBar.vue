<template>
    <header class="sticky top-0 z-10 px-4 pt-4">
    <nav
        class="mx-auto flex max-w-3xl items-center justify-between rounded-full bg-ink p-2 shadow-lg ring-4 ring-sage"
    >
        <span class="px-4 font-bold text-mint">Krisha Mae A. Libot</span>

        <div class="flex gap-1">
        <NuxtLink
            to="/"
            class="rounded-full px-5 py-2 font-semibold text-mint transition hover:bg-bark"
            exact-active-class="bg-sage! text-ink!"
        >
            Home
        </NuxtLink>
        <NuxtLink
            to="/profile"
            class="rounded-full px-5 py-2 font-semibold text-mint transition hover:bg-bark"
            exact-active-class="bg-sage! text-ink!"
        >
            Profile
        </NuxtLink>
        </div>
    </nav>
    </header>
</template>