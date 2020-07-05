<template>
    <section id="hero">
        <div class="container">
            <div class="hero-group d-flex justify-content-center align-items-center text-center">
                <div class="hero-content">
                    <img src="" alt=""><br>
                    <div class="hero-desc">
                        <p class="mb-2"></p>
                        <p><b></b></p> 
                   </div>
                </div>
            </div>
            <a href="#about" class="scroll-down"></a>
        </div>
    </section>
</template>

<style lang="sass" scoped>
    #hero
        height: 100vh
        background-image: url('../assets/img/devfest.svg')
        background-position: center center
        background-size: cover
        width: 100%
        .hero-group
            height: 100vh
            width: 100%
            .hero-content
                width: 100%
                margin-top: 60px
                img
                    max-width: 550px
                    width: 100%
                .hero-desc
                    margin-top: 30px
                    p
                        font-size: 19px
                        margin-bottom: 0
                        font-weight: 300
                    .address
                        font-size: 16px
                        margin-top: 10px
        .scroll-down
            position: absolute
            left: 49%
            bottom: 50px
            display: block
            text-align: center
            font-size: 20px
            z-index: 100
            text-decoration: none
            width: 35px
            height: 35px
            border-bottom: 2px solid #4285F4
            border-right: 2px solid #4285F4
            z-index: 3
            transform: translate(-50%, 0%) rotate(45deg)
            animation: fade_move_down 2.5s ease-in-out infinite

            /*animated scroll arrow animation*/
            @keyframes fade_move_down
                0%  
                    transform: translate(0,-10px) rotate(45deg)
                    opacity: 0
                50% 
                    opacity: 1
                100%
                    -webkit-transform: translate(0,10px) rotate(45deg)
                    opacity: 0
</style>