---
title: Stackbit
sections:
  - type: hero_section
    title: Stackbit
    subtitle: The optional subtitle
    align: center
    padding_top: medium
    padding_bottom: none
    background_color: none
  - type: blog_feed_section
    blog_feed_cols: three
    enable_cards: true
    show_recent: false
    tag: data/tags/stackbit.json
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: true
    show_image: true
    padding_top: small
    padding_bottom: large
    has_border: true
  - type: form_section
    title: Inline Form
    title_align: center
    content: Subscribe to our newsletter to make sure you don't miss anything.
    content_align: center
    form_position: bottom
    form_layout: inline
    form_id: subscribeForm
    form_action: /thank-you
    form_fields:
      - type: form_field
        input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
    submit_label: Subscribe
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: secondary
seo:
  type: stackbit_page_meta
  title: Posts in Stackbit
  description: This is the author archive page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Posts in Stackbit
      keyName: property
    - name: 'og:description'
      value: This is the author archive page
      keyName: property
    - name: 'og:image'
      value: images/classic/post-5.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Posts in Stackbit
    - name: 'twitter:description'
      value: This is the author archive page
    - name: 'twitter:image'
      value: images/classic/post-5.png
      relativeUrl: true
layout: advanced
---
