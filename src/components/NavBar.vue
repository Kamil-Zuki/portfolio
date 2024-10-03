<template>
      <a 
      href="#" class="logo"
        :class="{ active: activeLink === '' }" 
        @click="setActiveLink('Home')"
      ><img src="/src/imgs/Logo.svg"></a>
    <nav>
      <a 
        href="#" 
        :class="{ active: activeLink === 'Home' }" 
        @click="setActiveLink('Home')"
      >Home</a>
      
      <a 
        href="#services" 
        :class="{ active: activeLink === 'Services' }" 
        @click="setActiveLink('Services')"
      >Services</a>
      
      <a 
        href="#skills" 
        :class="{ active: activeLink === 'Skills' }" 
        @click="setActiveLink('Skills')"
      >Skills</a>
      
      <a 
        href="#education" 
        :class="{ active: activeLink === 'Education' }" 
        @click="setActiveLink('Education')"
      >Education</a>
      
      <a 
        href="#experience" 
        :class="{ active: activeLink === 'Experience' }" 
        @click="setActiveLink('Experience')"
      >Experience</a>
    </nav>
  </template>
  
  <script setup>
  import { ref } from 'vue'
  
  // Step 1: Create a reactive state to track the active link
  const activeLink = ref('Home') // Default active link
  
  // Step 2: Function to update the active link
  const setActiveLink = (link) => {
    activeLink.value = link
  }
  </script>
  
  <style scoped>



  
  @media (max-width: 995px) {
    nav {
      position: absolute;
      display: none;
      top: 0;
      right: 0;
      width: 40%;
      border-left: 3px solid #b74b4b;
      border-bottom: 3px solid #b74b4b;
      border-bottom-left-radius: 2rem;
      padding: 1rem solid;
      background-color: #161616;
      border-top: 0.1rem solid rgba(0, 0, 0, 0.1);
    }
  
    nav.active {
      display: block;
    }
  
    nav a {
      display: block;
      font-size: 2rem;
      margin: 3rem 0;
    }
  
    nav a:hover,
    nav a.active {
      padding: 1rem;
      border-radius: 0.5rem;
      border-bottom: 0.5rem solid #b74b4b;
    }
  }

  
.logo{
    font-size: 3rem;
    color: #b74b4b;
    font-weight: 800;
    cursor: pointer;
    transition: 0.5s ease;
}

.logo:hover{
    transform: scale(1.1);
}
  </style>
  