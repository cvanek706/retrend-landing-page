---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Give Your Retail A Mind.
      text: Leverage AI to Gain New Insights From Real Customer Activity, Make Category Management Effortless, and Maximize Exposure.
      primary_action:
        text: Get Started
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Read the docs
        url: https://docs.hugoblox.com
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        video:
          # Add your image background to `assets/media/`.
          filename: bg.mp4
  - block: features
    id: features
    content:
      title: Features
      text: Discover how Retrend AI can transform your business
      items:
        - name: GeorgeBot
          icon: bolt
          description: Our real-time conversational chatbot integrates directly with your inventory, providing an excellent, automated, and fully observable customer experience.
        - name: Re-Category
          icon: magnifying-glass
          description: Category management headaches are a thing of the past. Automate your categories with zero loss of control or accuracy. Leverage robust, lightning-fast search algorithms.
        - name: Kiosks
          icon: sparkles
          description: Employ GeorgeBot as both software and hardware on a kiosk in your store today, with cutting-edge semantic turn-detection, noise filtering, and acoustic echo cancellation.
        - name: Customizable. Easy.
          icon: star
          description: Take full control of the retail experience. Choose which products GeorgeBot should tell customers about and maximize exposure.
        - name: Analytics
          icon: rectangle-group
          description: Make informed decisions in ways previously impossible, backed by meaningful insights with intent analysis, product engagement stats, and so much more.
        - name: ...And Much More
          icon: code-bracket
          description: Open up new possibilities to grow your business in new ways.
  - block: hero   # or ‘hero’ if you want the big banner
    id: demo
    content:
      title: Launch demo
      text: |
        {{< youtube D2vj0WcvH5c >}}
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Transform your retail business
          text: As easy as 1, 2, 3!
          feature_icon: check
          features:
            - Set up inventory integration with Retrend AI
            - Employ your very first GeorgeBot Virtual Retail Assistant
            - Gain new insights about your customers
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Get Started
            url: https://hugoblox.com/templates/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  # - block: cta-card
  #   content:
  #     title: Build your future-proof website
  #     text: As easy as 1, 2, 3!
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---