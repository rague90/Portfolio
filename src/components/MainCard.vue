<template>
<div class="wrapper">
        <div class="main-container">
         <div class="container-one">
              <div class="profile">
                     <img src="../assets/DSC08564.jpg" alt="">
                      <h3>Guedjiba Abdraouf</h3>
                      <p>Software Developer</p>
              </div>
              <div class="social-links">
                 
                      <div class="link">
                      <a href="https://github.com/rague90"> 
                         <img src="../assets/5968866.png" alt="">
                        <h2>Github</h2>
                        </a> 
                      </div>

                      <div class="link">
                       <a href="https://www.linkedin.com/in/guedjiba-raouf-308530135/">
                          <img src="../assets/174857.png" alt="">
                         <h2>Linked</h2>
                         </a>
                      </div>

                      <div class="link">
                         <a href="https://www.facebook.com/photo/?fbid=1892851877584201&set=a.602424963293572"> 
                            <img src="../assets/kisspng-college-of-charleston-logo-computer-icons-free-high-quality-twitter-icon-5ab03c2d9ad5b2.4819297715214991816342.jpg" alt="">
                          <h2>Twitter</h2>
                        </a> 
                      </div>

                      <div class="link">
                  
                        <a href="https://www.facebook.com/photo/?fbid=1892851877584201&set=a.602424963293572">
                            <img src="../assets/Instagram-Icon.png" alt="">
                            <h2>instagram</h2>
                            </a>
                      </div>
                 

              </div>



         
</div>

         <div class="container-tow">
            <div class="about-me">
                <h1>About Me</h1>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Rerum eveniet optio exercitationem quia asperiores numquam aliquid vero deleniti accusamus, iure totam enim, neque iste hic recusandae, sapiente consectetur similique est.
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis repudiandae, ipsa doloremque nesciunt deserunt maxime explicabo consequuntur architecto expedita ex quibusdam. Iste officia quam reiciendis natus. Accusamus quam excepturi nobis.
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vitae, non illo beatae fuga voluptates aut debitis voluptatibus reiciendis qui pariatur corporis placeat provident nulla doloremque odio at? Rerum, voluptate error?
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Est nisi at illum? Laudantium aspernatur eveniet debitis eos culpa in repudiandae, impedit ad quo, itaque voluptates, nisi nulla laboriosam tempore eligendi!
                </p>
            </div>

            <div class="technology-section">
                <h1>Technologies Studied</h1>
                <div class="logos">
                    <img src="../assets/html.png" alt="">
                    <img src="../assets/js.png" alt="">
                    <img src="../assets/PHP-PNG-File.png" alt="">
                    <img src="../assets/laravel.png" alt="">
                    <img src="../assets/logo.png" alt="">
                </div>
            </div>
            
            <div class="button-conainer">
                 <div class="projects-button">
                       <a href="">My Projects</a>
                 </div>
                 <div  class="projects-button">
                    <a href="">My Resume</a>
                 </div>
            </div>






         </div>
 
 </div>
</div>

</template>
<script>
</script>
<style>
.wrapper
{
    display: flex;
    justify-content: center;
}

img{
    height: 20px;
    border-radius:5px ;
}
.main-container 
{
    display: flex;
    flex-direction: row;
    background-color: #A6ACAF  ;
    border-radius: 20px;
      box-shadow: rgba(0.24,0.24,0.24,0.24) 4px 3px 8px;
      width: 60%;
}
.container-one
{
    background-color: #DBE1E1  ;
    width: 20%;
    padding: 1%;
    margin: 0.5%;
    border-radius: 20px;
    box-shadow: rgba(0.24,0.24,0.24,0.24) 4px 3px 8px;
}
.profile img
{
height: 8rem;

}
.link a
{
    text-decoration: none;
    color: #2c3e50;
    font-size: 12px;
}
.link img
{
    height: 2rem;
}
.container-tow
{
background-color:#fff;
width: 80%;
margin: 1%;
border-radius:15px ;
  box-shadow: rgba(0.24,0.24,0.24,0.24) 4px 3px 8px;
}
.about-me
{
    text-align: left;
    margin: 0.5%;
}
.logos img
{
    height: 2.5rem;
}
.button-conainer
{
    margin-top:2% ;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}
.projects-button
{
    background-color:#281834  ;
    margin: 5px;
    padding: 5px;
    border-radius: 12px;;
}
.projects-button a {
    text-decoration: none;
     color: #fff;
}


</style>
