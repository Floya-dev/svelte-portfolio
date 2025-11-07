<script>
  import favicon from "$lib/assets/cat.svg";
  import "../app.css";
  import Header from "../components/Header.svelte";
  import Footer from "../components/Footer.svelte";
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
  <title>Floya-self</title>
</svelte:head>

<div
  class="relative flex flex-col max-w-[1400px] mx-auto w-full text-sm sm:text-base min-h-screen"
>
  <div>
    <!-- svelte-ignore a11y_consider_explicit_label -->
    <button>
      <i class="fa-solid fa-arrow-up"></i>
    </button>
  </div>
  <Header />
  <slot />
  <Footer />
</div>
