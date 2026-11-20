<template>
  <section class="mx-auto max-w-5xl px-6 py-16">
    <div class="mx-auto max-w-3xl">
      <p class="inline-block rounded-full bg-olive px-4 py-1 text-sm font-semibold text-mint">
        3rd Year · Information Technology
      </p>

      <div class="my-10 flex items-center gap-8">
        <div class="relative ml-4 h-64 w-64 shrink-0">
          <div class="absolute inset-0 translate-x-4 translate-y-4 rounded-full bg-olive"></div>
          <div class="absolute inset-0 -translate-x-4 -translate-y-4 rounded-full bg-sage"></div>
          <img
            src="/profile.png"
            alt="Profile picture of Krisha Mae A. Libot"
            class="relative h-full w-full rounded-full border-8 border-ink object-cover object-[center_40%] shadow-xl"
          />
        </div>

        <h1 class="min-w-0 text-3xl font-extrabold leading-tight text-ink md:text-5xl">
          Krisha Mae A. Libot
        </h1>
      </div>

      <p class="mt-4 text-lg text-bark">
        I'm a 20-year-old 3rd year college student taking Information Technology.
        I love turning ideas into things people can see and enjoy, whether it's a
        story, a drawing, or a web page.
      </p>

      <div class="mt-8 rounded-3xl border-l-8 border-sage bg-bark p-6 text-mint shadow-lg">
        <h2 class="text-2xl font-bold">Welcome to my website!</h2>
        <p class="mt-2">
          Thank you for visiting my first Nuxt application. Feel free to look around
          and get to know me.
        </p>
      </div>

      <NuxtLink
        to="/profile"
        class="mt-8 inline-block rounded-full bg-ink px-8 py-3 font-semibold text-mint transition hover:bg-olive"
      >
        View My Profile →
      </NuxtLink>
    </div>
  </section>
</template>