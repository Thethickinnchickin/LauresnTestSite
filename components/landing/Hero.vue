<template>
  <main class="grid lg:grid-cols-2 place-items-center pt-16 pb-8 md:pt-8 ">
    <div class="p-24 md:order-1 hidden md:block">
      <img
        class="rounded-full transition-transform transform hover:scale-125"
        src="~/assets/img/portrait.jpg"
        alt="Starship starts the engine"
        loading="eager"
        format="avif"
        width="512"
        height="512"
      />
    </div>

    <div>
      <h1 class="text-5xl lg:text-6xl xl:text-7xl font-bold lg:tracking-tight italiana-regular">
        Lauren's Marketing
      </h1>
      <p class="text-lg mt-4 text-slate-600 max-w-xl italiana-bold">
        Something about yourself or the business here a small passage
        <wbr /> This is more text that is after the text break
      </p>
      <div class="mt-6 flex flex-col sm:flex-row gap-3">
        <LandingLink
          href="http://localhost:3000/about"
          target="_blank"
          rel="noopener"
          >About</LandingLink
        >
        <LandingLink
          size="lg"
          styleName="outline"
          rel="noopener"
          href="https://github.com/Gr33nW33n/nuxtship-template"
          target="_blank"
          >View Repo</LandingLink
        >
      </div>
    </div>
  </main>
</template>
