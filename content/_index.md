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
        <strong><a href="/uploads/JMP_ShimingWu.pdf" target="_blank" rel="noopener">What Constrains Insolvency in Property Insurance? Market Discipline, Capital Regulation, and Catastrophe Exposure</a>

        Job Market Paper
        </strong>

        <p>This paper disentangles the roles of capital regulation and credit ratings in mitigating insolvency risk in the U.S. property insurance market. I first investigate the mechanism through which capital requirements affect the insurance market. Using an instrumental variable approach that exploits a 2017 policy change as a quasi-experiment, I find that a $1 million increase in required capital leads insurers to hold $3.34 million more in capital and to raise insurance prices by 0.218 percentage points. These results reveal a direct trade-off between financial stability and consumer affordability. To further explore the underlying mechanisms, I develop a structural model in which insurers make capital and pricing decisions in a competitive market with limited liability and exposure to catastrophic risks. Counterfactual analyses show that tightening capital requirements improves solvency but raises prices. In the absence of capital regulation, the model predicts that the insolvency rate would increase by 0.09 percentage points, while insurance prices would decline by about 5.1%, accompanied by greater risk-taking and market concentration. A third counterfactual scenario examines a market without capital regulation but with high credit rating salience. When consumers place greater emphasis on credit ratings, the insolvency rate decreases; however, intensified price competition reduces profitability and increases market concentration. Overall, the findings underscore that capital regulation remains crucial for sustaining market stability, as heightened rating salience alone cannot fully substitute for its stabilizing effects.</p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/Shiming_Transformation of College to University and Impacts on Labor Market Outcomes and Training Participation under Employment Insurance.pdf" target="_blank" rel="noopener">Transformation of College to University and Impacts on Labor Market Outcomes and Training Participation under Employment Insurance</a>
        </strong>

        <p>This paper studies the impacts of different types of post-secondary education on education and labor market outcomes, with a particular focus on training participation during unemployment under Canada’s Employment Insurance (EI) system. I first use variations of distances to institutions and exogenous variations of colleges that upgraded into universities to investigate the value added to university education. Then I separately estimate the impacts of the transformed universities and traditional colleges and universities. I compare results from OLS and IV regressions. To address treatment heterogeneity, I adapt the locally linear specification from Mountjoy (2022). Results suggest that the difference between university and college graduates is marginal. However, university entry improves labor market outcomes, such as employment and earnings, compared with cohorts without post-secondary education. Graduates from transformed universities obtain a higher probability of being employed and higher earnings compared with people without post-secondary education. Nonetheless, transformed university graduates may have worse performance in the labor market compared with graduates from colleges or traditional universities. In addition, transformed university graduates are more likely to register for EI-supported training programs during unemployment, compared with graduates from colleges, traditional universities, and individuals without post-secondary education, highlighting an important interaction between higher education pathways and training incentives embedded in the EI system.</p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/Contracting the Cosmos Externalities, Capital Markets, and Coasian Bargaining.pdf" target="_blank" rel="noopener">Contracting the Cosmos: Externalities, Capital Markets, and Coasian Bargaining</a>
        </strong>

        <p>The growing energy requirements of artificial intelligence (AI) present significant challenges for terrestrial power grids, prompting the technology sector to consider deploying data centers in low Earth orbit. However, operating in the orbital commons introduces an unpriced spatial externality: the endogenous jump-to-ruin risk associated with orbital congestion, known as the Kessler Syndrome. This paper develops a continuous-time stochastic real options game featuring endogenous asset loss and exogenous technological shocks to examine the capital structure and entry timing for commercial space infrastructure. The analysis highlights a theoretical tension: in environments subject to endogenous jump-to-ruin, standard uncoordinated competitive entry increases physical asset density, thereby elevating the probability of collision and potential market failure. Furthermore, the model shows that traditional debt financing is structurally unviable due to zero collateral recovery upon collision, suggesting a pure equity structure. To address the spatial externality, I model two equilibrium regimes. Under a mandatory insurance regime, global reinsurance syndicates function as decentralized regulatory mechanisms, pricing the spatial externality into a firm's cost of capital. In a self-insured open access regime, physical carrying capacity constraints and endogenous debris removal costs incentivize Coasian bargaining. The findings suggest that the unregulated space market tends to consolidate into a coordinated oligopoly, mitigating the tragedy of the commons through private financial constraints without requiring direct sovereign intervention</p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/A Reinforcement Learning Approach to Dynamic Capital Regulation in Property Insurance_Shiming.pdf" target="_blank" rel="noopener">A Reinforcement Learning Approach to Dynamic Capital Regulation in Property Insurance</a>
        </strong>

        <p>Regulators in the U.S. property insurance market face a critical challenge: transitioning from static, formula-based capital requirements to dynamic, model-based regimes. While dynamic regulation offers the potential to improve social welfare and market resilience, it suffers from two major barriers: computational intractability under profound uncertainty and a lack of interpretability required for regulatory oversight. In this paper, I propose a novel framework for outcome-based regulatory design. I develop a Learn-Verify-Explain methodology that utilizes Deep Reinforcement Learning to discover optimal dynamic capital strategies. Unlike traditional black-box approaches, my framework integrates Formal Verification to mathematically guarantee compliance with safety constraints and Decision Tree Extraction to distill complex policies into transparent, implementable rules. Empirical results demonstrate that this hybrid approach outperforms traditional static benchmarks, increasing social welfare by approximately 35% while reducing insolvency rates to zero. Crucially, the distilled policy reveals a risk-sensitive stabilization strategy: the agent learns to prioritize market efficiency through deregulation during stable periods, while imposing immediate corrective tightening upon detecting early signs of distress. This study provides an experiment of AI-in-the-loop financial regulation.</p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/Adaptation, Insurer Solvency, and Affordability_Shiming.pdf" target="_blank" rel="noopener">Adaptation, Insurer Solvency, and Affordability</a>
        </strong>

        <p>I analyze the growing tension between insurer solvency and insurance affordability in property markets exposed to climate change. I develop a structural model where risk-averse households choose between purchasing insurance and investing in physical risk adaptation, while competitive insurers face regulatory capital requirements for systemic climate risk. My model demonstrates two findings: (1) high frictional cost of regulatory capital creates a high entry price for insurance that is relatively insensitive to individual adaptation, and (2) below a specific wealth threshold, both physical adaptation and insurance coverage collapse as households lack the liquidity to clear the solvency-loaded premium. Through policy counterfactuals, I find that premium subsidies are counterproductive; by making insurance artificially cheap, they cause households to increase financial coverage while decreasing physical adaptation effort. In contrast, adaptation grants that directly target the liquidity friction are highly effective, allowing households to jump to a higher state of resilience, which improves both household welfare and market-wide financial stability.</p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/From Monoculture to Market.pdf" target="_blank" rel="noopener">From Monoculture to Market: The Economics of Plant Biodiversity, Systemic Risk, and Consumer Welfare</a>
        </strong>

        <p>Modern industrial agriculture relies on monocultures to maximize economies of scale, yet this genetic homogenization introduces profound systemic risks to global food security. This paper investigates whether market competition naturally corrects this trend or exacerbates it, utilizing a two-stage structural model of endogenous cultivar choice and price competition. By estimating a random coefficients Logit model, I quantify the static welfare gains from cultivar variety and the dynamic insurance value of biodiversity against correlated supply shocks. Simulation results demonstrate that consumers derive significant utility from variety, with a transition to pure monoculture resulting in a 73% loss in static consumer surplus. Crucially, I find that market structure determines this vulnerability: a simulated competitive oligopoly sustains four distinct cultivars, whereas a monopoly restricts the market to just two, internalizing cannibalization. Furthermore, I identify a substantial market failure: while monoculture is statically efficient in normal states, it creates unpriced systemic tail risk. Under simulated shocks, the expected social welfare of a diverse biological portfolio is approximately 68% higher than that of a monoculture. These results suggest that profit-maximizing firms structurally under-provide biodiversity, providing a rigorous economic rationale for biodiversity subsidies and stringent antitrust scrutiny in agribusiness. </p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/Shiming_Defensive Triage Minimizing Insurance Liability via Bayesian Uncertainty Quantification in Emergency Queues.pdf" target="_blank" rel="noopener">Defensive Triage: Minimizing Insurance Liability via Bayesian Uncertainty Quantification in Emergency Queues</a>
        </strong>

        <p>Emergency Department (ED) overcrowding presents a dual crisis: it compromises patient safety and destabilizes the medical liability insurance market. High-cost malpractice claims, particularly those stemming from failure to diagnose ambiguous cases, drive up insurance premiums, thereby increasing healthcare overhead and limiting patient access to affordable care. Traditional triage protocols and deterministic Machine Learning (ML) models optimize for operational efficiency but ignore the fat-tail liability risks associated with diagnostic uncertainty. This paper proposes a novel Defensive Triage mechanism that integrates Bayesian Uncertainty Quantification into queueing logic. By prioritizing patients based on epistemic uncertainty, we effectively hedge against catastrophic misdiagnosis. Using a discrete-event simulation benchmarked against standard protocols, I demonstrate that this approach significantly reduces aggregate liability exposure. I argue that by lowering the frequency of high-severity claims, Defensive Triage allows insurers to stabilize premiums. This creates a virtuous economic cycle: reduced insurer risk lowers provider costs, ultimately expanding the capacity of the healthcare system to provide accessible, insured care to a broader population.</p>
        </div>

        <div class="wide-content justified-text">
        <strong><a href="/uploads/Hedging Against the Silver Tsunami_Shiming.pdf" target="_blank" rel="noopener">Hedging Against the Silver Tsunami: A Health Capital Preservation Triage Framework to Mitigate Long-Term Care Liability and Insurance Risks</a>
        </strong>

        <p>As populations age, the primary economic threat to healthcare sustainability is the accelerated depreciation of health capital. While traditional triage focuses on short-term liability shielding, musculoskeletal (MSK) triage in elderly populations requires a long-term capital preservation approach. This research proposes three novel frameworks: The Functional Autonomy Hedge (FAH), which utilizes gradient-based symptom volatility; Expected Liability Calibration (ELC), which optimizes for insurance solvency by pricing the marginal cost of diagnostic delay; and the Frailty-Decay Shield (FDS), which incorporates a biological aging parameter. By identifying latent invisible risks near clinical cliffs, I employ actuarial policies to prioritize patients with high-risk profiles. Simulation results (N=5,000) demonstrate that while FAH offers a modest 5.6% liability reduction over standard AI, the optimized ELC framework achieves a 50.2% reduction. The FDS framework, by pricing frailty, provides the superior result with a 52.4% reduction, effectively serving as a mathematically rigorous hedge against the systemic risks of the Silver Tsunami.</p>
        </div>

        <div class="wide-content justified-text">
        <strong>The Impacts of Health Insurance Mandates on the Labour Market and Health, Evidence from ACA</strong>

        (Draft available on request)

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
        <strong>The Energy Bridge: Optimal Sequencing of Terrestrial Nuclear and Space-Based Power for AI Computation</strong>

        <p>The rapid expansion of artificial intelligence is creating a terminal energy bottleneck that traditional terrestrial grids are ill-equipped to handle. While space-based solar power represents the ultimate solution for high-density compute clusters, the technology remains in its infancy, necessitating a multi-decade transition strategy involving terrestrial solar and Small Modular Reactors (SMRs). This paper develops a structural corporate finance model to analyze the optimal sequencing of these heterogeneous energy investments under conditions of technological uncertainty and capital irreversibility. Using a continuous-time real options framework, I examine the trade-offs between the lower capital intensity of terrestrial solar and the high-baseload reliability of nuclear SMRs as bridges to eventual orbital energy migration. The model characterizes the technological overhang created by long-lived nuclear assets and the resulting stranded asset risk if space-based breakthroughs occur prematurely. I solve the firm's intertemporal optimization problem to derive endogenous investment thresholds and optimal capital structure dynamics. The paper aims to propose a novel class of contingent-claim financing instruments. The resulting framework provides a rigorous valuation architecture for technology firms and infrastructure investors navigating the high-stakes frontier of the AI energy transition.</p>
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
        ECON 345 Money and Banking, TA (UBC)  
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
