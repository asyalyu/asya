---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

---


<style>
    #sidebar a {
  color: black;
  text-decoration: none; /* Optional: Remove underline */
}
#sidebar a.active {
  color:rgb(16, 10, 212);
  font-weight: bold;

}
</style>

<nav id="sidebar" style="
  position: fixed;
  top: 185px;
  left: 210px; /* Halfway between 0 and 220px */
  width: 200px;
  height: 80vh;
  padding: 1rem;
  background-color: transparent;
  border-right: none;
  overflow-y: auto;
  transform: translateX(-50%);
  font-size: 1.5rem; /* Increase base font size */
  font-weight: 600; /* Optional: make text bolder */
">
  <ul style="font-family: 'Open Sans', sans-serif; font-size: 1.7rem;list-style: none; padding-left: 0; margin: 0;">
    <li><a href="#projects">Recent Projects</a></li>
    <li><a href="#publications">Publications</a></li>
    <li><a href="#technologies">Technologies and Skills</a></li>
    <li><a href="#awards">Awards</a></li>
    <li><a href="#education">Education</a></li>
  </ul>
</nav>


<!-- <div id="right-graphic-container" style="
  position: fixed;
  top: 100px;
  right: 20px;
  width: 200px;
  height: 200px;
  z-index: 1000;
">
  <img src="/assets/3.png" alt="Moving Graphic" id="moving-graphic" style="width: 100%; height: 100%;" />
</div> -->

<main class="page-content" aria-label="Content">
  <div class="wrapper" style="max-width: 1600px; margin: auto;">
    <div class="home" style="border-left: none; padding-left: 1rem;">

<div class="top-section" style="display: flex; justify-content: space-between; align-items: center; padding: 2rem; position: relative;">

  <div style="max-width: 100%; line-height: 1.4;">
    <h1 style="font-family: 'Open Sans', sans-serif; font-size: 2.2rem;margin: 0 0 0.5rem 0;">Asya (Lyubavina) Vaisberg</h1>
    <p style="font-family: 'Georgia', serif; font-size: 1.7rem; margin:  0 0 0.5rem 0; color: rgb(16, 10, 212)">
      Jack of All Trades, Master of Some 
    </p>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;">
    Student of Computer Science and Chinese at Pomona College
      </p>
  </div>

  <img src="{{ '/assets/Asya Headshots 2025-12.jpg' | relative_url }}" alt="Asya (Lyubavina) Vaisberg" style="width: 300px; height: 300px; object-fit: cover; border-radius: 8px; margin-right: -20rem;" />

</div>

          
<div class="lower-section" style="padding: 2rem; width: 140%; margin: auto;">
            <h2 style="font-family: 'Georgia', serif; font-size: 1.7rem; margin:  0 0 2.5rem 0;" id="projects">Recent Projects</h2>
            <section class="project" style="display: flex; align-items: center; margin-bottom: 2rem; padding-bottom: 1rem;">
  <img src="{{ '/assets/pai.png' | relative_url }}" alt="Pa-i Website" style="width: 250px; height: 150px;border-radius: 8px;object-fit: cover; margin-right: 1rem; flex-shrink: 0;" />
  <div>
    <h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0; font-weight: bold;color: rgb(16, 10, 212)" >Pa-i Website</h3>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;">Led a team to design and launch a modern, user-centric website for the P-ai club, implementing enhanced UI/UX features as well as expanded functionality to increase member engagement</p>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;"><a href="https://pai5c.com/" target="_blank">Website</a></p>
  </div>
</section>





<section class="project" style="display: flex; align-items: center; margin-bottom: 2rem; padding-bottom: 1rem;">
  <img src="{{ '/assets/quiz.png' | relative_url }}" alt="Adaptive Chinese Placement Test" style="width: 250px; height: 150px; object-fit: cover; margin-right: 1rem; flex-shrink: 0;border-radius: 8px;" />
  <div>
    <h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0; font-weight: bold; color: rgb(16, 10, 212)">Adaptive Chinese Placement Test</h3>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;">Currently maintaining the Firebase web-app and developing new functionality to improve user experience</p>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;"><a href="https://adaptive-chinese-test.firebaseapp.com/" target="_blank">Website</a></p>
  </div>
</section>

<section class="project" style="display: flex; align-items: center; margin-bottom: 2rem; border-bottom: 1px solid #ccc; padding-bottom: 1rem;">
  <img src="{{ '/assets/gradio.png' | relative_url }}" alt="AI-Powered Document Reader for BLV Users" style="width: 250px; height: 150px; object-fit: cover; margin-right: 1rem; flex-shrink: 0; border-radius: 8px;" />
  <div>
    <h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0; font-weight: bold; color: rgb(16, 10, 212)">AI-Powered Document Reader for BLV Users</h3>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;">Collaborated with classmates to design and develop an AI powered document/image reading application for visually impaired users</p>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;"><a href="https://github.com/verrels15/AI-Powered-Document-Reader-for-BLV-Users" target="_blank">Github Repo</a></p>
  </div>
