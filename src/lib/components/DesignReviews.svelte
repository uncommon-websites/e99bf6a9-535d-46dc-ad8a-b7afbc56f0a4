<script>
  let activeTab = 'Discovery';
  const tabs = ['Discovery', 'Design', 'Development', 'Launch'];
</script>

<section class="py-24 bg-white text-center">
  <div class="max-w-[1200px] mx-auto px-6">
    <h2 class="text-5xl font-bold mb-6 tracking-tight text-gray-900">
      Collaborative Design<br>Process
    </h2>
    
    <!-- Tabs -->
    <div class="flex justify-center mb-8">
      <div class="bg-gray-100 p-1 rounded-lg inline-flex">
        {#each tabs as tab}
          <button 
            class="px-4 py-1.5 text-sm font-medium rounded-md transition-all {activeTab === tab ? 'bg-white text-gray-900 shadow-sm' : 'text-gray-500 hover:text-gray-700'}"
            on:click={() => activeTab = tab}
          >
            {tab}
          </button>
        {/each}
      </div>
    </div>

    <p class="text-lg text-gray-600 mb-16 max-w-2xl mx-auto leading-relaxed">
      Stay in the loop with real-time collaboration. Our transparent process keeps you informed at every stage, from concept to launch.
    </p>

    <!-- UI Mockup -->
    <div class="bg-white rounded-xl shadow-2xl overflow-hidden border border-gray-200 text-left h-[700px] flex flex-col">
      <!-- Toolbar -->
      <div class="h-12 border-b border-gray-200 flex items-center justify-between px-4 bg-white">
        <div class="flex items-center gap-4">
           <span class="text-xs font-mono text-gray-500">318-2214</span>
           <span class="text-gray-300">/</span>
           <span class="text-xs font-bold text-gray-900 flex items-center gap-2">
             <span class="w-2 h-2 rounded-full bg-blue-500"></span>
             Enclosure - Revision 4
           </span>
        </div>
        
        <div class="flex items-center gap-6">
           <div class="flex items-center gap-4 text-xs font-medium text-gray-500">
              <button class="hover:text-gray-900 flex items-center gap-1"><span>👁️</span> Preview</button>
              <button class="text-red-500 flex items-center gap-1 border-b-2 border-red-500 pb-3 mt-3"><span>💬</span> Comments <span class="bg-red-100 text-red-600 px-1 rounded text-[10px]">3</span></button>
              <button class="hover:text-gray-900 flex items-center gap-1"><span>clock</span> History</button>
           </div>
        </div>

        <div class="flex items-center gap-2">
           <button class="text-xs border border-gray-200 rounded px-2 py-1 flex items-center gap-1 text-gray-600">Views ▼</button>
           <button class="text-xs border border-gray-200 rounded px-2 py-1 flex items-center gap-1 text-gray-600">100% Zoom ▼</button>
        </div>
      </div>

      <div class="flex flex-1 overflow-hidden">
        <!-- Left Sidebar (Tree) -->
        <div class="w-64 bg-gray-50 border-r border-gray-200 flex flex-col text-xs">
           <div class="p-2 border-b border-gray-200 flex items-center justify-between">
              <span class="font-bold text-gray-700">ASSEMBLY</span>
              <div class="flex gap-1 text-gray-400">
                 <span>🔍</span>
                 <span>⚙️</span>
              </div>
           </div>
           <div class="flex-1 overflow-y-auto p-2 space-y-1">
              <div class="flex items-center gap-2 text-gray-600 pl-2">
                 <span>▼</span> <span>Reference Stand</span>
              </div>
              <div class="flex items-center gap-2 text-gray-600 pl-2">
                 <span>▼</span> <span>Reference Background</span>
              </div>
              <div class="flex items-center gap-2 font-medium text-gray-900 pl-2 bg-blue-50 rounded py-1">
                 <span>▼</span> <span>Enclosure Assembly</span> <span class="ml-auto text-[10px] bg-gray-200 px-1 rounded text-gray-600">R5</span>
              </div>
              <div class="pl-6 space-y-1">
                 <div class="flex items-center gap-2 text-gray-700">
                    <span>👁️</span> <span>Bottom Enclosure</span> <span class="ml-auto text-[10px] bg-gray-200 px-1 rounded text-gray-600">R4</span>
                 </div>
                 <div class="flex items-center gap-2 text-gray-700">
                    <span>👁️</span> <span>Top Enclosure</span> <span class="ml-auto text-[10px] bg-gray-200 px-1 rounded text-gray-600">R9</span>
                 </div>
                 <div class="flex items-center gap-2 text-gray-500">
                    <span>👁️</span> <span>92703A454-18_Stainless_st...</span>
                 </div>
                 <div class="flex items-center gap-2 text-gray-500">
                    <span>👁️</span> <span>92703A454-18_Stainless_st...</span>
                 </div>
                 <div class="flex items-center gap-2 text-gray-500">
                    <span>👁️</span> <span>92703A454-18_Stainless_st...</span>
                 </div>
              </div>
              <div class="flex items-center gap-2 text-gray-600 pl-2 pt-2">
                 <span>▶</span> <span>Keyboard Assembly</span> <span class="ml-auto text-[10px] bg-gray-200 px-1 rounded text-gray-600">R2</span>
              </div>
           </div>
        </div>

        <!-- Center (3D View) -->
        <div class="flex-1 bg-gray-100 relative flex items-center justify-center overflow-hidden">
           <!-- Placeholder for 3D model -->
           <div class="w-[400px] h-[400px] bg-gray-300 rounded-xl shadow-inner relative transform rotate-12">
              <div class="absolute inset-0 bg-gradient-to-br from-gray-200 to-gray-400 rounded-xl border border-gray-400"></div>
              <!-- Simulated details -->
              <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-20 h-20 border-4 border-gray-500/20 rounded-full"></div>
              <div class="absolute top-10 left-10 w-4 h-4 rounded-full bg-gray-500/30 shadow-inner"></div>
              <div class="absolute top-10 right-10 w-4 h-4 rounded-full bg-gray-500/30 shadow-inner"></div>
              <div class="absolute bottom-10 left-10 w-4 h-4 rounded-full bg-gray-500/30 shadow-inner"></div>
              <div class="absolute bottom-10 right-10 w-4 h-4 rounded-full bg-gray-500/30 shadow-inner"></div>
              
              <!-- Annotation Pin -->
              <div class="absolute top-1/3 left-1/3 w-8 h-8 bg-red-500 rounded-full border-2 border-white shadow-lg flex items-center justify-center text-white font-bold text-xs cursor-pointer z-10 hover:scale-110 transition-transform">
                 1
              </div>
           </div>
           
           <!-- Overlay controls -->
           <div class="absolute bottom-4 left-1/2 transform -translate-x-1/2 bg-white rounded-full shadow-lg px-4 py-2 flex gap-4 text-gray-500">
              <button>↺</button>
              <button>↔</button>
              <button>🔍</button>
           </div>
           
           <!-- User Avatars overlay -->
           <div class="absolute top-4 left-1/2 transform -translate-x-1/2 bg-white/80 backdrop-blur rounded-full px-3 py-1 flex items-center gap-2 text-xs shadow-sm">
              <div class="flex -space-x-2">
                 <div class="w-6 h-6 rounded-full bg-blue-500 border-2 border-white"></div>
                 <div class="w-6 h-6 rounded-full bg-green-500 border-2 border-white"></div>
                 <div class="w-6 h-6 rounded-full bg-yellow-500 border-2 border-white"></div>
              </div>
              <span class="text-gray-600">3 currently viewing</span>
           </div>
        </div>

        <!-- Right Sidebar (Comments) -->
        <div class="w-80 bg-white border-l border-gray-200 flex flex-col">
           <div class="p-4 border-b border-gray-100">
              <div class="flex items-center gap-2 mb-3">
                 <div class="w-6 h-6 rounded-full bg-gray-200"></div>
                 <input type="text" placeholder="Add a comment..." class="flex-1 bg-transparent text-sm focus:outline-none">
              </div>
              <div class="flex justify-between items-center">
                 <div class="flex gap-2 text-gray-400">
                    <button>📎</button>
                    <button>@</button>
                    <button>😊</button>
                 </div>
                 <button class="bg-blue-500 text-white text-xs px-3 py-1.5 rounded font-medium">Post</button>
              </div>
           </div>
           
           <div class="flex-1 overflow-y-auto p-4 space-y-6">
              <div class="flex items-center justify-between text-[10px] font-bold text-gray-400 uppercase tracking-wider mb-2">
                 <span>All Comments</span>
                 <div class="flex gap-2">
                    <button>Filter</button>
                    <button>Sort</button>
                 </div>
              </div>

              <!-- Comment 1 -->
              <div class="flex gap-3">
                 <div class="w-8 h-8 rounded-full bg-blue-100 flex-shrink-0"></div>
                 <div>
                    <div class="flex items-baseline gap-2 mb-1">
                       <span class="text-xs font-bold text-gray-900">Cody Stronghold</span>
                       <span class="text-[10px] text-gray-400">6h</span>
                    </div>
                    <div class="text-xs text-gray-600 bg-gray-50 p-2 rounded-lg border border-gray-100 mb-1">
                       <span class="text-blue-500">@cody</span> Updated enclosure walls to 6mm, increased fillet radius to fit
                    </div>
                    <div class="flex items-center gap-2 mt-1">
                       <div class="w-4 h-4 rounded-full bg-gray-200"></div>
                       <span class="text-[10px] text-gray-400">Add a reply...</span>
                    </div>
                 </div>
              </div>

              <!-- Comment 2 -->
              <div class="flex gap-3 relative">
                 <div class="absolute -left-2 top-2 w-1 h-12 bg-gray-100 rounded-full"></div> <!-- Thread line -->
                 <div class="w-8 h-8 rounded-full bg-red-100 flex-shrink-0 z-10"></div>
                 <div>
                    <div class="flex items-baseline gap-2 mb-1">
                       <span class="text-xs font-bold text-gray-900">Cody Stronghold</span>
                       <span class="text-[10px] text-gray-400">6h</span>
                    </div>
                    <div class="text-xs text-gray-600 mb-1">
                       Can we increase the enclosure walls to 6mm thickness?
                    </div>
                    <div class="flex items-center gap-2 mt-1">
                       <div class="w-4 h-4 rounded-full bg-gray-200"></div>
                       <span class="text-[10px] text-gray-400">Add a reply...</span>
                    </div>
                 </div>
              </div>
           </div>
        </div>
      </div>
    </div>
  </div>
</section>
