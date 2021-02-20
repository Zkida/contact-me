<template>
  <div class="container flex flex-col mx-auto min-h-screen">
    <Header />
    <main class="flex flex-grow items-center justify-center flex-col">
      <h1 class="text-2xl font-bold">Hi, I'm Joseph Ruano 🤘</h1>
      <h2 class="mt-8 md:mt-14 text-center text-4xl md:text-6xl font-bold">
        I <span class="highlighted">build</span> custom WordPress <br />themes
        and plugins
      </h2>
      <div
        class="w-full px-4 md:w-3/5 text-center mt-8 md:mt-12 text-xl md:text-2xl"
      >
        <p>A <span class="font-bold">Web Developer</span> in WI.</p>
        <p>
          <span class="font-bold">I'm skilled in:</span> building and
          customizing websites, creating custom plugins, website maintenance and
          support, website optimization, and fixing crashed and broken websites.
        </p>
        <div class="mt-12">
          <a
            class="px-6 py-4 bg-black border border-black hover:bg-white hover:text-black text-white text-base rounded-full"
            href="mailto:hi@jruano.dev"
            >CONTACT ME</a
          >
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.highlighted {
  position: relative;
  z-index: 0;
}

.highlighted:before {
  content: '';
  width: 100%;
  height: 12px;
  bottom: 6px;
  position: absolute;
  background: #75e6da;
  z-index: -1;
}
</style>
