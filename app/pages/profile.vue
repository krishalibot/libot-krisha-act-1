<template>
    <section class="mx-auto max-w-4xl px-6 py-12">
    <h1 class="text-center text-5xl font-extrabold text-ink">My Profile</h1>
    <div class="mx-auto mt-3 h-2 w-24 rounded-full bg-olive"></div>

    <div class="mt-10 grid gap-6 md:grid-cols-2">
        <!-- Personal Information -->
        <div class="rounded-3xl bg-ink p-6 text-mint shadow-lg">
        <h2 class="mb-3 text-2xl font-bold text-sage">Personal Information</h2>
        <ul class="space-y-1">
            <li><span class="font-semibold">Name:</span> Krisha Mae A. Libot</li>
            <li><span class="font-semibold">Age:</span> 20</li>
            <li><span class="font-semibold">Birthday:</span> 10/29/2006</li>
            <li><span class="font-semibold">Family:</span> 1 sibling and mom</li>
            <li><span class="font-semibold">Address:</span> Millennium Village Bonbon Butuan City</li>
        </ul>
        </div>

        <!-- Educational Background -->
        <div class="rounded-3xl bg-bark p-6 text-mint shadow-lg">
        <h2 class="mb-3 text-2xl font-bold text-sage">Educational Background</h2>
        <ul class="space-y-3">
            <li>
            <span class="font-semibold">Elementary:</span><br />
            Graduated at Latrinidad Elementary School
            </li>
            <li>
            <span class="font-semibold">High School:</span><br />
            Graduated at Butuan City School of Art and Trades (Strand: GAS)
            </li>
        </ul>
        </div>

        <!-- Skills and Interests -->
        <div class="rounded-3xl bg-olive p-6 text-mint shadow-lg">
        <h2 class="mb-3 text-2xl font-bold text-ink">Skills and Interests</h2>

        <h3 class="font-semibold text-ink">Skills</h3>
        <div class="mb-4 mt-2 flex flex-wrap gap-2">
            <span class="rounded-full bg-ink px-4 py-1 text-sm">Basic Programming</span>
            <span class="rounded-full bg-ink px-4 py-1 text-sm">Web Development</span>
        </div>

        <h3 class="font-semibold text-ink">Interests</h3>
        <div class="mt-2 flex flex-wrap gap-2">
            <span class="rounded-full bg-mint px-4 py-1 text-sm text-ink">Creative writing</span>
            <span class="rounded-full bg-mint px-4 py-1 text-sm text-ink">Board games</span>
            <span class="rounded-full bg-mint px-4 py-1 text-sm text-ink">Book collecting</span>
            <span class="rounded-full bg-mint px-4 py-1 text-sm text-ink">Art</span>
        </div>
        </div>

        <!-- Hobbies -->
        <div class="rounded-3xl bg-sage p-6 text-ink shadow-lg">
        <h2 class="mb-3 text-2xl font-bold">Hobbies</h2>
        <ul class="space-y-2">
            <li class="rounded-full bg-mint px-4 py-2">Reading</li>
            <li class="rounded-full bg-mint px-4 py-2">Listening to podcasts</li>
            <li class="rounded-full bg-mint px-4 py-2">Board games</li>
        </ul>
        </div>
    </div>

    <div class="mt-10 text-center">
        <NuxtLink
        to="/"
        class="inline-block rounded-full bg-ink px-8 py-3 font-semibold text-mint transition hover:bg-olive"
        >
        ← Back to Home
        </NuxtLink>
    </div>
    </section>
</template>