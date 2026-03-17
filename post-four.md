---
type: PostLayout
title: Sharing my wisdom with the world 🌎
colors: colors-a
date: '2024-02-01'
author: content/data/team/doris-soto.json
excerpt: >-
  More context that may or may not be helpful
featuredImage:
  type: ImageBlock
  url: /images/featured-Image4.jpg
  altText: Post thumbnail image
bottomSections:
  - elementId: ''
    type: RecentPostsSection
    colors: colors-f
    variant: variant-d
    subtitle: Recent posts
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 2
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        textAlign: left
    showFeaturedImage: true
    showReadMoreLink: true
  - type: ContactSection
    backgroundSize: full
    title: 'Stay up-to-date with my words ✍️'
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit 🚀"
      styles:
        self:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        flexDirection: row
        textAlign: left
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ante lorem, tincidunt ac leo efficitur, feugiat tempor odio. Curabitur at auctor sapien. Etiam at cursus enim. Suspendisse sed augue to[...]  

## Heading 2

Etiam facilisis lacus nec pretium lobortis. Praesent dapibus justo non efficitur efficitur. Nullam viverra justo arcu, eget egestas tortor pretium id. Sed imperdiet mattis eleifend. Vivamus suscip[...]  

### Heading 3

Vestibulum ullamcorper risus auctor eleifend consequat. Vivamus mollis in tellus ac ullamcorper. Vestibulum sit amet bibendum ipsum, vitae rutrum ex. Nullam cursus, urna et dapibus aliquam, urna l[...]  

{% raw %}
```javascript
{
  page.content && (
    <Markdown
      options={{ forceBlock: true, overrides: { pre: HighlightedPreBlock } }}
      className="sb-markdown max-w-3xl mx-auto"
      data-sb-field-path="content"
    >
      {page.content}
    </Markdown>
  );
}
```
{% endraw %}

In volutpat efficitur nulla, aliquam ornare lectus ultricies ac. Mauris sagittis ornare dictum. Nulla vel felis ut purus fermentum pretium. Sed id lectus ac diam aliquet venenatis. Etiam ac aucto[...]  

Nam rutrum magna sed pellentesque lobortis. Etiam quam mauris, iaculis eget ex ac, rutrum scelerisque nisl. Cras finibus dictum ex sed tincidunt. Morbi facilisis neque porta, blandit mauris quis,[...]  

Aenean scelerisque ullamcorper est aliquet blandit. Donec ac tellus enim. Vivamus quis leo mattis, varius arcu at, convallis diam. Donec ac leo at nunc viverra molestie ac viverra nisi. Proin int[...]