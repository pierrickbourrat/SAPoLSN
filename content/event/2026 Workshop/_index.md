---
title: "2026 Workshop"
date: 2026-08-04
type: landing

design:
  spacing: "6rem"

sections:

  - block: hero
    content:
      title: |
        Philosophy Meets the Life Sciences

      text: |

        **24–25 August 2026**

        School of Humanities, Macquarie University, Sydney

      image:
        filename: workshop-poster.jpg


  - block: markdown
    id: about

    content:
      title: About
      text: |

        The main objective of this 2-day workshop will be to showcase research in philosophy that deeply engages with the life sciences and, conversely, to feature work in the life sciences that engages substantially with philosophy. The theme of the workshop is intentionally broad, as an effort to support both continued dialogue between experts in philosophy and the life sciences while also providing a platform for potential future collaborations.


  - block: people
    id: speakers

    content:
      title: Speakers

      user_groups:
        - Speakers2026

      sort_by: Params.last_name
      sort_ascending: true

    design:
      show_role: true
      show_social: false
      show_interests: false


  - block: people
    id: organisers

    content:
      title: Organisers

      user_groups:
        - Organisers2026

      sort_by: Params.last_name
      sort_ascending: true

    design:
      show_role: true
      show_social: false
      show_interests: false

  - block: markdown
    id: program

    content:
      title: Program

      text: |

        ## Day 1 (24 August)

        <div align="center">

        | Time | Speaker | Title |
        |------|----------|---------|
        | 08:30-08:50 |  | Coffee / Registration |
        | 08:50-09:00 |  | Welcome |
        | 09:00-09:45 | Paul Griffiths (University of Sydney and Macquarie University) | TBA |
        | 09:45-10:30 | Mingjun Zhang (University of Sydney and Macquarie University) | Demystifying Distinctively Mathematical Explanations |
        | 10:30-11:00 |  | Coffee Break 1 |
        | 11:00-11:45 | David Kaplan (Macquarie University) | It's about time: A mechanistic perspective on timescales and temporal organisation in the brain |
        | 11:45-12:30 | Andreas Wagner (University of Zürich) | TBA |
        | 12:30-02:00 |  | Lunch |
        | 02:00-02:45 | Chris Lean (Macquarie University) | Genomic Globalisation |
        | 02:45-03:30 | Cristina Villegas (Konrad Lorenz Institute for Evolution and Cognition Research) | Modeling Evolutionary Variation with Causal Probability |
        | 03:30-04:00 |  | Coffee Break 2 |
        | 04:00-04:45 | Rob Wilson (University of Western Australia) | The Progenerative View of Kinship as a Philosophical Intervention in the Fragile Sciences |
        | 04:45 pm |  | End of Day 1 |
        | 06:00 pm |  | Dinner at The Ranch |

        </div>

        ---

        ## Day 2 (25 August)

        <div align="center">

        | Time | Speaker | Title |
        |------|----------|---------|
        | 08:30-09:00 |  | Coffee / Arrival |
        | 09:00-09:45 | David Raubenheimer (University of Sydney) | Agencies in nutritional systems |
        | 09:45-10:30 | Rachael Brown (Australian National University) | TBA |
        | 10:30-11:00 |  | Coffee Break 1 |
        | 11:00-11:45 | Yafeng Shan (The Hong Kong University of Science and Technology) | Origins of Genetics Revisited |
        | 11:45-12:30 | Andrew Barron (Macquarie University) | The first neural spatial representation |
        | 12:30-02:00 |  | Lunch |
        | 02:00-02:45 | John Matthewson (Massey University) | Model organisms and population types |
        | 02:45-03:30 | Sandy Boucher (University of New England) | Endogenising organisation: organicism and the major transitions in evolution |
        | 03:30-04:00 |  | Coffee Break 2 |
        | 04:00-04:45 | Patrick McGivern (University of Wollongong) | Transitions in biological individuality and mesoscale structure |
        | 04:45-05:30 | Ken Cheng (Macquarie University) | Basic units of action as basis for navigation |
        | 05:30 pm |  | End of Workshop |

        </div>

  - block: markdown
    id: location

    content:
      title: Location

      text: |

        <div style="text-align: center; margin: 0 auto;">
          <img src="Lakeside.png" 
               alt="Map of the venue" 
               style="max-width: 100%; width: 700px; height: auto; display: block; margin: 0 auto;">
        </div>

        <p style="text-align: center; margin-top: 1rem;">
          <a href="https://maps.app.goo.gl/WwpNbySsNT9JboNZ6?g_st=ic" target="_blank" rel="noopener">
            Lakeside Hotel &amp; Conference Centre
          </a><br>
          Macquarie University<br>
          Sydney, Australia
        </p>
    
    design:
      css_class: "text-center"


  - block: markdown
    id: sponsors

    content:
      title: Sponsors
      text: |
        <style>
        .sponsor-grid {
          display: flex;
          flex-wrap: wrap;
          justify-content: center;   /* 水平居中 */
          align-items: center;       /* 垂直居中（当高度不一致时有用） */
          gap: 2rem;
          margin: 2rem auto 0;       /* 上下外边距 + 水平自动居中 */
          max-width: 100%;
          width: 100%;
        }

        .sponsor-card {
          width: 180px;
          text-align: center;
          display: flex;
          flex-direction: column;
          align-items: center;       /* 卡片内部图片和文字也居中 */
        }

        .sponsor-card img {
          max-width: 100%;
          max-height: 100px;
          object-fit: contain;
          display: block;            /* 去掉图片默认的 inline 空隙 */
          margin: 0 auto;
        }

        .sponsor-name {
          margin-top: 0.5rem;
        }

        .sponsor-name a {
          text-decoration: none;
          color: inherit;
        }

        .sponsor-name a:hover {
          text-decoration: underline;
        }
        </style>

        <div class="sponsor-grid">

          <div class="sponsor-card">
            <img src="/images/institutions/SAPoLSN.jpg" alt="SAPoLSN logo">
            <div class="sponsor-name">
              <a href="https://www.sapolsn.com" target="_blank" rel="noopener">
                SAPoLSN
              </a>
            </div>
          </div>

          <div class="sponsor-card">
            <img src="/images/institutions/mq.jpg" alt="Macquarie University logo">
            <div class="sponsor-name">
              <a href="https://www.mq.edu.au" target="_blank" rel="noopener">
                Macquarie University
              </a>
            </div>
          </div>

          <div class="sponsor-card">
            <img src="/images/institutions/pku.jpg" alt="Peking University logo">
            <div class="sponsor-name">
              <a href="https://www.pku.edu.cn" target="_blank" rel="noopener">
                Peking University
              </a>
            </div>
          </div>

          <div class="sponsor-card">
            <img src="/images/institutions/fdu.jpg" alt="Fudan University logo">
            <div class="sponsor-name">
              <a href="https://www.fudan.edu.cn" target="_blank" rel="noopener">
                Fudan University
              </a>
            </div>
          </div>

          <div class="sponsor-card">
            <img src="/images/institutions/JTF.jpg" alt="JTF logo">
            <div class="sponsor-name">
              <a href="https://www.templeton.org/" target="_blank" rel="noopener">
                John Templeton Foundation
              </a>
            </div>
          </div>

          <div class="sponsor-card">
            <div class="sponsor-name">
              <a href="https://www.mq.edu.au/research/research-centres-institutes-and-initiatives/minds-and-intelligences" target="_blank" rel="noopener">
                Minds and Intelligences Research Centre
              </a>
            </div>
          </div>

        </div>
---