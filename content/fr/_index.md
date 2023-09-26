---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
#  - block: hero
#    content:
#      title: Hugo Academic Theme
#      image:
#        filename: hero-academic.png
#      cta:
#        label: '**Get Started**'
#        url: https://wowchemy.com/templates/
#      cta_alt:
#        label: Ask a question
#        url: https://discord.gg/z8wNYzb
#      cta_note:
#        label: >-
#          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
#      text: |-
#        **Generated by Wowchemy - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**
#
#        **Easily build anything with blocks - no-code required!**
#
#        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
#
#        <!--Custom spacing-->
#        <div class="mb-3"></div>
#        <!--GitHub Button JS-->
#        <script async defer src="https://buttons.github.io/buttons.js"></script>
#    design:
#      background:
#        gradient_end: '#1976d2'
#        gradient_start: '#004ba0'
#        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#  - block: features
#    content:
#      title: Skills
#      items:
#        - name: R
#          description: 90%
#          icon: r-project
#          icon_pack: fab
#        - name: Statistics
#          description: 100%
#          icon: chart-line
#          icon_pack: fas
#        - name: Photography
#          description: 10%
 #         icon: camera-retro
#          icon_pack: fas
  - block: collection
    id: publications
    content:
      title: Publications
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        folders:
          - publication
        author: ""
        category: ""
        tag: ""
        exclude_featured: true
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: citation
      columns: '2'
  - block: collection
    content:
      title: Other texts
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      count: 0
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: list
      flip_alt_rows: true
  - block: markdown
    id: conferences
    content:
      title: Conferences
      subtitle: List of conferences I attended
      text: |-
          1. *[Algebraic Combinatorics in Representation Theory](https://conferences.cirm-math.fr/1490.html)*, CIRM, Luminy, August 2016
          2. *[Geometry and Representation Theory](https://imsc.uni-graz.at/baur/ESI2017/)*, ESI, Vienna, January 2017
          3. Symposium [*L'enseignement des mathématiques, où en sont les différences filles-garçons ?*](http://www.femmes-et-maths.fr/index.php?page=blog_lire&id=220), IHP, Paris, September 2017
          4. [*Forum des jeunes mathématiciennes*](http://forum2017.iecl.univ-lorraine.fr/), Nancy, November 2017
          5. [*Cluster Algebras, Twenty Years On*](https://conferences.cirm-math.fr/1777.html), CIRM, Luminy, March 2018
          6. *[Interactions of quantum affine algebras with cluster algebras, current algebras and categorification](https://quantumaffine2018.catholic.edu/)*, Washington DC, June 2018
          7. *[World Meeting for Women in Mathematics](https://www.worldwomeninmaths.org/)* (WM)², Rio de Janeiro, July 2018
          8. *[International Congress of Mathematicians](http://www.icm2018.org/portal/main.html)* (ICM2018), Rio de Janeiro, August 2018
          9. *[Representations in Lie Theory and Interactions](https://conferences.cirm-math.fr/1817.html)*, CIRM, Luminy, November 2018
          10. *[XXV Brazilian Algebra School](http://www.ime.unicamp.br/~ea25/index.html)*, Campinas, December 2018
          11. *[Cluster Algebras 2019](https://sites.google.com/view/clusteralg19)* (CA 2019), Kyoto, June 2019
          12. *[Categorifications, Moduli Spaces and Representation Theory](https://conferences.cirm-math.fr/2134.html)*, CIRM, Luminy, January 2020
          13. *[Workshop Algebraic and geometric Lie theory](https://www.math.u-psud.fr/~plamondon/colloqueTournant/)* "Colloque tournant", IHP, Paris, February 2020
          14. *[ARTIN 2020: Tensor Categories, Quantum Groups and Related Topics](https://www.nottingham.ac.uk/mathematics/events/workshops/artin-2020.aspx)*, University of Nottingham, June 2020
          15. *[Quantum Algebra Days](https://damienespadon.wixsite.com/dersympapp/quantum-algebra-days)*, IMAG, Montpellier, November 2020
          16. *[Quantum Groups and Cohomology Theory of Quiver and Flag Varieties](https://conferences.cirm-math.fr/2221.html)*, CIRM, BBB, December 2020
          17. *[New developments in representation theory arising from cluster algebras research school](https://www.newton.ac.uk/event/carw01/)*, INI, Cambridge, September 2021
          18. *[New developments in representation theory arising from cluster algebras](https://www.newton.ac.uk/event/carw02/)*, INI, Cambridge, September 2021
          19. *[Enveloping Algebras and Geometric Representation Theory](https://www.mfo.de/occasion/2144/www_view)*, Oberwolfach, November 2021
          20. *[WINART3 workshop](http://women-in-ncalg-repthy.org/conferences/winart3-workshop/)*, Banff, April 2022 
          21. *[Bridges between representation theory and algebraic geometry: Singularities, friezes and cluster categories](https://sites.google.com/view/singular-clusters)*, Leeds, May 2022 
          22. *[Summer School: Representation theory and flag or quiver varieties](https://school2022.sciencesconf.org/)*, Paris, June 2022 
          23. *[Geometric Reresentation Theory workshop](https://indico.ipmu.jp/event/409/overview)*, Kavli IPMU, Zoom, June-July 2022 
          24. *[World Meeting for Women in Mathematics](https://2022.worldwomeninmaths.org/)*, Youtube, July 2022
          25. *[Bases for cluster algebras](https://www.birs.ca/events/2022/5-day-workshops/22w5173?fbclid=IwAR0M7dSknWDPbW9eR_2EDSgr69QY3WWjrQ9AYij6ZEm1dcYlvsRKZN4gbgM)*, Oaxaca, September 2022 
          26. *[The Geometry of Double Affine Hecke Algebras and Coulomb Branches](https://www.icms.org.uk/HeckeAlgebras)*, Edinburgh, March 2023 
    design:
      columns: '1'
      view: compact


  - block: accomplishments
    id: teaching
    content:
      title: Teaching
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Tutor
          organization: University of Edinburgh
          organization_url: 'https://www.maths.ed.ac.uk/school-of-mathematics'
          date_start: '2022-09-01'
          date_end: '2022-12-16'
          description: |2-
              **Honours Analysis** Worshops
        - title: Tutor
          organization: University of Edinburgh
          organization_url: 'https://www.maths.ed.ac.uk/school-of-mathematics'
          date_start: '2022-01-20'
          date_end: '2022-04-08'
          description: |2-
              **Honours Algebra** - Skills Labs
        - title: Tutor
          organization: University of Edinburgh
          organization_url: 'https://www.maths.ed.ac.uk/school-of-mathematics'
          date_start: '2021-09-01'
          date_end: '2021-12-15'
          description: |2-
              **Introduction to Linear Algebra** Workshops
        - title: Teaching Assistant
          organization: Université Paris Diderot
          organization_url: 'https://u-paris.fr/'
          date_start: '2017-09-01'
          date_end: '2018-08-31'
          description: |2-
              **Advanced Algebra and Analysis** Travaux Dirigés
        - title: Teaching Assistant
          organization: Université Paris Diderot
          organization_url: 'https://u-paris.fr/'
          date_start: '2016-09-01'
          date_end: '2017-08-31'
          description: |2-
              **Basic Algebra and Analysis** Travaux Dirigés
        - title: Oral examiner
          organization: Lycée Saint Louis
          date_start: '2013-09-01'
          date_end: '2015-08-31'
          description: |2-
              Weekly oral exams (**colles**) for 1st year students preparing for engineer school.
#        - title: Professor of Semiconductor Physics
#          company: University X
#          company_url: ''
#          company_logo: org-x
#          location: California
#          date_start: '2016-01-01'
#          date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: accomplishments
    id: other_activities
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Other activities
#      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2023-01-06'
          date_start: '2022-09-01'
          description: ''
          organization: University of Edinburgh
          title: Organizer of the [**Algebra Seminar**](https://sites.google.com/view/hodge-seminars/)
#          url: ''
        - date_end: '2022-08-31'
          date_start: '2021-09-01'
          description: ''
          organization: University of Edinburgh
          title: Organizer of the [**Hodge Seminar**](https://sites.google.com/view/hodge-seminars/)
#          url: ''
        - date_end: '2023-01-06'
          date_start: '2021-09-01'
          description: ''
          organization: University of Edinburgh
          title: Postdoc representative, [*Equality, Diversity and Inclusion* committee](https://www.maths.ed.ac.uk/school-of-mathematics/about-us/equality-diversity-and-inclusion)
#          url: 'https://www.maths.ed.ac.uk/school-of-mathematics/about-us/equality-diversity-and-inclusion'
        - date_end: '2019-08-31'
          date_start: '2017-09-01'
          description: ''
          organization: Université Paris Diderot
          title: Organizer of the *Rencontres Master-Doctorants*
          description : Biannual meetings between graduate students and PhD students.
#          url: 'https://www.maths.ed.ac.uk/school-of-mathematics/about-us/equality-diversity-and-inclusion'
        - date_end: '2019-08-31'
          date_start: '2017-09-01'
          description: ''
          organization: Université Paris Diderot
          title: Member of the [*Comité Parité*](https://www.imj-prg.fr/comite-parite/)
#          url: 'https://www.imj-prg.fr/comite-parite/'

#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
    design:
     columns: '2'
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
      # Choose how many pages you would like to offset by
#      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
 #     view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
 #   design:
 #     columns: '2'
 #     view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
#      # Contact (add or remove contact options as necessary)
      email: lea.bittmann@ed.ac.uk
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
      address:
        street: James Clerk Maxwell Building
        city: Edinburgh
#        region: CA
        postcode: 'EH9 3FD'
        country: United Kingdom
#        country_code: UK
      directions: Office 5422
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#      # Automatically link email and phone or display as text?
#      autolink: true
#      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
---