<template>
    <section id="partners">
        <div class="container">
             <div class="partners-group">
                 <div class="co-presenter">
                    <h6>Community Partners</h6>
                     <div class="partner-logo d-flex mb-4 mt-3 align-items-center flex-wrap">
                        <img src="../assets/img/partners/wtm.svg" class="wtm">
                        <img src="../assets/img/partners/dsc.svg" class="dsc">
                    </div>
                 </div>
             </div>
        </div>
    </section>
</template>

<style lang="sass" scoped>
    @import "./node_modules/bootstrap/scss/bootstrap"

    #partners
        .partners-group
            padding: 70px 0
        .co-presenter
            .gdg
                height: 40px
            .wtm
                height: 40px
            .dsc
                height: 40px
            .uii
                height: 80px
            img
                height: 90px
                margin: 10px 40px 0 0
        .media-partner
            .teknoevent
                margin-right: 40px
            .chromplex
                height: 45px
            img
                height: 60px

    @include media-breakpoint-down(md)
        #partners
            text-align: center
            .partner-logo
                justify-content: center
                img
                    margin: 15px 10px
</style>