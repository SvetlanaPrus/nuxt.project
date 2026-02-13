<template>
  <footer class="footer bg-[#1e2939] text-[#ffffff] px-6 py-6 md:py-16">
    <div
      class="footer-content grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-6 md:gap-12 lg:gap-8 w-full"
    >
      <!-- Block 1 - Company info (order: 3 on mobile, 1 on desktop) -->
      <aside class="space-y-2 order-3 md:order-1">
        <p class="text-sm md:text-base font-semibold">2026 © Svetlana Prus</p>
        <p class="text-xs md:text-sm leading-relaxed text-justify">
          Lorem Ipsum is simply dummy text of the printing and typesetting
          industry. Lorem Ipsum has been the industry's standard dummy text ever
          since the 1500s.
        </p>
        <p class="text-xs md:text-sm leading-relaxed text-justify">
          It is a long established fact that a reader will be distracted by the
          readable content of a page when looking at its layout. The point of
          using Lorem Ipsum is that it has a more-or-less normal distribution of
          letters, as opposed to using 'Content here, content here', making it
          look like readable English.
        </p>
      </aside>

      <!-- Block 2 - Empty spacer (hidden on mobile) -->
      <div class="hidden lg:block order-2"></div>

      <!-- Block 3 - Editor (order: 1 on mobile, 3 on desktop) -->
      <nav class="space-y-2 order-1 md:order-2 lg:order-3">
        <h3 class="text-sm md:text-base font-semibold">
          Developer and editor of this website
        </h3>
        <p class="text-xs md:text-sm">Svetlana Prus</p>
      </nav>

      <!-- Block 4 - Contact (order: 2 on mobile, 4 on desktop) -->
      <nav class="space-y-2 order-2 md:order-3 lg:order-4">
        <div>
          <h3 class="text-sm md:text-base font-semibold">E-post</h3>
          <a
            href="mailto:swetlana.prus@gmail.com"
            class="text-xs md:text-sm link link-hover"
            >swetlana.prus@gmail.com</a
          >
        </div>
        <div>
          <h3 class="text-sm md:text-base font-semibold">Mobile phone</h3>
          <a href="tel:+4797514226" class="text-xs md:text-sm link link-hover"
            >97 51 4226</a
          >
        </div>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>
