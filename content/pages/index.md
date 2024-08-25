---
title: Home
slug: /
sections:
  - type: CarouselSection
    subtitle: About
    items:
      - type: FeaturedItem
        title: Raul-Alexandru Gorgan
        tagline: ''
        subtitle: >-
          I am a Full-Stack Software Engineer and researcher at Technical
          University of Cluj-Napoca. As a Computer Science graduate, currently
          following a Master in Artificial Intelligence, I combine theoretical
          knowledge with practical skills. I have an ambitious, responsible
          nature and always tend to develop personally and professionally. I am
          highly motivated to learn, to face challenges and I am open to new
          experiences in order to increase my expertise.
        text: ''
        image:
          type: ImageBlock
          url: /images/Gorgan Raul - Alexandru_MG_4869.jpg
          altText: Raul-Alexandru Gorgan
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        padding:
          - pt-5
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: Featured posts
      color: text-dark
      styles:
        self:
          textAlign: center
    posts:
      - content/pages/blog/five-tips-for-starting-a-startup.md
      - content/pages/blog/what-is-a-design-system.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: big-list
    colors: bg-light-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
  - type: ImageGallerySection
    subtitle: Skills
    images:
      - type: ImageBlock
        url: /images/empathy-logo.svg
        altText: Empathy logo
        elementId: ''
      - type: ImageBlock
        url: /images/wellster-logo.svg
        altText: Wellster logo
        elementId: ''
      - type: ImageBlock
        url: /images/vise-logo.svg
        altText: Vise logo
        elementId: ''
      - type: ImageBlock
        url: /images/telus-logo.svg
        altText: Telus logo
        elementId: ''
      - type: ImageBlock
        url: /images/contenful-logo.svg
        altText: Contentful logo
        elementId: ''
      - type: ImageBlock
        url: /images/sanity-logo.svg
        altText: Sanity logo
        elementId: ''
      - type: ImageBlock
        url: /images/rangle-logo.svg
        altText: Rangle logo
        elementId: ''
    elementId: ''
    motion: static
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mt-0
          - ml-0
          - mb-0
          - mr-0
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
