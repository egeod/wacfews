---
title: ""
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: hero
    content:
      title: Coastal Flood Awareness for West Africa
      text: Developing a science-based early warning system to forecast extreme coastal events and support disaster risk monitoring in the Gulf of Guinea
      primary_action:
        text: Learn More
        url: #https://hugoblox.com/templates/
        icon: rocket-launch
      announcement:
        text: Building an Coastal Flooding Early Warning System for the Gulf of Guinea
        link:
          text: #"Read more"
          url: #"/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`. bg-triangles.svg
          filename: tidal_ocean.jpg
          filters:
          filters:
            brightness: 0.5
  - block: markdown
    content:
      title: 'About the Project'
      subtitle: 'About the West African Coast Flooding Early Warning System'
      text: |-
        The *West African Coast Inundation Early Warning System* is an independent research initiative that was launched in early 2025 with a view to developing long-term forecasting tools for extreme coastal events in the Gulf of Guinea.
        Our objective is to establish a long-term, data-driven flood forecasting and alerting system for stakeholders in the Gulf of Guinea. We provide actionable information for disaster risk management across coastal West Africa by using satellite data, ocean modelling and statistical thresholds.
        From statistical modelling of historical events to real-time analysis of tides, wave action and sea level anomalies, this project aims to offer actionable insights to manage and prevent the impact of coastal flooding in the context of climate change.
        Should you wish to discuss potential collaborative opportunities, please do not hesitate to contact us at [reach out](egeodegeod@gmail.com)
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
          icon: waves
          description: Our approach involves the integration of data from Copernicus Marine Services, encompassing wave information and sea level anomaly data, in conjunction with the FES Tide Model to derive comprehensive estimates of total water levels.
        - name: Python & R-Based Models
          icon: code
          description: Our forecasting systems are developed using Python and R, ensuring both flexibility and scientific reproducibility.
        - name: Regional Forecasting
          icon: map
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
              **Our objective is to minimise vulnerabilities throughout society by making information regarding data and risk more accessible to a wider range of individuals.**
          image: audience.svg
          button:
            text: #Get Started
            url: #https://hugoblox.com/templates/
        - title: Promoting Coastal Resilience
          text: In addition to modelling and data collection, the project encompasses a range of engagement and knowledge-sharing activities, including
          feature_icon: bolt
          features:
            - Local outreach campaigns
            - On-site workshops and training
            - Educational materials for coastal schools and organizations
             **The objective of these programmes is to enhance preparedness and raise awareness of coastal hazards among affected communities.**
          # Upload image to `assets/media/` and reference the filename here
          image: trainings.svg
          button:
            text: #Join Discord
            url: #https://discord.gg/z8wNYzb
    design:
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    content:
      title: The project is overseen by an independent environmental researcher. The objective of the initiative is twofold firstly, to raise awareness of coastal flooding, and secondly, to promote environmental resilience.
      text: Drawing on expertise in geospatial data, ocean modelling, and data science, the project combines open-access tools such as Copernicus Marine Services,Google Earth Engine, and Sentinel imagery to support equitable access to coastal risk information.
      button:
        text: #Get Started
        url: #https://hugoblox.com/templates/
    design:
      card:
        css_class: "bg-primary-700"
        css_style: ""
---
