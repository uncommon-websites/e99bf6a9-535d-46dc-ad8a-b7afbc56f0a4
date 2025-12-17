<script>
  const features = [
    "Webflow development", "CMS architecture", "Custom interactions", "Performance optimization", "Responsive design", "SEO optimization",
    "Component libraries", "Design systems", "Brand consistency", "Conversion optimization", "Analytics integration", "A/B testing setup",
    "Content strategy", "User experience design", "Mobile-first approach", "Accessibility compliance", "Page speed optimization", "Custom code integration",
    "Third-party integrations", "Form automation", "E-commerce solutions", "Membership sites", "Blog systems", "Portfolio showcases",
    "Landing page optimization", "Marketing automation", "Lead generation", "Sales funnel design", "Growth strategy", "Technical consulting",
    "Team training", "CMS documentation", "Ongoing support", "Website maintenance", "Security updates", "Backup solutions",
    "Migration services", "Platform transitions", "Legacy system updates", "API integrations", "Custom functionality", "Dynamic content",
    "Multi-language support", "Localization", "Global CDN setup", "Performance monitoring", "Uptime tracking", "Error monitoring",
    "Version control", "Staging environments", "Quality assurance", "Cross-browser testing", "Device testing", "Load testing",
    "Strategic planning", "Growth consulting", "Competitive analysis", "User research", "Conversion audits", "Technical audits",
    "Brand development", "Visual design", "UI/UX design", "Prototyping", "Wireframing", "Design reviews"
  ];
</script>

<section class="pt-24 pb-12 bg-white text-center overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-6">
    <h2 class="text-5xl font-bold mb-16 tracking-tight text-gray-900 leading-tight">
      Everything You Need<br>to Scale Your Website
    </h2>

    <div class="flex flex-wrap justify-center gap-x-4 gap-y-3 text-xs text-gray-400 max-w-6xl mx-auto mb-32 opacity-70">
       {#each features as feature}
         <span class="hover:text-gray-900 transition-colors cursor-default">{feature}</span>
         <span class="text-gray-300">•</span>
       {/each}
    </div>

    <!-- CTA Section -->
    <div class="max-w-2xl mx-auto mb-24" id="start">
       <!-- Logo Icon -->
       <div class="w-32 h-40 mx-auto mb-8 flex items-center justify-center">
          <svg width="90" height="115" viewBox="0 0 90 115" fill="none" xmlns="http://www.w3.org/2000/svg">
             <path fill-rule="evenodd" clip-rule="evenodd" d="M31.8701 9.95388L15.3109 19.4791L31.8819 29.0064L48.446 19.4812L31.8701 9.95388ZM53.2588 27.7795L36.6927 37.3058L36.6911 56.3603L53.2588 46.8319V27.7795ZM58.0696 55.1313L41.5014 64.66L58.072 74.187L74.6383 64.6605L58.0696 55.1313ZM79.4486 72.9601L62.883 82.4862V101.538L79.4486 92.0122V72.9601ZM53.2614 101.539V82.4864L36.6903 72.9591V92.012L53.2614 101.539ZM27.0694 56.3613L10.5003 46.8319V27.7788L27.0711 37.3058L27.0694 56.3613ZM27.0687 67.4269L4.48643 54.4394C2.25391 53.1554 0.878662 50.7828 0.878662 48.215V19.4801C0.878662 17.7684 1.79538 16.1867 3.28356 15.3307L28.2608 0.963381C30.4933 -0.320696 33.2439 -0.321154 35.4766 0.962171L60.474 15.3299C61.963 16.1857 62.8804 17.7679 62.8804 19.4801V46.8319L86.665 60.5111C88.1535 61.3671 89.0702 62.9489 89.0702 64.6607V93.3956C89.0702 95.9635 87.6948 98.3361 85.4621 99.62L60.4776 113.988C58.9894 114.843 57.1558 114.843 55.6673 113.988L30.6773 99.6202C28.4444 98.3365 27.0687 95.9635 27.0687 93.3954V67.4269Z" fill="black"/>
          </svg>
       </div>
       
       <p class="text-lg text-gray-600 mb-8 leading-relaxed">
          Ready to transform your website into a strategic growth engine? Let's build something exceptional together.
       </p>
       <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm">
          Start Your Project
       </button>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-gray-950 text-white py-12 border-t border-gray-900" id="contact">
     <div class="max-w-[1200px] mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
        <div class="flex items-center gap-2">
           <div class="w-6 h-8 flex items-center justify-center">
              <svg width="20" height="26" viewBox="0 0 90 115" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd" d="M31.8701 9.95388L15.3109 19.4791L31.8819 29.0064L48.446 19.4812L31.8701 9.95388ZM53.2588 27.7795L36.6927 37.3058L36.6911 56.3603L53.2588 46.8319V27.7795ZM58.0696 55.1313L41.5014 64.66L58.072 74.187L74.6383 64.6605L58.0696 55.1313ZM79.4486 72.9601L62.883 82.4862V101.538L79.4486 92.0122V72.9601ZM53.2614 101.539V82.4864L36.6903 72.9591V92.012L53.2614 101.539ZM27.0694 56.3613L10.5003 46.8319V27.7788L27.0711 37.3058L27.0694 56.3613ZM27.0687 67.4269L4.48643 54.4394C2.25391 53.1554 0.878662 50.7828 0.878662 48.215V19.4801C0.878662 17.7684 1.79538 16.1867 3.28356 15.3307L28.2608 0.963381C30.4933 -0.320696 33.2439 -0.321154 35.4766 0.962171L60.474 15.3299C61.963 16.1857 62.8804 17.7679 62.8804 19.4801V46.8319L86.665 60.5111C88.1535 61.3671 89.0702 62.9489 89.0702 64.6607V93.3956C89.0702 95.9635 87.6948 98.3361 85.4621 99.62L60.4776 113.988C58.9894 114.843 57.1558 114.843 55.6673 113.988L30.6773 99.6202C28.4444 98.3365 27.0687 95.9635 27.0687 93.3954V67.4269Z" fill="white"/>
              </svg>
           </div>
           <span class="font-bold text-sm">BrightSite © 2025</span>
           <span class="text-gray-500 text-xs ml-2">Scalable Webflow Systems</span>
        </div>
        
        <div class="flex items-center gap-6 text-xs text-gray-400">
           <a href="#start" class="hover:text-white">Start a Project</a>
           <a href="#contact" class="hover:text-white">Contact</a>
           <a href="#" class="hover:text-white">Case Studies</a>
           <a href="#" class="hover:text-white">Privacy</a>
        </div>
     </div>
  </footer>
</section>
