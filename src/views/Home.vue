<!-- src/views/Home.vue -->
<template>
    <section class="home">
        <div class="home-img">
            <img src="/src/imgs/nagato.jpg" alt="">
        </div>
        <div class="home-content">
            <h1>Hi, It's <span>Kamil</span></h1>
            <h3 class="typing-text">I'm a <span></span></h3>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Minus labore dolores esse. Odit similique doloribus tenetur doloremque, sunt commodi in ipsa repudiandae debitis deleniti blanditiis quibusdam quaerat neque asperiores ea.</p>
            <div class="social-icons">
                <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                <a href="#"><i class="fa-brands fa-github"></i></a>
                <a href="#"><i class="fa-brands fa-x-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-instagram"></i></a>
            </div>
        </div>
    </section>

    <section id="services">
      <div class="container">
        <h2>Services</h2>
        <div class="cards">
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
        </div>
      </div>
    </section>

    <section id="skills">
      <div class="container">
        <h2>Skills</h2>
        <div class="cards">
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
        </div>
      </div>
    </section>
    <section id="education">
      <div class="container">
        <h2>Education</h2>
        <div class="cards">
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
        </div>
      </div>
    </section>

    <section id="expirience">
      <div class="container">
        <h2>Expirience</h2>
        <div class="cards">
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
          <div class="text-card">
            <h3>Title</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et deserunt sint accusantium est modi beatae saepe esse! Deserunt, quidem expedita quaerat a voluptatem perspiciatis iure optio quod cum molestias amet!</p>
          </div>
        </div>
      </div>
    </section>

  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  
.home{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 8rem;
    background-color: rgb(0, 0, 0);
}

.home .home-content h1{
    font-size: 6rem;
    font-weight: 700;
    line-height: 1.3;
}

span{
    color: #b74b4b;
}

.home-content h3{
    font-size: 4rem;
    margin-bottom: 1rem;
    font-weight: 700;
}

.home-content p{
    font-size: 1.6rem;
}

.home-img{
    border-radius: 50%;
}

.home-img img{
    position: relative;
    width: 32vw;
    border-radius: 50%;
    box-shadow: 0 0 25px solid #b74b4b;
    cursor: pointer;
    transition: 0.2s linear;
}

.home-img img:hover{
    font-size: 1.8rem;
    font-weight: 500;
}

.social-icons a{
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 4rem;
    height: 4rem;
    background-color: transparent;
    border: 0.2rem solid #b74b4b;
    font-size: 2rem;
    border-radius: 50%;
    margin: 3rem 1.5rem 3rem 0;
    transition: 0.3s ease;
    color: #b74b4b;
}

.social-icons a:hover{
    color: black;
    transform: scale(1.3) translateY(-5px);
    background-color: #b74b4b;
    box-shadow: 0  0 25px #b74b4b;
}

.btn{
    display: inline-block;
    padding: 1rem 2.8rem;
    background-color: black;
    border-radius: 4rem;
    font-size: 1.6rem;
    color: #b74b4b;
    letter-spacing: 0.3rem;
    font-weight: 600;
    border: 2px solid #b74b4b;
    transition: 0.3s ease;
    cursor: pointer;
}

.btn:hover{
    transform: scale3d(1.03);
    background-color: #b74b4b;
    color: black;
    box-shadow: 0 0 25px #b74b4b;
}

.typing-text{
    font-size: 34px;
    font-weight: 600;
    min-width: 280px;
}

.typing-text span{
    position: relative;
}

.typing-text span::before{
    content: "software Developer";
    color: #b74b4b;
    animation: words 20s infinite;
}

.typing-text span::after{
    content: "";
    background-color: black;
    position: absolute;
    width: calc(100% + 8px);
    height: 100%;
    border-left: 3px solid black;
    right: -8;
    animation: cursor 0.6s infinite;
}

section{
    min-height: 100vh;
    padding: 5rem 9% 5rem;
    display: flex;
    justify-content: center;
    align-items: center;
}

section:nth-child(1){
    color: #fff;
}

section:nth-child(2){
    color: #fff;
    /* background: #fff; */
}

section:nth-child(3){
    /* background: #fff; */
}


section .container{
  margin: 100px;
}

section h1{
  font-size: 60px;
}

section h2{
  font-size: 40px;
  text-align: center;
  text-transform: uppercase;
}


section .cards{
  display: flex;
}

section .cards .text-card{
  background: #b74b4b;
  margin: 20px;
  padding: 20px;
}

section .cards .text-card h3{
  font-size: 30px;
  text-align: center;
  text-transform: uppercase;
  margin-bottom: 10px;
}

@media(max-width: 900px){
  section h1{
    font-size: 40px;
  }

  section .cards{
    flex-direction: column;
  }
}

</style>
  