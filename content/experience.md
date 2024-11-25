---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: experience
    content:
      title: Research Experience
      username: admin
      date_format: Jan 2006
      items:
        - title: Undergraduate Student Researcher
          company: Carnegie Mellon University
          location: Pittsburgh, PA
          date_start: '2024-02-01'
          date_end: ''
          description: |
            - Developed the miniCTX benchmark to evaluate large language models in formal mathematics, focusing on real-world proof generation using context information.
            - Fine-tuned deepseek-coder-1.3B model using file-tuning data, which incorporates context information alongside traditional state-tactic pairs, outperforming larger models like Llemma-7B and GPT-4o.
---
