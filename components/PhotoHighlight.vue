<template>
    <section id="photo-hightlight">
        <div class="container">
            <h3 class="pb-2">#GDGJakarta Highlight</h3>
            <div class="photo-group row">
                <div class="photo-item col-6 col-lg-3">
                    <img src="../assets/img/devfest18/1.jpg" alt="" class="w-100">
                </div>
                <div class="photo-item col-6 col-lg-3">
                    <img src="../assets/img/devfest18/11.jpg" alt="" class="w-100">
                </div>
                <div class="photo-item col-12 col-lg-6">
                    <img src="../assets/img/devfest18/3.jpg" alt="" class="w-100">
                </div>
                <div class="photo-item col-6 col-lg-2">
                    <img src="../assets/img/devfest18/8.jpg" alt="" class="w-100">
                </div>
                <div class="photo-item col-6 col-lg-5">
                    <img src="../assets/img/devfest18/12.jpg" alt="" class="w-100">
                </div>
                <div class="photo-item col-12 col-lg-5">
                    <img src="../assets/img/devfest18/6.jpg" alt="" class="w-100">
                </div>
            </div>
        </div>
        <br>
        <div class="text-center">
            <a href="http://bit.ly/jkt-devfest-19" target="_blank">
                <button class="btn btn-primary btn-lg">See more photos</button>
            </a> 
        </div>
    </section>
</template>

<style lang="sass" scoped>
    #photo-hightlight
        padding: 50px 0
        .photo-group
            .photo-item
                padding: 10px
                img
                    border-radius: 10px
                    height: 220px
                    object-fit: cover
                    object-position: center center
</style>
