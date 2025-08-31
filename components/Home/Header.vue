<script setup lang="ts">
</script>
<template>
  <div class="home-header">
    <div class="image-container">
      <NuxtImg src="/images/logo3.png" class="logo" />
    </div>
    <div class="text-container">
      <p class="text">
        Hello, I'm <span class="name">Mohab</span> Iam a
        <span class="role">Frontend Developer</span>
      </p>
      <p class="description">
        As a passionate Front-End Developer, I specialize in creating dynamic
        and responsive web applications using React.js, HTML, and CSS. With a
        keen eye for design and a commitment to user experience
      </p>
      <button>
          <a href="../../public/pdfs/MyCv.pdf" class="downlaod-cv" download>
            <span>
                Download Cv
            </span>
            <IconsDownloadIcon class="download-icon" />
        </a>
      </button>

    </div>

  </div>
</template>

<style scoped lang="scss">
</style>