<template>
  <div class="py-20 bg-gray-50">
    <div class="max-w-7xl mx-auto px-6 lg:px-8">
      <!-- Section header -->
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Achieve AI breakthroughs with the most innovative post-training alignment</h2>
        <p class="text-lg text-gray-600 max-w-3xl mx-auto">
          Accelerate critical generative AI tasks with Aivarium
        </p>
      </div>

      <!-- Two column layout -->
      <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
        <!-- Left column: AI capabilities list -->
        <div class="space-y-12">
          <!-- Capability 1 -->
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Model evaluation</h3>
            <p class="text-gray-600">
              Identify model limitations and build differentiated models that users love with accurate and speedy human-made evaluations.
            </p>
          </div>

          <!-- Capability 2 -->
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Supervised fine-tuning</h3>
            <p class="text-gray-600">
              Refine model performance and fine-tune models for specific tasks and domains with human-generated data curation.
            </p>
          </div>

          <!-- Capability 3 -->
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">RLHF</h3>
            <p class="text-gray-600">
              Align AI behavior with human preferences through preference rankings and evaluations that enable continuous improvement.
            </p>
          </div>

          <!-- Capability 4 -->
          <div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Red teaming</h3>
            <p class="text-gray-600">
              Proactively identify and address vulnerabilities in AI systems before deployment for responsible model development.
            </p>
          </div>
        </div>

        <!-- Right column: Visual diagram -->
        <div class="relative">
          <!-- Hexagonal diagram placeholder -->
          <div class="aspect-square max-w-md mx-auto relative">
            <!-- Center hexagon -->
            <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 w-32 h-32 bg-white shadow-md rounded-xl flex items-center justify-center">
              <div class="text-primary-500 font-bold text-lg">AI Core</div>
            </div>

            <!-- Top hexagon -->
            <div class="absolute top-0 left-1/2 transform -translate-x-1/2 w-28 h-28 bg-orange-100 shadow-sm rounded-xl flex items-center justify-center">
              <div class="text-orange-700 font-medium text-sm">Model Evaluation</div>
            </div>

            <!-- Right hexagon -->
            <div class="absolute top-1/2 right-0 transform -translate-y-1/2 w-28 h-28 bg-blue-100 shadow-sm rounded-xl flex items-center justify-center">
              <div class="text-blue-700 font-medium text-sm">Fine Tuning</div>
            </div>

            <!-- Bottom hexagon -->
            <div class="absolute bottom-0 left-1/2 transform -translate-x-1/2 w-28 h-28 bg-green-100 shadow-sm rounded-xl flex items-center justify-center">
              <div class="text-green-700 font-medium text-sm">RLHF</div>
            </div>

            <!-- Left hexagon -->
            <div class="absolute top-1/2 left-0 transform -translate-y-1/2 w-28 h-28 bg-red-100 shadow-sm rounded-xl flex items-center justify-center">
              <div class="text-red-700 font-medium text-sm">Red Teaming</div>
            </div>

            <!-- Connecting lines (SVG) -->
            <svg class="absolute inset-0 w-full h-full" viewBox="0 0 400 400" fill="none" xmlns="http://www.w3.org/2000/svg">
              <line x1="200" y1="200" x2="200" y2="50" stroke="#E5E7EB" stroke-width="2" />
              <line x1="200" y1="200" x2="350" y2="200" stroke="#E5E7EB" stroke-width="2" />
              <line x1="200" y1="200" x2="200" y2="350" stroke="#E5E7EB" stroke-width="2" />
              <line x1="200" y1="200" x2="50" y2="200" stroke="#E5E7EB" stroke-width="2" />
            </svg>
          </div>
        </div>
      </div>

      <!-- Use cases section -->
      <div class="mt-20">
        <h3 class="text-xl font-semibold text-gray-900 mb-8 text-center">Train your models on our proven GenAI use cases</h3>
        
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
          <!-- Use case 1 -->
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-amber-100 rounded-lg flex items-center justify-center mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-amber-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
              </svg>
            </div>
            <h4 class="text-lg font-medium text-gray-900 mb-1">Complex reasoning</h4>
            <a href="#" class="text-sm text-amber-600 hover:text-amber-700 font-medium">Learn more</a>
          </div>

          <!-- Use case 2 -->
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-blue-100 rounded-lg flex items-center justify-center mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-blue-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z" />
              </svg>
            </div>
            <h4 class="text-lg font-medium text-gray-900 mb-1">Multimodal reasoning</h4>
            <a href="#" class="text-sm text-blue-600 hover:text-blue-700 font-medium">Learn more</a>
          </div>

          <!-- Use case 3 -->
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-yellow-100 rounded-lg flex items-center justify-center mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-yellow-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z" />
              </svg>
            </div>
            <h4 class="text-lg font-medium text-gray-900 mb-1">Image tasks</h4>
            <a href="#" class="text-sm text-yellow-600 hover:text-yellow-700 font-medium">Learn more</a>
          </div>

          <!-- Use case 4 -->
          <div class="bg-white p-4 rounded-lg shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
            <div class="w-12 h-12 bg-green-100 rounded-lg flex items-center justify-center mb-3">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-green-600" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z" />
              </svg>
            </div>
            <h4 class="text-lg font-medium text-gray-900 mb-1">Audio tasks</h4>
            <a href="#" class="text-sm text-green-600 hover:text-green-700 font-medium">Learn more</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
