<template>
    <div class="container-fluid">


        <div class="carousel slide" id="carouselControls">
            <div class="carousel-inner">
                <!--Title card-->
                <div class="carousel-item active">
                    <div class="card">
                        <div class="card-body d-flex justify-content-center align-items-center">
                            <div class="row">
                                <div class="col">
                                    <h1 class="display-1">Web & Software <br> Developer</h1>
                                </div>
                            </div>
                            <div class="row bg-danger">
                                <div class="col">

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!--end Title card-->
                <!--Experience card-->
                <div class="carousel-item">
                    <div class="card">
                        <div class="card-body">
                            <h1 class="display-1 text-start mb-5">Experience</h1>
                            <div class="container mx-5">
                                <h1 class="text-start">
                                    <strong class="fw-bold">
                                        What:
                                    </strong>
                                    Web Developer/Designer
                                </h1>
                                <h1 class="text-start">
                                    <strong class="fw-bold">
                                        Where:
                                    </strong>
                                    Eastman Kodak (remote)
                                </h1>
                                <h1 class="text-start">
                                    <strong class="fw-bold">
                                        When:
                                    </strong>
                                    May 2024 - Aug 2024
                                </h1>

                                <ul class="mx-5 mt-4">
                                    <li class="exp-bulletpoint text-start">
                                        <h4>
                                            Improved user experience and helped with
                                            a full site redesign using Vue.js
                                        </h4>

                                    </li>
                                    <li class="exp-bulletpoint text-start">
                                        <h4>
                                            Worked independently and in collaboration with a team
                                        </h4>
                                    </li>
                                    <li class="exp-bulletpoint text-start">
                                        <h4>
                                            Improved overall site functionality and QA testing
                                        </h4>
                                    </li>
                                    <li class="exp-bulletpoint text-start">
                                        <h4>
                                            Researched and recommended improvements for the site
                                        </h4>
                                    </li>
                                    <li class="exp-bulletpoint text-start">
                                        <h4>
                                            Updated page content through a Content Management System (CMS)
                                        </h4>
                                    </li>

                                </ul>
                            </div>



                        </div>
                    </div>
                </div>
                <!--end Experience card-->
                <!--Education card-->
                <div class="carousel-item">
                    <div class="card">
                        <div class="card-body">
                            <h1 class="display-1 text-start mb-5">Education</h1>

                            <div class="container mx-5">
                                <h1 class="exp-bulletpoint text-start fw-bold">Bachelor of Science</h1>
                                <h3 class="exp-bulletpoint text-start ms-5">in Computer Science</h3>
                                <h3 class="exp-bulletpoint text-start ms-5">Florida Southern College</h3>
                                <h3 class="exp-bulletpoint text-start ms-5">Aug 2022 - May 2025</h3>
                            </div>

                            <div class="container mt-5 mx-5">
                                <h1 class="exp-bulletpoint text-start fw-bold">Associate of Arts</h1>
                                <h3 class="exp-bulletpoint text-start ms-5">Hillsborough Community College</h3>
                                <h3 class="exp-bulletpoint text-start ms-5">May 2017 - Dec 2021</h3>
                            </div>
                        </div>
                    </div>
                </div>
                <!--end Education card-->
                <!--Recent projects card-->
                <div class="carousel-item">
                    <div class="card">
                        <div class="card-body">
                            <h1 class="display-1 text-start mb-5">Recent Projects</h1>

                            <div class="container mx-5">
                                <h1 class="text-start fw-bold">Nebulock</h1>
                                <h3 class="text-start ms-5">Vue.js, Firebase, Git, HTML/CSS, JS</h3>
                                <h3 class="text-start ms-5">Complex full-stack web application 
                                    that allows users to manage items in the game Destiny 2</h3>
                            </div>

                            <div class="container mt-5 mx-5 mb-5">
                                <h1 class="text-start fw-bold">Flashdeck</h1>
                                <h3 class="text-start ms-5">Django, Python, HTML/CSS, JS</h3>
                                <h3 class="text-start ms-5">full-stack web application for 
                                    creating and studying flashcards with advanced memorization 
                                    techniques</h3>
                            </div>

                            <a class="repo-link" href="https://github.com/JovanniRodriguez?tab=repositories">
                                <h2 class="text-start mt-5 ms-2">More Projects</h2>
                            </a>
                        </div>
                    </div>
                </div>
                <!--end Recent projects card-->
            </div>
        </div>

        <!-- <div class="row">
            <div class="col">
                <button role="button" data-bs-slide="next"
                data-bs-target="#carouselControls" id="nextSlideButton">
                    <img class="nav-arrow-right-img" src="/icons/nav-arrow-right-icon.png" alt="next">
                </button>
            </div>
        </div> -->

    </div>
</template>

<script>
export default {
    name: 'TitleSlide',
}
</script>

<style scoped>
.card {
    border: none;
}
.card-body{
    min-height: 800px;
}
.nav-arrow-right-img {
    width: 70px;
    cursor: pointer;
}

.nav-arrow-right-img:hover {
    transform: scale(1.3);
    transition: transform 0.5s ease;
}

#nextSlideButton {
    border: none;
    border-radius: 40%;
    width: auto;
    height: fit-content;
    background-color: transparent;
    cursor: auto;
}

.exp-bulletpoint {
    word-wrap: break-word;
    white-space: normal;
    overflow-wrap: anywhere;
}

.repo-link {
    display: inline-block;
    opacity: 10%;
    text-decoration: underline;
    color: black;
}
.repo-link:hover {
    
    opacity: 100%;
}
</style>