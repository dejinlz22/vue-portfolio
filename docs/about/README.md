---
pageClass: about-page
description: 'Personal Background'
avatar: /profile.jpg
head: 'JINNY LUZ DEJITO'
info: 'Student at CORDOVA PUBLIC COLLEGE School'
interests: 'Interests: HTML, CSS , JAVASCRIPT.'
socials:
- title: github
  link: https://github.com/dejinlz22
- title: instagram
  link: https://www.instagram.com
- title: email
  link: 'jindej21@gmail.com'
actions:
- text: Projects
  link: /projects/
- text: Blog
  link: https://github.com/dejinlz22
- text: CV
  link: /article/
footer: Made with ♥ by Jinny. Powered by VuePress
---

<AboutCard :frontmatter="$page.frontmatter" >

Hello! I'm JINNY DEJITO, a passionate and dedicated individual with a strong background in my School. I thrive in dynamic environments and enjoy taking on new challenges that push me to expand my skills and knowledge.

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>