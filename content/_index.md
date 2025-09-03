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
      title: Get into the routine of showing up... for life
      text: Grow Just by Showing Up
      primary_action:
        text: Get Started
        url: https://www.meetup.com/spark-chance-improv/events/
        icon: rocket-launch
      announcement:
        text: "Now meeting once a week."
        link:
          text: "Join in"
          url: "https://www.meetup.com/spark-chance-improv/events/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: landing.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: features
    id: features
    content:
      title: What we offer
      text: Transform Through Play
      items:
        - name: Tailored Training for All Levels
          icon: magnifying-glass
          description: Whether you're a beginner exploring improv for fun or a seasoned clown sharpening your skills, Spark Chance offers customises our meetups for every skill level. From foundational techniques to structured scene work, we meet you where you are.
        - name: Fun vibes
          icon: bolt
          description: Experience the joy of improv in a welcoming, inclusive space. Our meetups are designed to spark laughter, creativity, and connection, making learning both impactful and unforgettable.
        - name: Reaccess Forgotten Potential
          icon: sparkless
          description: Improv’s playful exercises quietly dissolve self-doubt and fear, helping you break through personal barriers. Discover newfound confidence and creativity as you embrace spontaneity in a supportive, fun environment.
        - name: Personal Growth
          icon: star
          description: Build confidence, quick thinking, and emotional intelligence through improv. Our exercises, inspired by techniques like Viola Spolin’s, help you navigate life’s challenges with creativity and resilience.
        - name: Playful De-Stress with a Twist
          icon: code-bracket
          description: Our bold, fun-filled workshops turn stress into laughter with a touch of sass. Dive into improv’s quirky world and feel refreshed, no meditation required.
        - name: Unshakeable Strength Through Play
          icon: rectangle-group
          description: Develop the mental toughness to face life’s ups and downs through fun improv scenarios. You’ll master staying grounded and resourceful, ready for any situation with a smile.
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Bounce Back with Improv Smarts
          text: Learn to handle life’s tough moments with quick thinking and poise. Our dynamic workshops train you to stay calm and creative, no matter what challenges come your way.
          feature_icon: check
          features:
            - Resilience
            - Good humour
            - Relatability
          # Upload image to `assets/media/` and reference the filename here
          image: split.png
          button:
            text: Show up
            url: https://www.meetup.com/spark-chance-improv/events/
        - title: Grow Your Social Circle Through Play
          text: Make friends effortlessly
          feature_icon: bolt
          features:
            - Laugh and create 
            - Share silliness
            - Make connections
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Show up
            url: https://www.meetup.com/spark-chance-improv/events/
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Michele"
          role: ""
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Came back into the present like nothing else. Gone through a number of other art classes - writing and drawing - but nothing really lights the creative spark like improv. Spark Choice were very welcoming, and I'll be back again!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
