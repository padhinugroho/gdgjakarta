<template>
    <div>
        <header id="header-page">
        <div class="container">
                <div class="header-page-group d-flex justify-content-center align-items-center">
                    <h1>Schedule</h1>
                </div>
            </div>
        </header>
        <Schedule/>
        <Divider/>
    </div>
</template>

<script>
import HeaderPage from '~/components/HeaderPage.vue'
import Schedule from '~/components/Schedule.vue'
import Divider from '~/components/FooterDivider.vue'

export default {
    components: {
        HeaderPage,
        Divider,
        Schedule
    }
}
</script>