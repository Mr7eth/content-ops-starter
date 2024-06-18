---
title: Chi Siamo
slug: chi_siamo
sections:
  - title:
      text: Conosci il nostro team
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: >
      Il progetto è condotto da due professionisti: per l'audiovisivo, il
      filmmaker Mattia Mura, che accompagnerà i makers nel percorso di
      realizzazione del documentario, dalle prime riprese fino al montaggio
      finale, mentre per la recitazione Leonarda Saffi, che condurrà il team di
      attori/attrici attraverso l'improvvisazione e la creazione dei personaggi.
    actions: []
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: ''
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person2.json
      - content/data/person1.json
      - content/data/place1.json
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
      subtitle:
        textAlign: center
    type: FeaturedPeopleSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
