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
        **End of the Road? Autonomous Vehicles and Displacement Risk** (JMP)
        <div class="paper">
        <details class="abstract">
        <summary>{{< icon name="hero/document-text" size="20" >}}Abstract</summary>
        New technologies have motivated renewed concerns about job displacement. In this paper, I link
        workers' subjective displacement expectations to their direct and social exposure to a disruptive
        technology: autonomous vehicles (AVs). I find that commercial driver licensing and employment in
        truck driving fall disproportionately in more AV-exposed areas. The remaining drivers extend their
        work hours and reduce their participation in mortgage markets relative to less-exposed, neighboring
        drivers. Changes in household substance use are consistent with heightened automation-induced anxiety
        and revised beliefs about susceptibility to automation. The results indicate that perceived
        displacement risk affects households' labor supply, credit behavior, and health, all of which could
        inform welfare assessments and policy responses to automation.

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
        </div>
        </div>

        **Relief Beliefs: Effects of Anticipated Student Loan Forgiveness** (with [Xuan Xie](https://sites.google.com/uw.edu/xuanxie/home))
        <div class="paper">
        <details class="abstract">
        <summary>{{< icon name="hero/document-text" size="20" >}}Abstract</summary>
        Political support for student loan forgiveness has been growing, particularly on the left, but evidence
        regarding its effects remains limited. We evaluate the immediate consumption response to President
        Biden's 2022 loan forgiveness announcement which promised debt relief of $10,000 to $20,000 for
        approximately 42 million borrowers. We find that retail stores located in counties with a 1% higher
        share of eligible student loan borrowers saw a persistent 0.1% increase in weekly sales. The positive
        spending response was absent in counties with high shares of financially delinquent households, consistent
        with delinquent borrowers being liquidity constrained and unable to smooth consumption. Novel data on debt
        relief eligibility and applications suggest that student loan borrowers anticipated relief they ultimately
        did not receive and adjusted their spending in response.

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
        </div>
        </div>

  - block: markdown
    id: wip
    content:
      title: Work in Progress
      text: |
        **Who Benefits from Venture Capital?** (with [Victor Lyonnet](https://sites.google.com/site/victorlyonnet/) and [Léa Stern](https://leastern.com/))

  - block: markdown
    id: pub
    content:
      title: Publications
      text: |
        **Institutional and Political Determinants of Statutory Tax Rates: Empirical Evidence from Sub-Saharan Africa**  
        (with Sanjeev Gupta, Carlos Mulas-Granados, Jianhong Liu and Kelsey Ross)  
        *[Journal of African Development, 2021](https://scholarlypublishingcollective.org/psup/african-development/article-abstract/22/2/227/293262/Institutional-and-Political-Determinants-of)*

        **The Future of Central America: Challenges for Sustainable Development**  
        *[Inter-American Development Bank, 2019](https://publications.iadb.org/es/el-futuro-de-centroamerica-retos-para-un-desarrollo-sostenible)*
---