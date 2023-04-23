<script setup>
import HomeBodyItem from './HomeBodyItem.vue'
</script>

<template>
    <ul class="article-list">
        <li >
            <HomeBodyItem>
                <template #heading>
                    <a class="article-title" href="">
                        TitleTitleTitle
                    </a>
                </template>
                <template #description>
                    <a class="article-description" href="">
                        Vue’s official documentation provides you with all information you need to get started. Vue’s official documentation provides you with all information you need to get started.
                    </a>
                </template>
                <template #info>
                    <span>2023-04-23</span>
                    <span class="article-list-divider">-</span>
                    <a href="https://vuejs.org/">#Vue</a> <a href="https://vuejs.org/">#Documentation</a>
                </template>
            </HomeBodyItem>
        </li>
        <li>
            <HomeBodyItem>
                <template #heading>
                    <a class="article-title" href="">
                        TitleTitleTitle
                    </a>
                </template>
                <template #description>
                    <a class="article-description" href="">
                        Vue’s official documentation provides you with all information you need to get started. Vue’s official documentation provides you with all information you need to get started.
                    </a>
                </template>
                <template #info>
                    <span>2023-04-23</span>
                    <span class="article-list-divider">-</span>
                    <a href="https://vuejs.org/">#Vue</a> <a href="https://vuejs.org/">#Documentation</a>
                </template>
            </HomeBodyItem>
        </li>
    </ul>
</template>

<style scoped>
.article-list-divider {
    margin: 0 0.5rem;
}
.article-title, .article-description {
    color: #000;
}
.article-list li {
    position: relative;
    display: block;
    padding: 50px 0;
    border-bottom: 1px solid #ebeaea;
}
</style>