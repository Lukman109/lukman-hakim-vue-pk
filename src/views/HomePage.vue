<template>
    <div class="home">
      <h1 class="title">Welcome to My Personal Website</h1>
      <div class="image-container">
        <img :src="require('@/assets/walpaper.jpg')" alt="Home Image" class="image" />
      </div>
      <p class="description">Nama Saya Lukman Hakim dan Saya Sedang Belajar Web Developer.</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'HomePage',
  }
  </script>
  
  <style scoped>
  .home {
    text-align: center;
  }
  
  .title {
    font-size: 32px;
    color: #333;
    margin-bottom: 10px;
  }
  
  .image-container {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    margin: 0 auto;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }
  
  .image {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  .description {
    font-size: 18px;
    color: #666;
  }
  </style>
  