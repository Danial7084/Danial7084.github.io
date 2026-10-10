---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/DS_CV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: foster.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
          text_color_light: true

  - block: markdown
    id: wp
    content:
      title: Working Papers
      text: |
        **End of the Road? Autonomous Vehicles and Displacement Risk**
        <div class="paper">
        <details class="abstract">
        <summary>{{< icon name="hero/document-text" size="20" >}}Abstract</summary>
        New technologies have renewed concerns about job displacement. In this paper, I link workers'
        subjective displacement expectations to their direct and social exposure to a disruptive technology:
        autonomous vehicles (AVs). I find that commercial driver licensing and employment in
        truck driving fall disproportionately in more AV-exposed areas. The remaining drivers extend
        their work hours and reduce participation in mortgage markets relative to less-exposed, neighboring
        drivers. Changes in household spending on alcohol and tobacco products are consistent with
        heightened automation-induced anxiety. The results indicate that perceived displacement risk
        affects households' labor supply, credit behavior, and health, all of which could inform welfare
        assessments and policy responses to automation.

        <figure class="abs-fig">
          <a href="uploads/DS_End_of_the_Road.pdf" target="_blank" rel="noopener">
            <img src="uploads/figures/CA_AV_did_dyn.png"
                 alt="Effect of AV exposure on CDL licensing: event study plot"
                 loading="lazy">
          </a>
          <figcaption>AV Testing in California</figcaption>
        </figure>
        </details>

        <div class="paper-actions">
          <a href="uploads/DS_End_of_the_Road.pdf" target="_blank" rel="noopener noreferrer">
            {{< icon name="hero/arrow-down-tray" size="20" >}} PDF</a>
            <a href="https://ssrn.com/abstract=6725879" target="_blank" rel="noopener noreferrer">
            {{< icon name="hero/link" size="20" >}} SSRN</a>
          <a href="https://www.ft.com/content/e888b187-75c0-4233-9588-d1b9948b1b0a" target="_blank" rel="noopener noreferrer">
            {{< icon name="hero/newspaper" size="20" >}} Financial Times</a>
          <p class="punchline">{{< icon name="hero/light-bulb" size="18" >}}Households respond preemptively to the threat of automation</p>
          <div class="presentations">{{< icon name="hero/presentation-chart-bar" size="18" >}}NBER SI 2026 Digital Economics and Artificial Intelligence, NBER Economics of Transportation Spring 2026, Colorado Finance Summit 2025
          </div>  
        </div>
        </div>

        **Relief Beliefs: Effects of Anticipated Student Loan Forgiveness** (with [Xuan Xie](https://sites.google.com/uw.edu/xuanxie/home))
        <div class="paper">
        <details class="abstract">
        <summary>{{< icon name="hero/document-text" size="20" >}}Abstract</summary>
        We study how households adjust consumption to news about future liabilities. Our setting is President Biden's August 2022 student loan forgiveness announcement, which promised $10,000 to $20,000 in debt relief to approximately 42 million borrowers. Because the announcement occurred during the student loan payment moratorium, it created an uncertain wealth shock without contemporaneously changing required payments. We link administrative data on debt relief eligibility and applications to high-frequency retail scanner data. Stores located in counties with a 1 percentage point higher share of eligible borrowers experienced a persistent 0.1% increase in weekly sales following the announcement. This response was absent in counties with high pre-announcement delinquency rates, consistent with delinquent borrowers being liquidity constrained and unable to smooth consumption. Sales subsequently declined in more-exposed counties when the Supreme Court blocked the plan. Together with widespread debt relief applications, the spending responses show that beliefs about ultimately unrealized debt relief affected households' behavior.

        <figure class="abs-fig">
          <a href="uploads/DS_XX_Relief_Beliefs.pdf" target="_blank" rel="noopener">
            <img src="uploads/figures/geo_share_eligible.jpg"
                 alt="Change in weekly retail sales following forgiveness announcement"
                 loading="lazy">
          </a>
          <figcaption>Distribution of Student Loan Forgiveness</figcaption>
        </figure>
        </details>

        <div class="paper-actions">
          <a href="uploads/DS_XX_Relief_Beliefs.pdf" target="_blank" rel="noopener noreferrer">
            {{< icon name="hero/arrow-down-tray" size="20" >}} PDF</a>
          <a href="https://ssrn.com/abstract=5157757" target="_blank" rel="noopener noreferrer">
            {{< icon name="hero/link" size="20" >}} SSRN</a>
          <p class="punchline">{{< icon name="hero/light-bulb" size="18" >}}Households adjust consumption to news about future liabilities</p>
          <div class="presentations">{{< icon name="hero/presentation-chart-bar" size="18" >}}NBER Economics of Education Spring 2026, 10th SAFE Household Finance Workshop
          </div>
          <p class="awards">{{< icon name="hero/presentation-chart-line" size="18" >}}FMA 2025 Annual Meeting Best Paper Award (semifinalist)</p>
        </div>
        </div>

  - block: markdown
    id: wip
    content:
      title: Work in Progress
      text: |
        **Who Benefits from Venture Capital?** (with [Victor Lyonnet](https://sites.google.com/site/victorlyonnet/) and [Léa Stern](https://leastern.com/))

  # - block: markdown
  #   id: pub
  #   content:
  #     title: Publications
  #     text: |
  #       **Institutional and Political Determinants of Statutory Tax Rates: Empirical Evidence from Sub-Saharan Africa**  
  #       (with Sanjeev Gupta, Carlos Mulas-Granados, Jianhong Liu and Kelsey Ross)  
  #       *[Journal of African Development, 2021](https://scholarlypublishingcollective.org/psup/african-development/article-abstract/22/2/227/293262/Institutional-and-Political-Determinants-of)*

  #       **The Future of Central America: Challenges for Sustainable Development**  
  #       *[Inter-American Development Bank, 2019](https://publications.iadb.org/es/el-futuro-de-centroamerica-retos-para-un-desarrollo-sostenible)*
---
