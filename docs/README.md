---
pageClass: home-page
# some data for the components

name: JINNY LUZ G. DEJITO
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/dejinlz22
  - title: instagram
    icon: "/icons/instagram-mono.svg"
    link: https://www.instagram.com

cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: Student at CORDOVA PUBLIC COLLEGE
email: jindejito21@gmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Former student at CORDOVA PUBLIC COLLEGE. know how to create website using html, css and javascript.

## Education & Experiences

- **CORDOVA PUBLIC COLLEGE** <br/>
   2020-2024


## Projects


[→ Full list](/projects/)

<ProjectCard image="/projects/1.png" hideBorder=true>

  

</ProjectCard>

<ProjectCard hideBorder=true>


</ProjectCard>




<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
