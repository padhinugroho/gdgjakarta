<template>
    <div>
        <header id="header-page">
            <div class="container">
                <div class="header-page-group d-flex justify-content-center align-items-center">
                    <h1>Teams</h1>
                </div>
            </div>
        </header>
        <Teams/>
        <Divider/>
    </div>
</template>

<script>
import HeaderPage from '~/components/HeaderPage.vue'
import Teams from '~/components/Teams.vue'
import Divider from '~/components/FooterDivider.vue'

export default {
    components: {
        HeaderPage,
        Divider,
        Teams
    }
}
</script>