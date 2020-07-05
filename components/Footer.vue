<template>
    <footer>
        <div class="container">
            <div class="social">
                <p>Follow Us</p>
                <ul>
                    <li><a href="https://www.meetup.com/GDG-Jakarta" target="_blank"><img src="../assets/img/icons/meetup.svg" alt=""></a></li>
                    <li><a href="https://www.facebook.com/gdgjakarta/" target="_blank"><img src="../assets/img/icons/facebook.svg" alt=""></a></li>
                    <li><a href="https://twitter.com/gdgjkt" target="_blank"><img src="../assets/img/icons/twitter.svg" alt=""></a></li>
                    <li><a href="https://www.instagram.com/gdgjakarta/" target="_blank"><img src="../assets/img/icons/instagram.svg" alt=""></a></li>
                    <li><a href="https://www.youtube.com/gdgjakarta" target="_blank"><img src="../assets/img/icons/youtube.svg" alt=""></a></li>
                </ul>
            </div>
            <div class="copyright d-flex justify-content-between">
                <div>
                    <img src="../assets/img/gdg-jakarta-dark.svg" alt="">
                </div>
                <p>&#9400; 2020. Made by GDG Jakarta - <a href="https://github.com/gdgindonesia/devfest-19-landing" target="_blank">Source Code</a></p>
            </div>
        </div>
    </footer>
</template>

<style lang="sass" scoped>
    @import "./node_modules/bootstrap/scss/bootstrap"

    footer
        background-color: #f8f9fa
        padding: 15px 0 30px 0
        span
            color: red
        .social
            display: flex
            align-items: center
            padding-bottom: 15px
            p
                margin: 0
                font-size: 15px
                text-transform: uppercase
                font-weight: 500
            ul
                list-style: none
                padding: 0
                margin: 0 10px
                li
                    display: inline-block
                    margin: 5px
                    img
                        max-width: 22px
                        width: 100%
        .copyright
            padding-top: 30px
            border-top: 1px solid #dedede
            img 
                height: 22px
            p
                font-size: 15px
                margin: 0
    
    @include media-breakpoint-down(md)
        footer
            .social
                justify-content: center
            .copyright
                flex-direction: column
                text-align: center
                p
                    margin-top: 15px
</style>