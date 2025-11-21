---
title: "Contact"
---

<div class="text-center space-y-8">

<p class="text-xl text-gray-700 leading-relaxed max-w-2xl mx-auto">
Let's discuss your audiences, your data, and how a private AI research system could expand your insight toolkit.
</p>

<div class="pt-8 flex items-center justify-center gap-3">
<span class="px-8 py-4 bg-gray-900 text-white rounded-lg text-lg font-medium">
contact@elver.tech
</span>
<button id="copyBtn" onclick="copyEmail()" class="p-4 bg-gray-100 hover:bg-gray-200 rounded-lg transition-all duration-200" title="Copy email">
<svg id="copyIcon" class="w-5 h-5 text-gray-700 transition-opacity" fill="none" stroke="currentColor" viewBox="0 0 24 24">
<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 16H6a2 2 0 01-2-2V6a2 2 0 012-2h8a2 2 0 012 2v2m-6 12h8a2 2 0 002-2v-8a2 2 0 00-2-2h-8a2 2 0 00-2 2v8a2 2 0 002 2z"></path>
</svg>
<svg id="checkIcon" class="w-5 h-5 text-green-600 transition-opacity hidden" fill="none" stroke="currentColor" viewBox="0 0 24 24">
<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path>
</svg>
</button>
</div>

<script>
function copyEmail() {
  navigator.clipboard.writeText('contact@elver.tech').then(() => {
    const btn = document.getElementById('copyBtn');
    const copyIcon = document.getElementById('copyIcon');
    const checkIcon = document.getElementById('checkIcon');

    copyIcon.classList.add('hidden');
    checkIcon.classList.remove('hidden');
    btn.classList.add('bg-green-100');
    btn.classList.remove('bg-gray-100');

    setTimeout(() => {
      copyIcon.classList.remove('hidden');
      checkIcon.classList.add('hidden');
      btn.classList.remove('bg-green-100');
      btn.classList.add('bg-gray-100');
    }, 1500);
  });
}
</script>

<p class="text-gray-600 pt-8">
We help research professionals build internal systems that are bespoke, secure, and enterprise-grade.
</p>

</div>
