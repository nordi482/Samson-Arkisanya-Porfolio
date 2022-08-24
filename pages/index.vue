<template>
     <header class="full-page">
        <div className='nav-bar'>
          <div class="logo-container">
            <img src="assets/icons/sa.svg" alt="logo">
          </div>
            <a href="">Resume</a>
            <a href="">Project</a>
            <a href="">About</a>
            <button class="btn-stroke">Contact Me</button>
        </div>

          <div class="first-container">
            <div class="hero-section">
            <div class="web-block">Samson Akisanya <br> Senior <span class="web-word">Android </span> Developer and <br> <span class="web-word-two">Kotlin Backend</span> Developer</div>
            </div >
          <div class="social-media">
                    <img src="assets/icons/twitter.svg" alt="logo-social">
                    <img src="assets/icons/github.svg" alt="logo-social">
                    <img src="assets/icons/linkedin.svg" alt="logo-social">
                    <img src="assets/icons/instagram.svg" alt="logo-social">

            <button class="btn-filled"> <img src="assets/icons/calender.svg" alt="btn-call"> Schedule a call </button>
            </div>

            <div class="second container">
                  <h5 class="extras"> 15+ Years of experience</h5>
                   <h5 class="extras"> 100+ Completed projects</h5>
                   <h5 class="extras"> 100+ Happy customers</h5>
            </div>
          </div>


          <div class="third-container">
             
              <section class="about-me">
                  
                  <img src="assets/images/BG.png" alt="image">
                  <h6 class="text-area">Samson is a highly motivated professional, committed to achieving <br> excellence both professionally and personally. He has detailed knowledge <br>
                  and experience of Testing, Analysis, Design, Configuration, Development and <br> Implementation. Samson is a lateral thinker and has a strong passion for <br>
                  learning about new technologies. Samson has good communication skills <br> combined with the ability to relate well to people at all levels. Samson is a <br> 
                  great self starter and very capable of working independently. Samson has a <br> lot of experience working in an Agile scrum environment using JIRA. Samson <br>
                  recognizes the importance of Test Driven Development with Unit Testing and <br> is a diligent practitioner. Samson is an enthusiastic student of Machine <br> Learning and Data Science. <br>
                  <code> I build </code> </h6>

              </section>
          </div>

          <div class="fourth-container">

              <section class="experience">

                    <h3 class="text">I've worked at</h3>
                    <img src="" alt="assets/icons/VEON Logo.svg">
                    <img src="" alt="assets/icons/skylogo.svg">
                    <img src="" alt="assets/icons/yeologo.svg">
                    <img src="" alt="assets/icons/dopaylogo.svg">
                    <img src="" alt="assets/icons/isobarlogo.svg">
                    <img src="" alt="assets/icons/Accedo Logo.svg">
                    <img src="" alt="assets/icons/Nokia Logo.svg">
                    <img src="" alt="assets/icons/clydesdale.svg">
              
              </section>
              
          </div>
          
          <div class="fifth-container">

              <section class="projects-box">
                       <div class="projects">
                                <h4 class="project-name">MyPinPad</h4>
                                <img src="assets/images/pinpad.png" alt="project-image">
                                <h4 class="project-role">Senior Andriod Dev</h4>
                                <h4 class="project-date">Nov 2021-present</h4>
                       </div>

                       <div class="projects">
                                <h4 class="project-name">Deliveroo</h4>
                                <img src="assets/images/deliveroo.png" alt="project-image">
                                <h4 class="project-role">Senior Andriod Dev</h4>
                                <h4 class="project-date">Feb 2021-May 2021</h4>
                       </div>

                       <div class="projects">
                                <h4 class="project-name">Curry Pc World Apps</h4>
                                <img src="assets/images/currypc.png" alt="project-image">
                                <h4 class="project-role">Senior Andriod Dev</h4>
                                <h4 class="project-date">Dec 2020-Feb 2021</h4>
                       </div>

                       <div class="projects">
                                <h4 class="project-name">Dopay</h4>
                                <img src="assets/images/dopay.png" alt="project-image">
                                <h4 class="project-role">Lead Andriod Dev</h4>
                                <h4 class="project-date">2017</h4>
                       </div>

                       <div class="projects">
                                <h4 class="project-name">Zara Med</h4>
                                <img src="assets/images/zaramed.png" alt="project-image">
                                <h4 class="project-role">Lead Andriod Dev</h4>
                                <h4 class="project-date">2020</h4>
                       </div>

                       <div class="projects">
                                <h4 class="project-name">Weezy</h4>
                                <img src="assets/images/weezy.png" alt="project-image">
                                <h4 class="project-role">Lead Andriod Dev</h4>
                                <h4 class="project-date">2020</h4>
                       </div>

                       <div class="view-more">
                          View More Projects
                       </div>
              
              </section>
          
          </div>

     </header>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
