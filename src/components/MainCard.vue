<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/pp.jpg" alt="">
                <h3>Kevin LEAO</h3>
                <p>Developpeur Web</p>
            </div>
            <div class="social-links">
                <a href="">
                    <div class="link">
                        <img src="../assets/githubLogo.png" alt="">
                        <h2>GitHub</h2>
                    </div>
                    <div class="link">
                        <img src="../assets/linkedinLogo.png" alt="">
                        <h2>Linkedin</h2>
                    </div>
                    <div class="link">
                        <img src="../assets/instagramLogo.png" alt="">
                        <h2>Instagram</h2>
                    </div>
                </a>
            </div>
        </div>
    
        <div class="container-two">
            <div class="about-me">
                <h1>About Me</h1>
                <p> Sed tempor metus eget wisi. Duis cursus. Nam nunc. Nulla placerat wisi sed est. 
                    Aenean risus. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Proin erat dolor, 
                    ultricies a, rutrum sed, posuere eget, metus. Donec sagittis nunc ac tortor. Aliquam erat volutpat. 
                    Curabitur consectetuer, augue nec viverra eleifend, dolor dolor volutpat orci, dapibus pellentesque eros pede a arcu. 
                    Nullam augue. Etiam eget nulla vel mi porta hendrerit. Phasellus cursus scelerisque tortor. Maecenas ut leo.</p>
            </div>
            <div class="technology-section">
                <h1>Technologies Studied</h1>
                <img src="../assets/htmlLogo.png" alt="">
                <img src="../assets/cssLogo.png" alt="">
                <img src="../assets/jsLogo.png" alt="">
            </div>
            <div class="button-container">
                <div class="projects-button">
                    <a href="">My Projects</a>
                </div>
                <div>
                    <a href="">My Resume</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    img{
        height: 20px;
    }

    .main-container{
        display: flex;
        flex-direction: row;
        background-color: grey;
    }
</style>