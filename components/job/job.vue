<script setup>
    import { content } from './data.js';

</script>
<template>
    <section class="job" id="job">
        <h2 class="job__title font-serif-style h1">опыт<br><span class="font-non-serif-style font-accent-style">раб<span class="font-serif-style">о</span>ты</span></h2>
        <div class="job__list">
            <article v-for="item in content" class="job__item p --m" :key="item.number">
                <div class="job__item-period job__item-point">
                    <span>
                       {{ item.period.start }}
                    </span>
                    <span>
                        {{ item.period.end }}
                    </span>
                </div>
                <div class="job__item-place job__item-point --gap-8">
                    <span>
                        {{ item.place.title }}
                    </span>
                    <span>
                        {{ item.place.address }}
                    </span>
                </div>
                <div class="job__item-position job__item-point --gap-8">
                    <span>
                        {{ item.position.title }}
                    </span>
                    <span>
                        {{ item.position.description }}
                    </span>
                </div>
            </article>
        </div>
    </section>
</template>
<style src="~/components/job/__job.css" lang="css"></style>