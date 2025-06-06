---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
    name: 'PakePlus'
    text: 'Turn web into desktop & mobile apps'
    tagline: Package web/Vue/React projects into desktop/mobile apps in minutes
    image:
        src: ../pplogo.png
        alt: PakePlus
    actions:
        - theme: brand
          text: Download
          link: /en/download/
        - theme: brand
          text: WebBeta
          link: https://pakeplus.netlify.app/
        - theme: alt
          text: Guide
          link: /en/guide/

features:
    - title: Open Source
      details: PakePlus is open source and you can find its source code on GitHub
      icon: 🐙
    - title: Cross Platform
      details: Windows/macOS/Linux/Android/iOS are all supported
      icon: 💻
    - title: Small Size
      details: The size is smaller than Electron package by about 20 times (less than 5M!)
      icon: 🚀
    - title: Mobile Support
      details: Use native framework to package Android and iOS APP, which is smaller and faster
      icon: 📲
    - title: Easy to Use
      details: UI is simple, no need to install any development environment, save time and save money
      icon: 📦
    - title: Simultaneous Compilation
      details: Just minutes, one click to compile multiple platforms, no environment and time anxiety
      icon: 🧘‍♀️
    - title: Internationalization
      details: Support internationalization, friendly to global users
      icon: 🌍
    - title: Customization
      details: You can customize the application icon, application name, and inject JavaScript code
      icon: 🎨
    - title: Static File Support
      details: Support packaging static html files or Vue/React projects compiled dist
      icon: 🍀
    - title: Debug Support
      details: Support debug mode, whether in preview or release, you can find bugs and eliminate bugs
      icon: 🐞
    - title: Data Security
      details: PakePlus will not upload any data, all data is stored on your computer
      icon: 🔒
    - title: Technical Support
      details: If you encounter any problems during use, you can chat with us
      icon: 💬
---

<div :class="$style.buildInfo">
    <span :class="$style.buildTime">Built Time：{{ data.buildTime }}</span>
</div>

<script setup>
import { data } from '../static/js/buildtime.data.ts'
</script>

<style module>

.buildInfo{
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    margin-top: 20px;
}

.buildTime{
    color: gray;
}
</style>
