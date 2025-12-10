<script>
  const features = [
    "Stricted permissions", "Vendor access to bill of materials", "Vendor management", "Deletions of data prevented, write-only", "Every commit preserved", "Team permissions",
    "Assembly reparenting within a bill of materials", "Generate a bill of materials from a design", "Design releases", "Clear to build management", "Vendor management", "Easily load a bill of materials from a design",
    "Detailed bill of materials item history", "Revision tracking for all parts", "Alternates tracking", "Live redlined bill of materials changes", "3D CAD viewers", "Mechanical drawings",
    "Detailed bill of materials item history", "Revision tracking for all parts", "Alternates tracking", "Live redlined bill of materials changes", "Firmware versioning",
    "Electrical bills of materials", "Electrical layouts", "Electrical schematics", "Full bill of materials edit history", "Mechanical bills of materials", "Project access for members",
    "Vendor management", "Vendor access to bill of materials", "Deletions of data prevented, write-only", "Team permissions", "Generate a bill of materials from a design",
    "Design releases", "Vendor restricted permissions", "Clear to build management", "Vendor management", "Easily load a bill of materials from a design", "Detailed bill of materials item history",
    "Part number management", "Procurement tracking", "Clear to build management", "Design releases", "Create custom columns for a bill of materials of filtering",
    "Mechanical drawings", "3D CAD viewers", "Revision tracking for all parts", "Alternates tracking", "Create custom columns for a bill of materials of filtering", "Download attachments from bill of materials",
    "Create custom columns for a bill of materials", "Full bill of materials edit history", "Live redlined bill of materials changes", "Electrical schematics",
    "Firmware versioning", "Electrical layouts", "Full bill of materials edit history", "Live redlined bill of materials changes"
  ];
</script>

<section class="pt-24 pb-12 bg-white text-center overflow-hidden">
  <div class="max-w-[1400px] mx-auto px-6">
    <h2 class="text-5xl font-bold mb-16 tracking-tight text-gray-900 leading-tight">
      ...And Much,<br>Much More.
    </h2>

    <div class="flex flex-wrap justify-center gap-x-4 gap-y-3 text-xs text-gray-400 max-w-6xl mx-auto mb-32 opacity-70">
       {#each features as feature}
         <span class="hover:text-gray-900 transition-colors cursor-default">{feature}</span>
         <span class="text-gray-300">•</span>
       {/each}
    </div>

    <!-- CTA Section -->
    <div class="max-w-2xl mx-auto mb-24">
       <!-- Device Image Placeholder -->
       <div class="w-64 h-64 mx-auto mb-8 bg-gray-100 rounded-3xl shadow-2xl flex items-center justify-center relative border-4 border-gray-200">
          <div class="absolute inset-2 bg-gray-800 rounded-2xl flex flex-col items-center justify-center overflow-hidden">
             <!-- Screen -->
             <div class="w-full h-1/2 bg-black flex items-center justify-center border-b border-gray-700">
                <span class="text-4xl">✌️</span>
             </div>
             <!-- Keys -->
             <div class="w-full h-1/2 grid grid-cols-3 gap-1 p-2 bg-gray-700">
                <div class="bg-orange-500 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
                <div class="bg-gray-600 rounded-full shadow-inner"></div>
             </div>
          </div>
       </div>
       
       <p class="text-lg text-gray-600 mb-8 leading-relaxed">
          Do you want to revolutionize how your team collaborates and builds hardware together? You need Config.
       </p>
       <button class="bg-[#2563EB] text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition-colors font-semibold text-sm">
          Get started
       </button>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-[#0B0F19] text-white py-12 border-t border-gray-800">
     <div class="max-w-[1200px] mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6">
        <div class="flex items-center gap-2">
           <div class="w-5 h-5 bg-white text-black rounded flex items-center justify-center">
              <svg width="12" height="12" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M12 2L2 7V17L12 22L22 17V7L12 2Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
                  <path d="M12 8L16 10V14L12 16L8 14V10L12 8Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
              </svg>
           </div>
           <span class="font-bold text-sm">Config @ 2025</span>
           <span class="text-gray-500 text-xs ml-2">Designed in the United States</span>
        </div>
        
        <div class="flex items-center gap-6 text-xs text-gray-400">
           <a href="#" class="hover:text-white">Sign in</a>
           <a href="#" class="hover:text-white">Get started</a>
           <a href="#" class="hover:text-white">Terms</a>
           <a href="#" class="hover:text-white">Privacy</a>
           <a href="#" class="hover:text-white">Twitter</a>
        </div>
     </div>
  </footer>
</section>
