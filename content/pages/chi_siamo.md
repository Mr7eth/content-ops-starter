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
      attori attraverso l'improvvisazione e la creazione dei personaggi.
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
      - content/data/person1.json
      - content/data/person2.json
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
  - title:
      text: Partecipa
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Un identikit dei partecipanti
    items:
      - title: Sono un'attrice/attore
        subtitle: Sales
        text: >
          Se sei un aspirante attrice o attore, se frequenti un'accademia di
          recitazione o un corso di teatro, se anche solo in passato hai avuto
          esperienza nel campo della recitazione questa esperienza è adatta a
          te! In particolar modo se ti piace trascorrere del tempo in compagnia,
          essere parte di un gruppo di lavoro e hai uno spirito ironico!
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
      - title: Sono un filmmaker/videomaker
        subtitle: Marketing
        text: >
          Se hai una minima esperienza di settore, che tu sia autodidatta, stia
          frequentando una scuola o conosca almeno i fondamenti base del
          videomaking, questo progetto è ideale per te. Ci spingeremo fuori
          dalla confort zone di un corso base per sviluppare tecniche di
          intervista, illuminazione e regia in circostanze ai limiti del
          controllo di un set, per cui è importante avere almeno una base di
          esperienza preliminare. Durante il corso, proverai un po' di tutto per
          cui è anche importante essere pronti a mettersi in gioco in più ruoli
          e avere uno spirito collaborativo. Se ti piace fare squadra,
          sperimentare nuovi progetti e apprezzi l'ironia, questo workshop è
          perfetto per te!
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
        type: FeaturedItem
    actions:
      - label: Iscriviti ora
        url: /Contatti
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---