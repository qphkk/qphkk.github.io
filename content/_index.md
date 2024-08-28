---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Vita #Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctor of Engineering
          company: Department of Applied Physics, The University of Tokyo
          company_url: ''
          location: Tokyo
          date_start: '2024-04-01'
          date_end: ''
          description: |2-
              Director: Prof. Yukitoshi Motome
        - title: Master of Engineering
          company: Department of Applied Physics, The University of Tokyo
          company_url: ''
          location: Tokyo
          date_start: '2022-04-01'
          date_end: '2024-03-31'
          date_end: ''
          description: |2-
              Director: Prof. Yukitoshi Motome

              Thesis: *Reservoirs* of Insight: Harnessing and Probing Nature via Computational Paradigms ([Outstanding Master Thesis Award](https://www.ap.t.u-tokyo.ac.jp/themes/ap_t_u-tokyo/campus/pdf/2023/2023M.pdf))
        - title: Bachelor of Engineering
          company: Department of Applied Physics, The University of Tokyo
          company_url: ''
          location: Tokyo
          date_start: '2018-04-01'
          date_end: '2022-03-31'
          description: |2-
              Director: Prof. Eiji Saitoh
              
              Thesis: 逆スピンホール効果による磁化状態トモグラフィ (Magnetization state tomography by inverse spin-Hall effect) ([Outstanding Bachelor Thesis Award](https://www.ap.t.u-tokyo.ac.jp/themes/ap_t_u-tokyo/campus/pdf/2021/2021B.pdf))
    design:
      columns: '2'
  - block: experience
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Fellowships, etc.' # 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: BOOST NAIS
          company: University of Tokyo
          company_url: https://spring-gx.adm.s.u-tokyo.ac.jp/en/boost/
          date_end: '2027-03-31'
          date_start: '2024-08-01'
          description: Advanced AI Talent Development to Lead the Next-Generation Intelligent Society ([BOOST NAIS](https://spring-gx.adm.s.u-tokyo.ac.jp/en/boost/))
        - title: JSPS research fellowships for young scientists (DC1)
          company: Japan Society for the Promotion of Science
          company_url: https://www.jsps.go.jp/english/
          date_end: '2024-07-31'
          date_start: '2024-04-01'
          description: Research Fellowships for Young Scientists  ([DC1](https://www.jsps.go.jp/english/e-pd/)) 
        - title: Mitou Target Program
          company: Information-technology Promotion Agency, Japan (IPA)
          company_url: https://www.ipa.go.jp/en/index.html
          date_end: '2024-02-29'
          date_start: '2023-06-01'
          description: |2-
            Research project for the [development of a fast machine learning method based on quantum reservoir computing](https://www.ipa.go.jp/jinzai/mitou/target/2023/gaiyou_yn-2.html)

            Project Manager: Prof. Naoki Yamamoto
        - title: MERIT-WINGS
          company: University of Tokyo
          company_url: https://www.merit.t.u-tokyo.ac.jp/merit/en/index.html
          date_end: '2027-03-31'
          date_start: '2022-10-01'
          description: World-leading Innovative Graduate Study program for Materials Research, Information, and Technology ([MERIT-WINGS](https://www.merit.t.u-tokyo.ac.jp/merit/en/index.html))
        - title: Nakatani RIES
          company: Nakatani Foundation
          company_url: https://www.nakatani-foundation.jp/en/
          date_end: '2021-03-31'
          date_start: '2020-04-01'
          description: International research internship at Georgia Institute of Technology (online)
        - title: Iizuka Takeshi Scholarships
          company: Iizuka Takeshi Scholarship Foundation
          company_url: https://www.iizuka-takeshi-ikuei.or.jp/
          date_end: '2022-03-31'
          date_start: '2018-04-01'
  #   design:
  #     columns: '2'
  - block: portfolio
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      columns: '2'
      view: citation
  - block: portfolio
    id: presentations
    content:
      count: 2
      order: desc
      exclude_upcoming: false
      active: true
      title: Presentations
      filters:
        folders:
          - event
      buttons:
        - name: International
          tag: International
        - name: Domestic
          tag: Domestic
        - name: Seminar
          tag: Seminar
    #headless: true
    design:
      columns: '1'
      view: Compact
  - block: portfolio
    id: press
    content:
      title: Press, Patent, etc.
      filters:
        folders:
          - press
      buttons:
        - name: Japanese
          tag: Japanese
        - name: English
          tag: English
      count: 2
      order: desc
    #headless: true
    design:
      columns: '2'
      view: List
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards' # 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: 
          date_start: '2024-02-02'
          #description: 物理工学科優秀卒業論文賞
          organization: Department of Applied Physics, The University of Tokyo
          organization_url: https://www.ap.t.u-tokyo.ac.jp/en/
          title: Outstanding Master Thesis Award
        - date_end: 
          date_start: '2023-07-06'
          description: Best Poster Award, International Conference on Strongly Correlated Electron Systems 2023
          organization: SCES2023
          organization_url: https://www.sces2023.org
          title: Best Poster Award
        - date_end: 
          date_start: '2022-03-25'
          #description: 工学部長賞（学修）
          organization: School of Engineering, The University of Tokyo
          organization_url: https://www.t.u-tokyo.ac.jp/en/foe
          title: Dean's Award for Academic Excellence
        - date_end: 
          date_start: '2022-03-25'
          #description: 工学部長賞（研究）
          organization: School of Engineering, The University of Tokyo
          organization_url: https://www.t.u-tokyo.ac.jp/en/foe
          title: Dean's Award for Outstanding Research
        - date_end: 
          date_start: '2022-03-25'
          #description: 物理工学科優秀卒業論文賞
          organization: Department of Applied Physics, The University of Tokyo
          organization_url: https://www.ap.t.u-tokyo.ac.jp/en/
          title: Outstanding Bachelor Thesis Award
        - date_end: 
          date_start: '2021-10-14'
          # description: |2-
          #   物理工学特別輪講発表賞 (Best Presentation Award in the Advanced Seminar in Applied Physics)

          #   Advisor: Prof. Satoru Hayami
          description: Best Presentation Award, Advanced Seminar in Applied Physics
          organization: Department of Applied Physics, The University of Tokyo
          organization_url: https://www.ap.t.u-tokyo.ac.jp/en/
          title: Best Presentation Award
    design:
      columns: '1'
  - block: experience
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Experience' # 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      items:
        # - title: Visiting
        #   company: Frank Pollmann group
        #   company_url: https://spring-gx.adm.s.u-tokyo.ac.jp/en/boost/
        #   date_end: '2027-03-31'
        #   date_start: '2024-08-01'
        #   description: Advanced AI Talent Development to Lead the Next-Generation Intelligent Society ([BOOST NAIS](https://spring-gx.adm.s.u-tokyo.ac.jp/en/boost/))
        # - title: Visiting Student @ Technical University of Munich
        #     company: Frank Pollmann group
        #     company_url: https://www.professoren.tum.de/pollmann-frank
        #     date_end: '2024-12-06'
        #     date_start: '2024-9-29'
        # - title: Teaching Assistant (Statistical mechanics)
        #     company: UTokyo
        #     date_end: '2024-3-31'
        #     date_start: '2023-10-01'
        # - title: Teaching Assistant (Exercises in Mathematics and Mechanics I)
        #   company: UTokyo
        #   date_end: '2023-3-31'
        #   date_start: '2022-10-01'
        # - title: Internship @ Preferred Networks
        #   company: Preferred Networks
        #   company_url: https://www.preferred.jp/ja/
        #   date_end: '2022-9-30'
        #   date_start: '2022-8-03'
        - title: Part-time job @ SAS Institute Japan
          company_url: https://www.sas.com/ja_jp/home.html
          company: UTokyo
          date_end: '2019-7-31'
          date_start: '2018-6-01'
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: kaito-kobayashi92[!αΤ!]g.ecc.u-tokyo.ac.jp
      address:
        street: 7-3-1, Hongo
        city: Bunkyo-ku
        region: Tokyo
        postcode: '113-8656'
        country: Japan
        country_code: JP
      directions: Faculty of Engineering Bldg.6
      text: |2-
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3239.489477283997!2d139.75839867605993!3d35.71417877257663!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188c31b1189969%3A0xc9429c48c85c9716!2sFaculty%20of%20Engineering%20Building%206!5e0!3m2!1sen!2sjp!4v1699689477620!5m2!1sen!2sjp" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '1'
---
