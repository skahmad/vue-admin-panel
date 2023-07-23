<template>
  <div class="h-100 d-flex align-center justify-space-between">
    <!-- Footer: left content -->
    <span class="d-flex align-center">
      &copy;
      {{ new Date().getFullYear() }}
      
      By <a
        href="https://creatortestai.com"
        target="_blank"
        rel="noopener noreferrer"
        class="text-primary ms-1"
      > Creator</a>
    </span>
    
    <!-- Footer: right content -->
    <span class="d-md-flex gap-x-4 text-primary d-none">
      <a
        href="https://creatortestai.com/portfolio"
        target="noopener noreferrer"
      >Portfolio</a>
      <a
        href="https://creatortestai.com/docs"
        target="noopener noreferrer"
      >Documentation</a>
    </span>
  </div>
</template>
