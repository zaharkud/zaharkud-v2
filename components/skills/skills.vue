<script>

</script>
<template>
    <section class="skills" id="skills">
        <h2 class="skills__title font-non-serif-style h1">навы<span class="font-serif-style font-accent-style">ки</span></h2>
        <div class="skills__content">
            <div class="skills__column --first flex --direction-column --gap-48">
                <div class="skills__column-block flex --direction-column --gap-16">
                    <p class="skills__column-text p --m">
                        Фреймворки<br> и библиотеки
                    </p>
                    <div class="skills__circle-thumb">
                        <div class="skills__circle">
                            <p class="skills__circle-text p --xxl">
                                vue<br><span class="p --l">+ nuxt</span>
                            </p>
                        </div>
                    </div>
                </div>
                <div class="skills__column-block flex --direction-column --gap-8">
                    <p class="skills__column-text p --m">
                        Также работал с
                    </p>
                    <ul class="skills__column-list p --xl">
                        <li>react</li>
                    </ul>
                </div>
            </div>
            <div class="skills__column --second">
                <div class="skills__column-block flex --direction-column --gap-16">
                    <p class="skills__column-text p --m">
                        Отлично владею
                    </p>
                    <ul class="skills__column-list p --xl">
                        <li>html</li>
                        <li>css</li>
                        <li>javascript</li>
                    </ul>
                </div>
                <div class="skills__column-deco mt-48">
                    <nuxt-icon class="skills__star-deco" name="star-deco" />
                </div>
            </div>
            <div class="skills__column --third flex --direction-column --gap-112">
                <div class="skills__column-block flex --direction-column --gap-16">
                    <p class="skills__column-text p --m">
                        Рисовал дизайны<br> и графику в
                    </p>
                    <ul class="skills__column-list p --xl">
                        <li>figma</li>
                        <li>photo-<br>shop</li>
                    </ul>
                </div>
                <div class="skills__column-block flex --direction-column --gap-16">
                    <p class="skills__column-text p --m">
                        Иностранные языки
                    </p>
                    <ul class="skills__column-list p --xl">
                        <li>english B2</li>
                        <li>espanol B1</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>
<style src="~/components/skills/__skills.css" lang="css"></style>