---
title: Careers
slug: careers
sections:
  - title:
      text: AI teams that work closely together
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: >
      The power of collaboration is in artificial intelligence development. By
      fostering open communication, shared expertise, and coordinated
      problem-solving, these teams are able to accelerate innovation, tackle
      complex challenges, and create more effective AI solutions. This approach
      emphasizes the importance of teamwork, diverse skill sets, and a unified
      vision in achieving breakthrough advancements in AI technology.
    actions:
      - label: See open positions below
        url: /careers
        icon: arrowRight
        iconPosition: right
        style: primary
        type: Button
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
      text: Meet the team
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    people:
      - content/data/person1.json
      - content/data/person2.json
      - content/data/person3.json
      - content/data/person4.json
      - content/data/person5.json
      - content/data/person6.json
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
      text: Open positions
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Subtitle goes here
    items:
      - title: Account Executive
        subtitle: Sales
        text: >
          Drive client relationships and sales strategies, helping businesses
          harness the power of AI solutions.
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
      - title: AI Engineer
        subtitle: Artificial Intelligence Engineering
        text: >
          Design and develop cutting-edge AI models, optimizing algorithms and
          systems for real-world applications.
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
      - title: Senior Software Engineer
        subtitle: Engineering
        text: >
          Lead software development efforts, building scalable and efficient
          AI-driven solutions in a fast-paced environment.
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
    actions:
      - label: Apply now
        url: /
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
type: PageLayout
---
