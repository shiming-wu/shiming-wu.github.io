---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/CV_ShimingWu.pdf
    design:
      css_class: light
      # Avatar customization
      avatar:
        size: large  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      #background:
       # color: black
        #image:
          # Add your image background to `assets/media/`.
         # filename: IMG_0638.jpeg
          #filters:
           # brightness: 1.0
          #size: cover
          #position: center
          #parallax: false
  - block: markdown
    id: papers
    content:
      title: Working Papers
      subtitle: ''
      text: |-
       <div class="wide-content justified-text">
        <strong>What Constrains Insolvency in Property Insurance? Market Discipline, Capital Regulation, and Catastrophe Exposure
        
        Job Market Paper
        </strong>

        <p>This paper studies how employer mandates and health insurance affect labor market outcomes and health. I use staggered difference-in-differences research design and variations in the Affordable Care Act to learn how employer mandate affects labor market outcomes. I use doubly robust difference-in-differences in my main specifications to reduce selection bias. Results in the full sample suggest that the employer mandates in the Affordable Care Act increased hourly wages and did not have significant impacts on employment and part-time employment. Employer mandates stimulate a larger increase in employer-sponsored health insurance coverage rates among low-income workers. However, low-income workers are more vulnerable to involuntary part-time employment if employers reduce work hours to circumvent employer mandates. Firms prefer to reduce work hours to circumvent employer mandates instead of firing workers. Using doubly robust estimators and staggered difference-in-differences research design, I find evidence that providing health insurance improves workers' health. The employer mandate may increase productivity by improving workers' health status. Still, it may widen income inequality in the long run because low-income workers are more vulnerable to work hours losses.</p>
        </div>

        <div class="wide-content justified-text">
        <strong>Transformation of College to University and Impacts on Labor Market Outcomes</strong>

        <p>This paper studies the impacts of different types of post-secondary education on education and labor market outcomes. I first use variations of distances to institutions and exogenous variations of colleges that upgraded into universities to investigate the value added to university education. Then I separately estimate the impacts of the transformed universities and traditional colleges and universities. I compared results from OLS and IV regressions. To address the treatment heterogeneity, I adapt the locally linear specification from Mountjoy (2022). Results suggest that the difference between university and college graduates is marginal. However, university entry improves labor market outcomes, such as employment and earnings compared with cohorts without post-secondary education. Graduates from transformed universities obtain a higher probability of being employed and higher earnings compared with people without post-secondary education. Nonetheless, transformed university graduates may have worse performance in the labor market, compared with graduates from colleges or traditional universities. Furthermore, graduates from transformed universities are more willing to register for training when they are unemployed compared with the other three groups. </p>
        </div>

        <div class="wide-content justified-text">
        <strong>The Impacts of Health Insurance Mandates on the Labour Market and Health, Evidence from ACA</strong>

        <p>This paper studies how employer mandates and health insurance affect labor market outcomes and health. I use staggered difference-in-differences research design and variations in the Affordable Care Act to learn how employer mandate affects labor market outcomes. I use doubly robust difference-in-differences in my main specifications to reduce selection bias. Results in the full sample suggest that the employer mandates in the Affordable Care Act increased hourly wages and did not have significant impacts on employment and part-time employment. Employer mandates stimulate a larger increase in employer-sponsored health insurance coverage rates among low-income workers. However, low-income workers are more vulnerable to involuntary part-time employment if employers reduce work hours to circumvent employer mandates. Firms prefer to reduce work hours to circumvent employer mandates instead of firing workers. Using doubly robust estimators and staggered difference-in-differences research design, I find evidence that providing health insurance improves workers' health. The employer mandate may increase productivity by improving workers' health status. Still, it may widen income inequality in the long run because low-income workers are more vulnerable to work hours losses.</p>
        </div>

    design:
      view: article-grid
      columns: '1'
  - block: markdown
    id: progress
    content:
      title: Work in Progress
      subtitle: ''
      text: |-
        <div class="wide-content justified-text">
        <strong>Mitigating the Trade-off: How Natural Catastrophe Adaptation Can Reconcile Insurer Solvency and Affordability</strong>

        <p>Stringent capital regulation in property insurance markets creates a tension between insurer solvency and affordability. This paper demonstrates that adaptation to natural catastrophes can mitigate this trade-off. I develop and estimate a model of the property insurance market with interdependent loss structures, competition, and capital regulation. My counterfactual analysis shows that adaptation measures, by reducing the correlation of losses, would decrease the market insolvency rate and lower market concentration. Furthermore, I find a net positive impact on social welfare when the costs of insurer insolvency are repurposed to subsidize adaptation. My results indicate that policy should focus on incentivizing adaptation as a key tool for maintaining sustainable insurance markets.</p>
        </div>

        <div class="wide-content justified-text">
        <strong>A Reinforcement Learning Approach to Dynamic Capital Regulation in Property Insurance</strong>

        <p>This paper examines the policy debate on transitioning from static, formula-based capital regulation in the U.S. property insurance market to a dynamic, model-based approach. I propose a novel theoretical framework where regulators set a target insolvency probability, compelling insurers to adjust their capital holdings to remain below this threshold. A key feature of my model is the incorporation of an adaptive two-level learning process for insurers, acknowledging the evolving nature of risk due to climate change and increasing catastrophic events. I introduce an algorithm that enables regulators to facilitate this learning process while maintaining a stable and low industry-wide insolvency rate. This research contributes to the literature on financial regulation by demonstrating how a model-based approach can foster a more resilient and adaptive insurance sector in the face of growing uncertainty.</p>
        </div>

        <div class="wide-content justified-text">
        <strong>From Monoculture to Market: The Economics of Plant Biodiversity and Consumer Welfare</strong>

        <p>This paper investigates the complex relationship between industrial agriculture, plant biodiversity, and economic welfare. While industrial agriculture has been credited with increasing food production, it has also been linked to a significant decline in agrobiodiversity. This research disentangles two opposing economic forces: the homogenizing effect of industrial agriculture's focus on a few high-yield, storable crops, and the potential for market competition to foster product variety. I develop and estimate a structural model of demand and supply for fresh produce, employing a random coefficients logit model (BLP) to capture heterogeneous consumer preferences for a wide range of crop attributes, including variety. On the supply side, I model farmers' and food companies' decisions to offer different cultivars, considering the influence of production costs, market structure, and agricultural policies. Using detailed market-level data, I quantify the welfare effects of changes in plant biodiversity on consumers and producers. Furthermore, I extend the traditional welfare analysis to incorporate the non-market value of agrobiodiversity as a source of resilience to climate shocks. My findings aim to provide a more complete picture of the true social costs and benefits of industrial agriculture and to inform policies that promote a more diverse and sustainable food system. </p>
        </div>
    design:
      view: article-grid
      columns: '1'
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: ''
      text: |
        ECON 502 Macroeconomics, teaching TA (UBC)  
        ECON 490 Seminar in Applied Economics, TA (UBC)  
        ECON 370 Benefit-Cost Analysis and the Economics of Project Evaluation, TA (UBC)  
        ECON 356 Introduction to International Finance, TA (UBC)  
        ECON 255 Understanding Globalization, teaching TA (UBC)  
        ECON 102 Principles of Macroeconomics, teaching TA (UBC)  
        ECON 101 Principles of Microeconomics, teaching TA (UBC)  
    design:
      view: article-grid
      columns: '1'
  - block: markdown
    id: awards
    content:
      title: Awards and Grants
      subtitle: ''
      text: |
        CIDER Small Grants in Innovative Data (C\$26,000), 2023-2024  
        Sir Quo-Wei Lee Fellowship from St. John’s College, 2024-2026  
        Harnan A.N. Singh Scholarship in Economics, 2022  
        President’s Academic Excellence Initiative PhD Award, 2020-2026  
        Faculty of Arts Graduate Fellowship, 2020-2025  
        International Student Tuition Award, 2018-2026  
        Merit Student and Scholarships from Nankai University, 2012-2015  
    design:
      view: article-grid
      columns: '1'    
  #- block: markdown
   # content:
    #title: '📚 My Research'
    #subtitle: ''
    #text: |-
     #   Use this area to speak to your mission. I'm a research scientist in the Moonshot team at DeepMind. I blog about machine learning, deep learning, and moonshots.

      #  I apply a range of qualitative and quantitative methods to comprehensively investigate the role of science and technology in the economy.
        
       # Please reach out to collaborate 😃
    #design:
     # columns: '1'
  #- block: collection
   # id: papers
    #content:
     # title: Working Papers
      #filters:
       # folders:
        #  - papers
        #featured_only: true
    #design:
     # view: article-grid
      #columns: 1
 # - block: collection
  #  content:
   #   title: Recent Publications
    #  text: ""
     # filters:
      #  folders:
       #   - publication
        #exclude_featured: false
    #design:
     # view: citation
 # - block: collection
  #  id: awards
   # content:
    #  title: Recent & Upcoming Talks
     # filters:
      #  folders:
       #   - event
    #design:
     # view: article-grid
     # columns: 1
  #- block: collection
   # id: news
    #content:
     # title: Recent News
      #subtitle: ''
     # text: ''
      # Page type to display. E.g. post, talk, publication...
     # page_type: post
      # Choose how many pages you would like to display (0 = all pages)
     # count: 5
      # Filter on criteria
      #filters:
       # author: ""
        #category: ""
        #tag: ""
        #exclude_featured: false
        #exclude_future: false
        #exclude_past: false
        #publication_type: ""
      # Choose how many pages you would like to offset by
     # offset: 0
      # Page order: descending (desc) or ascending (asc) date.
     # order: desc
    #design:
      # Choose a layout view
     # view: date-title-summary
      # Reduce spacing
      #spacing:
       # padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
