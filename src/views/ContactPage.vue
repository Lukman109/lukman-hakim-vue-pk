<template>
    <div class="contact">
      <h1 class="title">Contact Me</h1>
      <p class="description">Anda dapat menghubungi saya di::</p>
      <ul>
        <li>Email: lukman5436@gmail.com</li>
        <li>Phone: 081232423133</li>
        <li>Address: Bangkalan</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'ContactPage',
  }
  </script>
  
  <style scoped>
  .contact {
    text-align: center;
  }
  
  .title {
    font-size: 28px;
    color: #333;
    margin-bottom: 10px;
  }
  
  .description {
    font-size: 16px;
    color: #666;
    margin-bottom: 20px;
  }
  
  ul {
    list-style: none;
    padding: 0;
    margin-bottom: 20px;
  }
  
  li {
    font-size: 16px;
    color: #666;
    margin-bottom: 5px;
  }
  </style>  