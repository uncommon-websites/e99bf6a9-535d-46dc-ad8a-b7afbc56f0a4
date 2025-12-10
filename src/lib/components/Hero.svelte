<script>
</script>

<section class="pt-20 pb-16 text-center max-w-[1200px] mx-auto px-6">
  <h1 class="text-6xl font-bold tracking-tight text-gray-900 mb-6 leading-[1.1]">
    Superpowers for<br>Hardware Teams
  </h1>
  <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto leading-relaxed">
    Config brings together engineering, operations, and manufacturing to make shipping high-quality hardware easier at scale.
  </p>
  <button class="bg-[#2563EB] text-white px-6 py-3 rounded-lg hover:bg-blue-700 transition-colors font-semibold text-sm mb-20 cursor-pointer">
    Get started
  </button>

  <!-- Exploded View Image Placeholder -->
  <div class="relative w-full aspect-[2/1] bg-gray-50 rounded-xl overflow-hidden flex items-center justify-center border border-gray-100">
    <!-- Abstract representation of exploded view -->
    <div class="relative w-[600px] h-[400px] perspective-[1000px]">
       <!-- Bottom Layer -->
       <div class="absolute top-[60%] left-[50%] transform -translate-x-1/2 -translate-y-1/2 w-64 h-64 bg-gray-200 rounded-2xl rotate-x-[60deg] rotate-z-[45deg] shadow-xl border border-gray-300"></div>
       
       <!-- Middle Layer (PCB) -->
       <div class="absolute top-[50%] left-[50%] transform -translate-x-1/2 -translate-y-1/2 w-56 h-56 bg-green-800/80 rounded-xl rotate-x-[60deg] rotate-z-[45deg] shadow-lg border border-green-700 backdrop-blur-sm flex items-center justify-center">
          <div class="w-full h-full grid grid-cols-4 gap-2 p-4 opacity-50">
             <div class="bg-yellow-400/50 rounded-sm col-span-2"></div>
             <div class="bg-gray-300/50 rounded-full"></div>
             <div class="bg-black/30 rounded-sm"></div>
          </div>
       </div>
       
       <!-- Top Layer (Casing) -->
       <div class="absolute top-[40%] left-[50%] transform -translate-x-1/2 -translate-y-1/2 w-64 h-64 bg-white/90 rounded-2xl rotate-x-[60deg] rotate-z-[45deg] shadow-2xl border border-gray-200 backdrop-blur-sm"></div>
       
       <!-- Floating Elements -->
       <div class="absolute top-[30%] left-[60%] w-8 h-8 bg-gray-400 rounded-full shadow-lg animate-bounce duration-[3000ms]"></div>
       <div class="absolute top-[35%] left-[40%] w-4 h-12 bg-gray-300 rounded-full shadow-lg rotate-45"></div>
       <div class="absolute top-[25%] left-[55%] w-2 h-20 bg-gray-300 rounded-full shadow-lg rotate-12"></div>
    </div>
    
    <div class="absolute inset-0 bg-gradient-to-t from-white via-transparent to-transparent pointer-events-none"></div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mt-20 text-left">
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">01</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Mechanical</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Drawings and designs managed in a way that works the way you think, with automatically generated BOMs. Compatible with NX and SolidWorks.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">02</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Electrical</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Manage your whole team's schematics and layouts with ease, also with automatically generated BOMs. Compatible with Altium.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">03</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Firmware</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Complete your BOM with firmware releases. Revision build assets manually and automatically with CI/CD Release integration.
      </p>
    </div>
  </div>
</section>
