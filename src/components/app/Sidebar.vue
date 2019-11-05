<template>
    <ul class="sidenav app-sidenav" :class="{open: value}">

        <router-link
            v-for="link in links"
            :key="link.url"
            tag="li"
            active-class="active"
            :to="link.url"
            :exact="link.exact">
        <a href="#" class="pointer">{{link.title}}</a>
        </router-link>
    </ul>
</template>

<script>
export default {
    props: ['value'],
    data: () => ({
        links: [
        {title: 'Профиль', url: '/profile'},
        {title: 'Пользователи', url: '/', exact: true},
        {title: 'Товары', url: '/goods'},
        {title: 'Планирование', url: '/planning'},
        {title: 'Новая запись', url: '/record'},
        {title: 'Категории', url: '/categories'}
        ]
    })
}
</script>



