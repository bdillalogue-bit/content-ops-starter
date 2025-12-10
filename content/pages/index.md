
---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Quality Remodeling & Construction You Can Trust
      color: text-dark
      type: TitleBlock
    subtitle: Serving Dayton, Huber Heights, Fairborn & surrounding areas
    text: >
      Marriott Construction is a family-owned remodeling and construction company
      proudly serving the greater Dayton region. From small repairs to complete home
      transformations, we handle every project with craftsmanship, honesty, and
      attention to detail. Your home is your biggest investment — let us help you
      protect and improve it.
    actions:
      - label: Get Free Estimate
        altText: ''
        url: '#contact'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
      - label: Make a Payment
        altText: Secure online payment
        url: '#payment'
        showIcon: true
        icon: creditCard
        iconPosition: right
        style: secondary
        type: Link
    media:
      url: /images/construction-hero.jpg
      altText: Marriott Construction – Professional home remodeling in Dayton, OH
      elementId: ''
      type: ImageBlock
    badge:
      label: Licensed • Bonded • Insured
      color: text-primary
      type: Badge
    elementId: hero-section
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
  - type: FeaturedItemsSection
    title:
      text: Our Services
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: One call does it all – interior & exterior residential remodeling
    items:
      - type: FeaturedItem
        title: Windows & Doors
        subtitle: Replacement & Installation
        text: Energy-efficient windows, entry doors, patio doors, and storm doors.
        image:
          url: /images/icon-windows.svg
          altText: Windows icon
          type: ImageBlock
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            textAlign: center
      - type: FeaturedItem
        title: Siding, Soffit & Gutters
        subtitle: Exterior Upgrades
        text: Vinyl, fiber cement, aluminum siding, seamless gutters, soffit & fascia.
        image:
          url: /images/icon-siding.svg
          altText: Siding icon
          type: ImageBlock
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            textAlign: center
      - type: FeaturedItem
        title: Decks & Room Additions
        subtitle: Expand Your Living Space
        text: Custom decks, porches, sunrooms, garage additions, and full room build-outs.
        image:
          url: /images/icon-deck.svg
          altText: Deck icon
          type: ImageBlock
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            textAlign: center
      - type: FeaturedItem
        title: Interior Remodeling
        subtitle: Kitchens, Baths & More
        text: Drywall, painting, flooring, trim, lighting, full kitchen & bathroom remodels.
        image:
          url: /images/icon-interior.svg
          altText: Interior remodeling icon
          type: ImageBlock
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            textAlign: center
    variant: four-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
  - subtitle: Trusted by homeowners throughout the Miami Valley
    images:
      - url: /images/logo-dayton.svg
        altText: Dayton OH
        type: ImageBlock
      - url: /images/logo-huberheights.svg
        altText: Huber Heights OH
        type: ImageBlock
      - url: /images/logo-fairborn.svg
        altText: Fairborn OH
        type: ImageBlock
      - url: /images/logo-beavercreek.svg
        altText: Beavercreek OH
        type: ImageBlock
      - url: /images/logo-kettering.svg
        altText: Kettering OH
        type: ImageBlock
      - url: /images/logo-vandalia.svg
        altText: Vandalia OH
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
    type: ImageGallerySection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pb-12
    type: DividerSection
  - type: GenericSection
    title:
      text: See Why Homeowners Choose Marriott Construction
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Real projects, real results
    media:
      title: Before & After Transformations
      url: /images/remodeling-showcase.mp4
      autoplay: true
      loop: true
      muted: true
      controls: true
      aspectRatio: '16:9'
      type: VideoBlock
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
  - type: CarouselSection
    subtitle: What our customers are saying
    items:
      - title: "They completely transformed our outdated kitchen into our dream space!"
        subtitle: Sarah M. – Huber Heights
        text: Professional crew, clean worksite, finished on time and on budget. Highly recommend!
        image:
          url: /images/review-1.jpg
          altText: Customer photo
          type: ImageBlock
        type: FeaturedItem
      - title: "Best decision we made was hiring Marriott for our new deck and siding."
        subtitle: Mike D. – Fairborn
        text: Attention to detail was incredible. The house looks brand new!
        image:
          url: /images/review-2.jpg
          altText: Customer photo
          type: ImageBlock
        type: FeaturedItem
      - title: "Replaced all windows and added a sunroom – outstanding workmanship."
        subtitle: Linda T. – Dayton
        text: Courteous, knowledgeable, and fairly priced. Will use them for every future project.
        image:
          url: /images/review-3.jpg
          altText: Customer photo
          type: ImageBlock
        type: FeaturedItem
    variant: next-prev-nav
    colors: bg-light-fg-dark
    styles:
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      text: Ready to Start Your Project?
      color: text-dark
      type: TitleBlock
    subtitle: Get your free, no-obligation estimate today
    text: Serving Dayton • Huber Heights • Fairborn • Beavercreek • Kettering • Vandalia and all surrounding communities.
    actions:
      - label: Request Quote
        url: '#contact'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    colors: bg-neutral-fg-light
    styles:
      self:
        alignItems: center
        padding:
          - pt-16
          - pb-16
  - type: GenericSection
    elementId: payment
    title:
      text: Make a Secure Payment
      color: text-dark
      type: TitleBlock
    text: >
      <script type="text/javascript" src="https://pci.jotform.com/jsform/253428759521060"></script>
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pb-12
          - pl-8
          - pr-8
  - type: GenericSection
    elementId: contact
    title:
      text: Contact Marriott Construction
      color: text-dark
      type: TitleBlock
    subtitle: We typically respond the same day
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: phone
          label: Phone
          hideLabel: true
          placeholder: Your phone number
          isRequired: true
          width: full
          type: TelFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email (optional)
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell us about your project...
          width: full
          type: TextareaFormControl
      elementId: contact-form
      type: FormBlock
      submitButton:
        label: Send Message
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        type: SubmitButtonFormControl
    badge:
      label: Free Estimates
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
seo:
  metaTitle: Marriott Construction | Home Remodeling Contractor Dayton OH
  metaDescription: Professional residential remodeling serving Dayton, Huber Heights, Fairborn & surrounding areas. Windows, siding, decks, room additions, kitchens, baths & more.
  socialImage: /images/construction-hero.jpg
  type: Seo
type: PageLayout
---
</DOCUMENT>
