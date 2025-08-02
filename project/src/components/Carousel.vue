<template>
    <div class="container-fluid">


        <div class="carousel slide" id="carouselControls">
            <div class="carousel-inner">
                <!--Title card-->
                <div class="carousel-item active">
                    <div class="card">
                        <div class="card-body">
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
                            <h1>experience card test</h1>
                        </div>
                    </div>
                </div>
                <!--end Experience card-->
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
    cursor:auto;
}
</style>