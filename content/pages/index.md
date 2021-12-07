---
title: Home
layout: PageLayout
sections:
  - type: HeroSection
    elementId: homepage-hero-1
    colors: colors-a
    title: "Your Starting Point To An Infinitely Scalable Site \U0001F680"
    text: "This starter includes a comprehensive component library that you can either use out of the box without having to code, or extend and add components if the code is strong with you \U0001F642\n"
    actions:
      - type: Button
        label: Sign up
        url: 'https://www.stackbit.com/'
        style: primary
        elementId: hero-main-button
    media:
      type: ImageBlock
      url: /images/box-small.png
      altText: Image alt text
      caption: Image caption
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-11
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - elementId: ''
    colors: colors-f
    title: Each section on this page is a component
    text: >
      You can add more components to the page by either pressing the + that
      appears on components' highlight frames, or through the left sidebar.
    actions:
      - type: Button
        label: Try Pressing the +s
        url: /
        style: primary
      - type: Link
        label: Read more
        url: /
        showIcon: true
        icon: arrowRight
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-20
          - mb-20
          - ml-20
          - mr-20
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    media:
      url: /images/Screen Shot 2021-12-03 at 12.10.37 AM.png
      altText: Where did everyone go?
      caption: Team meeting
      elementId: ''
      styles:
        self:
          opacity: 100
      type: ImageBlock
  - colors: colors-h
    elementId: ''
    images:
      - type: ImageBlock
        url: /images/apple.svg
        altText: Apple
        caption: Apple
      - type: ImageBlock
        url: /images/google-play.svg
        altText: Google Play
        caption: Google Play
      - type: ImageBlock
        url: /images/playstation.svg
        altText: PlayStation
        caption: PlayStation
      - type: ImageBlock
        url: /images/gatsby.svg
        altText: Gatsby
        caption: Gatsby
      - type: ImageBlock
        url: /images/xbox.svg
        altText: Xbox
        caption: Xbox
      - type: ImageBlock
        url: /images/skype.svg
        altText: Skype
        caption: Skype
      - type: ImageBlock
        url: /images/zcool.svg
        altText: ZCOOL
        caption: ZCOOL
    spacing: 3
    columns: 7
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
    imageSizePx: 240
    type: MediaGallerySection
    title: Try Deleting This Title Completely
  - colors: colors-h
    elementId: ''
    title: 'Feature Section Demo: Using Stackbit'
    subtitle: This section is highly versatile and has many configurations
    items:
      - type: FeaturedItem
        title: Faster
        text: >
          Stackbit makes you faster, if you're a developer unblocking your team
          or client, or if you're a creator that needs to ship an effective
          page.
        featuredImage:
          url: /images/faster.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
      - type: FeaturedItem
        title: Smarter
        text: >
          Work smarter leveraging a state-of-the-art component library and
          content models to future-proof your site.
        featuredImage:
          url: /images/smarter.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
      - type: FeaturedItem
        title: Focused
        text: >
          Developers can write components and automate workflows while site
          builders and focus on creating the right sites to deliver their
          messages across.
        featuredImage:
          url: /images/focused.svg
          altText: altText of the image
          caption: Caption of the image
          elementId: ''
          styles:
            self:
              opacity: 100
          type: ImageBlock
        styles:
          title:
            textAlign: center
          text:
            textAlign: center
    columns: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: FeaturedItemsSection
  - elementId: ''
    colors: colors-a
    title: Visually edit and style pages and components.
    text: >
      Our world-class visual editing experience is fast, intuitive, and
      powerful. WYSIWYG in-place editing, reusable components, layouts,
      variations, styling, media, and more. Everything you've come to expect
      from a modern visual site builder. Move fast without developer help or
      having to worry about breaking anything.
    media:
      type: ImageBlock
      url: /images/VIsually unlimited-7c7ce0ec.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-6
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderColor: border-primary
        borderWidth: 0
        borderStyle: solid
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-a
    title: Your site. Your code.
    text: "A Stackbit website is a git repo that you own. Every code commit is instantly reflected in the visual editor and since every visual edit is a git commit, git workflows and collaboration\_*just work*.\n"
    media:
      type: ImageBlock
      url: /images/project-diagram.png
      altText: Hero section image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-6
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
  - elementId: ''
    colors: colors-f
    testimonials:
      - quote: >
          “Stackbit is a visual editor for your site, regardless of the tech
          choices behind it - a rather amazing thing to see work.”
        name: Chris Coyier
        title: Happy customer
        image:
          type: ImageBlock
          url: /images/chris-coyier.png
          altText: Photo of Isabelle Parks
        styles:
          self:
            margin:
              - mt-0
              - mb-0
            flexDirection: row-reverse
          quote:
            textAlign: left
          name:
            textAlign: left
          title:
            textAlign: left
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: TestimonialsSection
  - elementId: ''
    variant: variant-b
    colors: colors-a
    posts:
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPostsSection
  - colors: colors-f
    elementId: ''
    title: Need Answers?
    items:
      - question: How it this different from what we have today?
        answer: >-
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
      - question: How it this different from what we have today?
        answer: >-
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
      - question: How it this different from what we have today?
        answer: >-
          At the office, working together is often a distruction, on remote, it
          could be motivation, At the office, working together is often a
          distruction, on remote, it could be motivation, At the office, working
          together is often a distruction, on remote, it could be motivation
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
    type: FaqSection
  - type: ContactSection
    colors: colors-f
    title: Get early access
    text: >
      Sign up your team today to be the first to try out our new product to
      increae your team’s productivity
    form:
      type: FormBlock
      elementId: contact-form
      destination: ''
      action: /.netlify/functions/submission_created
      fields:
        - name: email
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
      submitLabel: Sign Up
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-36
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      text:
        textAlign: left
---
