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
      title: Nordic Personalization Workshop
      text: September 16-17, Gothenburg, Sweden
      primary_action:
        text: Register
        url: https://forms.gle/frnriYnqTLG21Wzg6
        icon: rocket-launch
      #secondary_action:
      #  text: Read the docs
      #  url: https://docs.hugoblox.com
      #announcement:
      #  text: "Announcing the release of version 1."
      #  link:
      #    text: "Read more"
      #    url: "/blog/"
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
          filename: bg-triangles.svg
          filters:
            brightness: 0.4
  - block: stats
    content:
      items:
        - statistic: "R&D"
          description: |
            participants
        - statistic: "Nordic"
          description: |
            perspective on  
             personalization
        - statistic: "Two days"
          description: |
            of talks, discussions  
            and workshops
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: about
    content:
      title: The Nordic Personalisation Workshop
      text: We invite all researchers and practitioners in the Nordics to the second Nordic Personalisation Workshop at the Wallenberg Conference Center, Gothenburg. We aim on two days full of talks and discussions on ethics, responsibility in personalisation and recommender systems. There will also be plenty of time to meet peers both from industry and research and exchange ideas during the conference during coffee breaks, lunch and after-workshop drinks. 
  - block: cta-image-paragraph
    id: why
    content:
      items:
        - title: What to expect
          text: "**T**echnological advancements have transformed media consumption into an omnipresent and decentralized activity.  
          Social media, in particular, has become a crucial channel for media's constant accessibility. However, the sheer volume of information has made it increasingly difficult for users to manage their media intake. Recommender systems, a branch of Artificial Intelligence (AI), have become essential in helping users sift through this deluge. These platforms utilize AI to filter content, aiming to match it with the user's preferences, often unbeknownst to them.  <br>  <br>  

          **A**I thus enables media providers to offer personalized experiences by discerning user preferences.  
          Despite AI's clear benefits — such as aiding users in discovering relevant content and managing the influx of information — its potential adverse effects cannot be ignored. AI systems have the propensity to reinforce existing biases, leading to skewed and inequitable recommendations. Such tendencies have brought algorithmic discrimination to the forefront of public attention. This term refers to the biased treatment of individuals or groups based on attributes like gender, age, or ethnicity. <br> <br>
          "
          # Upload image to `assets/media/` and reference the filename here
          image: music.jpg
          
        - title: 
          text: "**O**ther negative consequences of media recommender systems include the creation of filter bubbles and echo chambers, which restrict users' exposure to a variety of viewpoints. Excessive personalization by algorithms can trap users within a narrow media spectrum, potentially fostering polarized content ecosystems.<br> <br>

          **T**he absence of editorial oversight, especially on social media platforms, raises the risk of misinformation propagation.<br> <br>

          **W**hile algorithms are not inherently designed to promote false information, they play a significant role in its distribution, especially as they tend to favor content that gains popularity, thus reflecting a 'popularity bias'.<br> <br>

          **D**eveloping responsible and equitable algorithms presents a considerable challenge. It is vital to foster a collective understanding of various algorithmic methods and their societal implications. Our 2nd Nordic Personalisation Workshop seeks to tackle these issues. The two day event will be held this year at Wallenberg Conference Center, Gothenburg (last year in Oslo)."
          # Upload image to `assets/media/` and reference the filename here
          image: news.png
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: call
    content:
      content:
      items:
        - title: Call for contributions
          text: "<p>We invite all researchers and practitioners in the Nordics (and elsewhere) to submit their latest work on personalisation and recommender systems to the 2nd Nordic Personalisation Workshop in Gothenburg (September 16-17) as a talk or a poster. Talks and posters can focus on recent research results (including significant work-in-progress), applications and use cases of personalization and recommender systems, and directions of future research.<br><br></p>

          <p>To present your work at the workshop, submit an abstract of your work and select what type of presentation you prefer. The abstract must be in plain text and no longer than 500 words, not including bibliographic references. Please submit your abstract</p>

            Talks will be allotted 10 minutes of presentation time during the workshop, while posters will be given a one-minute slot in a poster madness session and presented in a poster session. Please submit your contribution abstract <b><a href=https://forms.gle/RYhM2Lp37CTFujHr5>here</a></b>.<br><br>
          "
          button:
            text: Submit
            url: https://forms.gle/RYhM2Lp37CTFujHr5
          image: poster.png

    design:
      # Section background color (CSS class)
      css_class: "bg-white-100 dark:bg-white-900"
  - block: features
    id: venue
    content:
      title: Venue
      text: 'The workshop will be held at the Wallberg Conference Center in Gothenburg. To get to the venue by public transport, take a tram or bus to the stop <a href="https://maps.app.goo.gl/a4WrMppwsv9gRf8KA">Medicinaregatan</a> and walk along Medicinaregatan to the conference center. If you are taking public transport, simply tap your credit/debit card on the ticket machine to pay for your fare. ** 
            <div style="display: flex; justify-content: center;">
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1673.2712752315367!2d11.958097000722194!3d57.68782722705151!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x464ff313c630b7af%3A0x861010a67293672b!2sKonferenscentrum%20Wallenberg!5e0!3m2!1ssv!2sse!4v1718142321909!5m2!1ssv!2sse" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>'
     
---
