<script>
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import DesignManagement from '$lib/components/DesignManagement.svelte';
  import BOMSection from '$lib/components/BOMSection.svelte';
  import DesignReviews from '$lib/components/DesignReviews.svelte';
  import TeamSection from '$lib/components/TeamSection.svelte';
  import VendorSection from '$lib/components/VendorSection.svelte';
  import FooterSection from '$lib/components/FooterSection.svelte';
</script>

<main class="font-sans antialiased text-gray-900 bg-white selection:bg-primary-100 selection:text-primary-900">
  <Navbar />
  <Hero />
  <DesignManagement />
  <BOMSection />
  <DesignReviews />
  <TeamSection />
  <VendorSection />
  <FooterSection />
</main>

