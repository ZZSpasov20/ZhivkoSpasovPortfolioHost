<script setup lang="ts">

</script>

<template>
    
    <h1 class="projects-heading" id="work">Projects<span class="projects-heading--accent">.</span></h1>
    <div class="project-wrapper">
        <div class="image-wrapper" id="chrome">

        </div>
        <div class="project-text-wrapper" >
            <div class="accent-button">
                <p>JS</p>
            </div>
            <h2 class="project-title">This is the project Chroma</h2>
            <p class="project-text">Currently in development</p>
        </div>
    </div>
    <div class="project-wrapper project-wrapper--second">
        <div class="image-wrapper" id="strive">

        </div>
        <div class="project-text-wrapper" >
            <div class="accent-button">
                <p>Typescript</p>
            </div>
            <h2 class="project-title">This is the project Strive</h2>
            <a href="https://github.com/ZZSpasov20/Strive"><p class="project-text">Read more</p></a>
        </div>
    </div>
    <div class="project-wrapper">
        <div class="image-wrapper" id="neos">

        </div>
        <div class="project-text-wrapper" >
            <div class="accent-button">
                <p>C++</p>
            </div>
            <h2 class="project-title">This is the project Neos</h2>
            <a href="https://github.com/ZYPetkova20/Neos/tree/main"><p class="project-text">Read more</p></a>
        </div>
    </div>
</template>

<style scoped>
    @import '../assets/base.css';
    
    .projects-heading{
        margin-top: var(--section-gap);
        text-align: center;
        font-size: 40px;
        font-family: var(--heading-font);
    }
    .projects-heading--accent{
        color: var(--accent-colour);
    }

    .project-wrapper{
        margin-top: var(--section-gap);
        width: 100%;
        display: flex;
        height: 350px;
        align-items: center;
        justify-content: center;
        gap: 200px;
    }
    .image-wrapper{
        background-color: black;
        width: 650px;
        height: 360px; 
    }
    .project-text-wrapper{
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 30px;
    }
    .accent-button{
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: var(--accent-colour);
        width: 235.459px;
        height: 42.442px; 
        font-family: var(--heading-font);
        font-size: 18px;
        color: var(--text-colour-light);
    }
    .project-title{
        font-family: var(--heading-font);
        font-size: 40px;
        width: 470px;
    }
    .project-text{
        font-family: var(--heading-font);
        font-size: 20px;
        text-decoration: underline;
    }
    .project-wrapper--second{
        flex-direction: row-reverse
    }

    #neos{
        background-image: url("../assets/img/neosProject.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
    #strive{
        background-image: url("../assets/img/stive.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
    #chrome{
        background-image: url("../assets/img/chroma.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
</style>
