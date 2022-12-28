---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: about.avatar
  #   id: home
  #   content:
  #     # Choose a user profile to display (a folder name within `content/authors/`)
  #     username: admin
  #     text:
  #   design:
  #     background:
  #       color: black
  #       text_color_light: true
  #       image:
  #         # Add your image background to `assets/media/`.
  #         filename: space.jpg
  #         filters:
  #           brightness: 0.4
  #         size: cover
  #         position: center
  #         parallax: false
  #     css_class: d-flex fullscreen align-items-center

  - block: markdown
    id: home
    content:
      title: Gallery
      subtitle: ''
      text: test
    design:
      columns: '1'
      background:
        color: black
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: space.jpg
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
      css_class: d-flex fullscreen align-items-center
  # - block: markdown
  #   content:
  #     title: HomePage
  #     # subtitle: ''
  #     # To render inline or block math, wrap your LaTeX math with {{< math >}}$...${{< /math >}} or {{< math >}}$$...$${{< /math >}}
  #     text: [Home](https://universemodeling.com/)
  #   design:
  #     columns: '1'

---
