<template>
    <section id="about">
        <div class="container">
            <div class="about-group photo-group">
                <div class="row">
                    <div class="gdg col-12 col-md-6">
                        <h3>What is GDG?</h3>
                        <p>Google Developer Group is an open group of people who are interested in having open discussion about Google technologies. There are many froms of activities like watching videos together, open discussion, or gatherings.</p>
                        <p>When you join a Google Developer Group, you'll have the opportunity to meet local developers with similar interests in technology. A GDG meetup event includes talks on a wide range of technical topics where you can learn new skills through hands-on workshops. The community prides itself on being an inclusive environment where everyone and anyone interested in tech - from beginner developers to experienced professionals - all are welcome to join.</p>
                    </div>
                    <div class="devfest photo-group photo-item col-12 col-md-6">
                        <img src="../assets/img/gdgorganizers.jpg" alt="" class="w-100">
                   </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="sass" scoped>
    @import "./node_modules/bootstrap/scss/bootstrap"

    #about
        .about-group
            padding: 100px 0 50px 0
            .products
                list-style: none
                padding: 0
                li
                    display: inline-block
                    margin: 0 10px
                    img
                        height: 40px
                li:first-child
                    margin-left: 0

    @include media-breakpoint-down(md)
        #about
            .about-group
                .devfest
                    margin-top: 25px

    #about
        padding: 50px 0
        .photo-group
            .photo-item
                padding: 10px
                img
                    border-radius: 10px
                    height: 300px
                    object-fit: cover
                    object-position: center center
</style>