</section>

          
<h2 style="font-family: 'Georgia', serif; font-size: 1.7rem; margin:  0 0 2.5rem 0;" id = "publications" >Publications</h2>
           
          
<section class="publication" style="display: flex; align-items: center; margin-bottom: 2rem; border-bottom: 1px solid #ccc; padding-bottom: 1rem;">
  <img src="{{ 'assets/artkrit.png' | relative_url }}" alt="Computational Scaffolding..." style="width: 250px; height: 150px; object-fit: cover; margin-right: 1rem; flex-shrink: 0; border-radius: 8px;" />
  <div>
    <h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0; font-weight: bold; color: rgb(16, 10, 212)">Computational Scaffolding of Composition, Value, and Color for Disciplined Drawing</h3>
    <p style="font-family: 'Georgia', serif; font-size: 1rem; margin:  0 0 0.5rem 0;">ACM Symposium on User Interface Software and Technology (UIST), 2025</p>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;"> Collaborated with a multidisciplinary team to design and develop ArtKrit, a novel Krita extension which leverages AI-driven image segmentation to support disciplined drawing in digital art. Spearheaded user studies, employing iterative design methodologies to identify optimal features and improve user experience for digital artists. Co-authored a peer-reviewed paper on ArtKrit which received the <span style = "font-weight: bold; color: rgb(16, 10, 212)"> Best Paper Award at the ACM Symposium on User
Interface Software and Technology (UIST) </span> , a top-tier Human-Computer Interaction (HCI) conference </p>
    <p style="font-family: 'Open Sans', sans-serif; font-size: 1rem; margin:  0 0 0.5rem 0;"><a href="https://arxiv.org/abs/2509.17268" target="_blank">Read Paper</a></p>
  </div>
</section>

          
<h2 style="font-family: 'Georgia', serif; font-size: 1.7rem; margin:  0 0 2.5rem 0;" id = "technologies">Technologies and Skills</h2>
            <section class="technologies" style="margin-bottom: 2rem;border-bottom: 1px solid #ccc; padding-bottom: 1rem;">
  <p style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;">
    <span style = "font-weight: bold;color: rgb(16, 10, 212)"> Computer Languages:</span> Python, Java, JavaScript, HTML/CSS, Swift, Haskell
  </p>
  <p style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;">
    <span style = "font-weight: bold;color: rgb(16, 10, 212)"> Technologies:</span> Git, Firebase, React, Node.js, Flask, Heroku
  </p>
  <p style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;">
    <span style = "font-weight: bold;color: rgb(16, 10, 212)"> UX Research:</span> Thematic Analysis, Contextual Research Methods (Surveys, Interviews, Storyboarding), Prototyping (Figma)
  </p>
  <p style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;">
    <span style = "font-weight: bold;color: rgb(16, 10, 212)"> Human Languages:</span> English (fluent), Russian (fluent), Chinese (advanced), French (intermediate)
  </p>
</section>

<h2 style="font-family: 'Georgia', serif; font-size: 1.7rem; margin:  0 0 2.5rem 0;" id = "awards" >Awards</h2>
            
<h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;font-weight: bold;color: rgb(16, 10, 212)">Best Paper Award</h3>
              <p style="font-family: 'Georgia', serif; font-size: 1rem; margin:  0 0 0.5rem 0;" >UIST, 2025</p>
              

          
<h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0;font-weight: bold; color: rgb(16, 10, 212)">Tapia Scholarship Recipient</h3>
              <p style="font-family: 'Georgia', serif; font-size: 1rem; margin:  0 0 0.5rem 0;">Tapia, 2025</p>
        
     

<section class="awards" style="margin-bottom: 2rem; border-bottom: 1px solid #ccc; padding-bottom: 1rem;">
            <h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0; font-weight: bold;color: rgb(16, 10, 212)">Summer Undergraduate Research Program (SURP)</h3>
            <p style="font-family: 'Georgia', serif; font-size: 1rem; margin:  0 0 0.5rem 0;">Pomona College, 2024</p>
          </section>
 
          
   
<h2  style="font-family: 'Georgia', serif; font-size: 1.7rem; margin:  0 0 2.5rem 0;" id = "education">Education</h2>
            <section class="Education" style="margin-bottom: 2rem; ">
              <h3 style="font-family: 'Open Sans', sans-serif; font-size: 1.3rem; margin:  0 0 0.5rem 0; font-weight: bold;color: rgb(16, 10, 212)">Pomona College</h3>
              <p style="font-family: 'Georgia', serif; font-size: 1rem; margin:  0 0 0.5rem 0;">Double Major in Computer Science and Chinese</p>
              
</section>
           

  </div>


<script>
document.addEventListener('DOMContentLoaded', function () {
  const sections = document.querySelectorAll('main h2[id]');
  const navLinks = document.querySelectorAll('#sidebar a');

  function changeActiveLink() {
    let index = sections.length - 1;

    // Detect if scrolled to bottom
    const scrollBottom = window.innerHeight + window.scrollY >= document.body.offsetHeight - 2;

    if (scrollBottom) {
      // Highlight last link if at bottom
      index = sections.length - 1;
    } else {
      // Otherwise, find the current section by comparing scrollY and offsetTop
      for (let i = 0; i < sections.length; i++) {
        if (window.scrollY + 100 < sections[i].offsetTop) {
          index = i - 1;
          break;
        }
      }
      if (index < 0) index = 0;
    }

    navLinks.forEach(link => link.classList.remove('active'));
    if (navLinks[index]) {
      navLinks[index].classList.add('active');
    }
  }

  window.addEventListener('scroll', changeActiveLink);
  changeActiveLink();
});

document.addEventListener('scroll', function() {
  const graphic = document.getElementById('moving-graphic');
  // Get scroll amount between 0 and 1 for range
  const scrollPosition = window.scrollY / (document.body.scrollHeight - window.innerHeight);
  // Create movement range (e.g., 50px up and down)
  const movement = 50 * Math.sin(scrollPosition * 2 * Math.PI * 3); // 3 cycles
  graphic.style.transform = `translateY(${movement}px)`;
});

</script>