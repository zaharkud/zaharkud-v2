<script setup>
    import { content } from './data.js';
    console.log(content)
</script>
<template>
    <section class="aside-menu">
            <!-- <div class="first-screen__box">
                <div class="box"></div>
            </div> -->
            <div class="aside-menu__content">
                <div v-for="(item, key) in content" class="aside-menu__nav p --xl" :key="key">
                    <a class="aside-menu__link" :href="'#' + item.link" v-html="item.title"></a>
                </div>
            </div>
    </section>
</template>
<style src="~/components/aside-menu/__aside-menu.css" lang="css"></style>