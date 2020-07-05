<template>
    <div id="navbar">
        <nav class="navbar navbar-expand-lg navbar-light fixed-top pl-5 pr-5">
            <div class="navbar-brand" href="#">
                <nuxt-link to="/"><img src="../assets/img/gdg-jakarta-logo.svg" alt="" class="w-100"></nuxt-link>
            </div>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto ml-3">
                    <li class="nav-item">
                        <div class="nav-link"><nuxt-link to="/">Home</nuxt-link></div>
                    </li>
                    <li class="nav-item">
                        <div class="nav-link"><nuxt-link to="/">About</nuxt-link></div>
                    </li>
                    <li class="nav-item">
                        <div class="nav-link"><nuxt-link to="/">Events</nuxt-link></div>
                    </li>
                    <li class="nav-item">
                        <div class="nav-link"><nuxt-link to="/teams">Team</nuxt-link></div>
                    </li>
                    <li class="nav-item">
                        <div class="nav-link"><nuxt-link to="/">Schedule</nuxt-link></div>
                    </li>
                    <!--<li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Dropdown
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Action</a>
                        <a class="dropdown-item" href="#">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Something else here</a>
                        </div>
                    </li>-->
                </ul>
                <div class="register-button">
                    <nuxt-link to="/#call-to-action">
                        <button class="btn btn-primary">Join us!</button>
                    </nuxt-link>
                </div>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    data() {
        return {
            isActive: false
        }
    }
}
</script>

<style lang="sass" scoped>
    @import "./node_modules/bootstrap/scss/bootstrap"
    
    #navbar
        .navbar
            background-color: white
            // border-bottom: 1px solid #dedede
            box-shadow: 0 4px 5px 0 rgba(0,0,0,0.14), 0 1px 10px 0 rgba(0,0,0,0.12), 0 2px 4px -1px rgba(0,0,0,0.2)
            height: 70px
            .navbar-brand
                max-width: 200px
                width: 100%
            .navbar-nav
                position: relative
                .nav-item
                    padding: 0 10px
                    a
                        text-decoration: none
                        color: #676c72
                .active
                    a
                        color: #212121 !important
                .active:after
                    content: ""
                    position: absolute
                    width: calc(35% - 25px)
                    height: 2px
                    background-color: #1a73e8
                    bottom: -15px
                    left: 0
                
    @include media-breakpoint-down(md)
        .navbar 
            padding-left: 15px !important
            padding-right: 15px !important
            height: 70px
            .navbar-collapse
                background-color: white
                margin-left: -15px
                margin-right: -15px
                border-bottom: 1px solid #dedede
                padding-bottom: 10px
                margin-top: 5px
                .navbar-nav
                    margin-left: 8px !important
                .register-button
                    margin-left: 15px
</style>