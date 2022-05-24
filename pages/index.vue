<template>
  <div
    class="relative overflow-hidden pt-[120px] md:pt-[130px] lg:pt-[160px] min-h-screen min-w-screen bg-indigo-700"
  >
    <div class="container">
      <div class="-mx-4 flex flex-wrap items-center">
        <div class="w-full px-4">
          <div
            class="hero-content wow fadeInUp mx-auto max-w-[780px] text-center"
          >
            <h1
              class="mb-8 text-3xl font-bold leading-snug text-white sm:text-4xl sm:leading-snug md:text-[45px] md:leading-snug"
            >
              Penerimaan Peserta Didik Baru Online
            </h1>
            <p
              class="mx-auto mb-10 max-w-[600px] text-base text-[#e4e4e4] sm:text-lg sm:leading-relaxed md:text-xl md:leading-relaxed"
            >
              <span class="font-bold"
                >Official PPDB ONLINE &mdash; SMKN 4 BEKASI</span
              >
              <br />
              <span class="font-lighter">~ Sukseskan PPDB Online 2022 ~</span>
            </p>
            <ul class="mb-10 flex flex-wrap items-center justify-center">
              <li>
                <a
                  href="#"
                  class="inline-flex items-center justify-center rounded-lg bg-white py-4 px-6 text-center text-base font-medium text-dark transition duration-300 ease-in-out hover:text-primary hover:shadow-lg sm:px-10"
                >
                  Info Lebih Lanjut
                </a>
              </li>
            </ul>
            <p class="text-white mt-25">
              &copy; <a href="https://abubakarr_ra">Muhammad Aditya Nurdin</a>
            </p>
          </div>
        </div>
      </div>
      <div class="absolute bottom-0 -left-9 z-[-1]">
        <CircleItem />
      </div>
      <div class="absolute -top-6 -right-6 z-[-1]">
        <CircleItem />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
