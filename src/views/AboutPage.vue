<template>
    <div class="about">
      <div class="profile">
        <div class="image-container">
          <img :src="require('@/assets/pribadi.jpg')" alt="Profile Picture" class="image" />
        </div>
        <div class="profile-info">
          <h1 class="title">Teantang Saya</h1>
          <p class="description">Web Developer</p>
        </div>
      </div>
      <div class="personal-info">
        <h2 class="subtitle">Informasi Pribadi Saya</h2>
        <div class="info-box">
          <div class="info-item">
            <strong>Nama:</strong>
            <span>Lukman Hakim</span>
          </div>
          <div class="info-item">
            <strong>Umur:</strong>
            <span>23</span>
          </div>
          <div class="info-item">
            <strong>Alamat:</strong>
            <span>Bangkalan, Madura, Jawa Timur</span>
          </div>
          <div class="info-item">
            <strong>Hobi:</strong>
            <span>Baca Buku, Nonton Film, Belajar Web</span>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'AboutPage',
  }
  </script>
  
  <style scoped>
  .about {
    text-align: center;
    padding: 20px;
  }
  
  .profile {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
  }
  
  .image-container {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    overflow: hidden;
    margin-right: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }
  
  .image {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  .profile-info {
    text-align: left;
  }
  
  .title {
    font-size: 28px;
    color: #333;
    margin-bottom: 10px;
  }
  
  .description {
    font-size: 18px;
    color: #666;
  }
  
  .personal-info {
    text-align: left;
  }
  
  .subtitle {
    font-size: 20px;
    color: #333;
    margin-bottom: 10px;
  }
  
  .info-box {
    background-color: #f5f5f5;
    padding: 10px;
    border-radius: 4px;
  }
  
  .info-item {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
  }
  
  .info-item strong {
    width: 100px;
    font-weight: bold;
  }
  
  .info-item span {
    font-size: 16px;
    color: #666;
    margin-left: 10px;
  }
  </style>  