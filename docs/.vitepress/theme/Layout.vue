<template>
    <header>
        <div class="headshot-column">
            <img class="headshot" src="/assets/tim-headshot-web.jpg">
            <div class="icons">
                <a class="icon icon-linkedin" href="https://www.linkedin.com/in/tim-growney/" target="_blank"/>
                <a class="icon icon-twitter" href="https://twitter.com/realTimGrowney" target="_blank"/>
            </div>
        </div>
        <div>
            <h2>{{$site.title}}</h2>
            <div class="description">{{$site.description}}</div>
        </div>
    </header>
    <Content />
</template>

<style lang="sass" scoped>
  @import './layout.scss'
</style>