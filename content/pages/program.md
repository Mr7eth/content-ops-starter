---
type: PageLayout
title: Program
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Programma del Corso
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: >
      Il corso è diviso in due sezioni: il programma Makers, per individui
      interessati allo sviluppo audiovisivo e il programma Attorə, per individui
      interessati al lavoro di improvvisazione attoriale.
    actions: []
    badge:
      type: Badge
      label: Mockumentary lab
      color: text-primary
      styles:
        self:
          textAlign: center
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Programma di massima
      color: text-dark
    subtitle: Subtitle goes here
    text: >+
      **Durata:** 7 giorni


      **Arrivo:** Lunedì 9 Settembre in Giornata


      Si inizia da Martedì 10 Settembre


      **Orario delle sessioni:**


      *   **Mattina:** 9:00 - 12:30


      *   **Pomeriggio:** 14:00 - 19:00


      #### Divisione dei Tutor:


      *   **Tutor "Makers" (Tecnici e Filmmaker):** Guida alla realizzazione
      dell'audiovisivo.


      *   **Tutor Attori:** Guida alle attività di improvvisazione,
      interpretazione del personaggio e performance.

    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
      - type: Link
        label: See Tutorials
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    media:
      type: ImageBlock
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
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
  - type: FeaturedPostsSection
    posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    actions: []
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic section with a video
      color: text-dark
      styles:
        self:
          textAlign: left
    subtitle: Section with a video subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/placeholder-video.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
  - type: GenericSection
    title:
      type: TitleBlock
      text: Social Media Management
      color: text-dark
    subtitle: Increase your reach
    text: >
      A service that helps businesses to manage their social media accounts and
      posts.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Business Consulting
      color: text-dark
    subtitle: Be in good company
    text: >
      A service that provides advice and guidance to startups and small
      businesses.
    actions:
      - type: Button
        label: Get started
        url: /
        icon: arrowRight
        iconPosition: right
        style: secondary
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: CarouselSection
    subtitle: This is a subtitle
    items:
      - type: FeaturedItem
        title: >-
          “A designer knows he has achieved perfection not when there is nothing
          left to add, but when there is nothing left to take away.”
        tagline: Testimonial 1
        subtitle: 'Maria Walters, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/person-placeholder-light.png
          altText: Maria Walters
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
      - type: FeaturedItem
        title: >-
          “Quote from some important person goes right here. I love using
          Netlify.”
        tagline: Testimonial 2
        subtitle: 'Jane Doe, Company'
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder-dark.png
          altText: Jane Doe
          styles:
            self:
              borderRadius: full
        actions: []
        colors: bg-dark-fg-light
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
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: List of features here
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: Featured items section subtitle
    items:
      - type: FeaturedItem
        title: Feature Item One
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature1.svg
          altText: Placholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Feature Item Two
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Follow the tutorial to build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
      - type: FeaturedItem
        title: Feature Item Three
        tagline: This is the tagline
        subtitle: This is the item subtitle
        text: |
          Learn from the tutorial and build your first awesome Netlify site.
        image:
          type: ImageBlock
          url: /images/abstract-feature3.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
    actions: []
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: /program
seo:
  type: Seo
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create
  socialImage: /images/main-hero.jpg
  metaTags: []
---