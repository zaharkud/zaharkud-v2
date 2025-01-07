<script>

</script>
<template>
    <section class="projects" id="portfolio">
        <h2 class="projects__title font-non-serif-style h1">порт-<br><span class="font-serif-style font-accent-style">фолио</span></h2>
        <div class="projects__content">
            <div class="projects__control">
                <div class="projects__control-bullet-list">
                    <div v-for="item in 4" class="projects__control-bullet-item">
                    </div>
                </div>
            </div>
            <div class="projects__slider">

            </div>
            <div class="projects__info p --m">
                <div class="projects__info-header">
                    <div class="projects__info-title">
                        ARLEZU
                    </div>
                    <div class="projects__info-year">
                        2019 г.
                    </div>
                </div>
                <div class="projects__info-main">
                    Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis tempora doloribus qui illo ex rem obcaecati necessitatibus ullam porro fugit?
                </div>
                <div class="projects__info-tech">
                    nuxt vue
                </div>
            </div>
        </div>
    </section>
</template>
<style src="~/components/projects/__projects.css" lang="css"></style>