---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Building Dayton’s Future, One Project at a Time
      color: text-dark
      type: TitleBlock
    subtitle: Marriott Construction – Dayton, Ohio
    text: >
      Marriott Construction is a full-service general contractor proudly based in Dayton, Ohio. With decades of local experience, we deliver high-quality commercial and residential projects on time and on budget.
    actions:
      - label: Get a Quote
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: View Our Work
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/main-hero.svg
      altText: Marriott Construction – Dayton, Ohio
      elementId: ''
      type: ImageBlock
    badge:
      label: Trusted in Dayton Since 1995
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16

  - type: FeaturedItemsSection
    title:
      text: Why Choose Marriott Construction
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Local expertise. Proven results.
    items:
      - type: FeaturedItem
        title: 500+
        subtitle: Projects Completed
        text: >-
          Over 500 successful commercial and residential projects across the Greater Dayton area.
        image:
          type: ImageBlock
          altText: Projects icon
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - type: FeaturedItem
        title: 30+
        subtitle: Years Experience
        text: >-
          Three decades serving Dayton families and businesses with pride and craftsmanship.
        image:
          type: ImageBlock
          altText: Experience icon
          elementId: ''
          url: /images/icon2.svg
      - type: FeaturedItem
        title: 100%
        subtitle: Client Satisfaction
        text: >-
          Committed to quality workmanship and delivering beyond expectations.
        image:
          type: ImageBlock
          altText: Satisfaction icon
          elementId: ''
          url: /images/icon3.svg
    actions:
      - label: Request Consultation
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    badge:
      label: Dayton’s Trusted Builder
      color: text-primary
      type: Badge
    variant: three-col-grid
    colors: bg-neutral-fg-dark

  - subtitle: Trusted by Dayton-area businesses and homeowners
    images:
      - url: /images/empathy-logo.svg
        altText: Client logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Client 2
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Client 3
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Client 4
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Client 5
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Client 6
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Client 7
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    type: ImageGallerySection

  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: