---
title: ""
date: 2025-07-26
type: landing

design:
  spacing: "2rem"

sections:
  - block: hero
    content:
      title: West African Coastal Flooding Early warning System
      text: Developing a science-based platform to forecast extreme coastal events and support disaster risk monitoring in the Gulf of Guinea
      primary_action:
        text: "Learn More"
        url: "#about"
        icon: rocket-launch
        is_scrolly: true
      announcement:
        text: Building an Coastal Flooding Early Warning System for the Gulf of Guinea
        link:
          text: "Read More"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`. bg-triangles.svg
          filename: tidal_ocean.jpg
          filters:
            brightness: 0.5
  - block: markdown
    content:
      title: About the Project
      subtitle: About the West African Coast Flooding Early Warning System
      text: |-
        <p style="text-align:justify;">The <b>West African Coast Inundation Early Warning System</b>is an independent research initiative that was launched in early 2025 with a view to developing long-term forecasting tools for extreme coastal events in the Gulf of Guinea.</p>
        <p style="text-align:justify;">Our objective is to establish a long-term, data-driven flood forecasting and alerting system for stakeholders in the Gulf of Guinea. We provide actionable information for disaster risk management across coastal West Africa by using satellite data, ocean modelling and statistical thresholds.</p>
        <p style="text-align:justify;">From statistical modelling of historical events to real-time analysis of tides, wave action and sea level anomalies, this project aims to offer actionable insights to manage and prevent the impact of coastal flooding in the context of climate change.</p>
        <p style="text-align:justify;">Should you wish to discuss potential collaborative opportunities, please do not hesitate to contact us at <a href="egeodegeod@gmail.com">egeodegeod@gmail.com</a></p>
    
    design:
      columns: '1'
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: How It works
      text: 
      items:
        - name: Data Driven threshold Analysis
          icon: chart-bar
          description: We employ statistical methods to analyse historical sea conditions, thereby identifying risk thresholds for flooding events.
        - name: Integrated Ocean Modelling
          icon: code-bracket-square
          description: Our approach involves the integration of data from Copernicus Marine Services, encompassing wave information and sea level anomaly data, in conjunction with the FES Tide Model to derive comprehensive estimates of total water levels.
        - name: Python & R-Based Models
          icon: python
          description: Our forecasting systems are developed using Python and R, ensuring both flexibility and scientific reproducibility.
        - name: Regional Forecasting
          icon: map-pin
          description: Pilot studies are conducted on Ghana, Benin, Togo, Ivory Coast, Nigeria and Cameroon, with the objective of offering region-specific insights.

  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Who It's For
          text: This system is being constructed to serve 
          feature_icon: check
          features:
            - Coastal communities
            - Local and regional governments
            - Environmental agencies
            - NGOs and development groups
            - Schools and educational institutions
              <br>
              <p style="text-align:justify;"><b> Our objective is to minimise vulnerabilities throughout society by making information regarding data and risk more accessible to a wider range of individuals.</b></p>
          image: build-website.png
          button:
            text: "Get Started"
            url: ""
        - title: Promoting Coastal Resilience
          text: In addition to modelling and data collection, the project encompasses a range of engagement and knowledge-sharing activities, including
          feature_icon: bolt
          features:
            - Local outreach campaigns
            - On-site workshops and training
            - Educational materials for coastal schools and organizations
              <br>
              <p style="text-align:justify;"><b>The objective of these programmes is to enhance preparedness and raise awareness of coastal hazards among affected communities.</b></p>
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: ""
            url: ""
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      title: The objective of the initiative is twofold firstly, to raise awareness of coastal flooding, and secondly, to promote environmental resilience.
      text: Drawing on expertise in geospatial data, ocean modelling, and data science, the project combines open-access tools such as Copernicus Marine Services,Google Earth Engine, and Sentinel imagery to support equitable access to coastal risk information.
      button:
        text: "Learn More"
        url: ""
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
