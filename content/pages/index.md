---
draft: true
blocks:
  - style:
      alignment: 'flex-row-reverse text-left items-end items-start-vertical '
      featureContent: 'w-1/2 min-h-0 '
      padding: pt-52 pb-16 pr-0 pl-20
      featureImage: 'object-right object-scale-down '
      imagePadding: pt-0 pb-16 pr-20 pl-0
      labelStyles: text-white font-2 text-xl mb-0 font-bold
      headlineStyles: text-primary font-1 text-4xl mb-8 font-bold
      subheadStyles: text-gray font-1 text-xl mb-7 font-bold
      textStyles: 'text-black font-1 text-base mb-4 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-white
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154094/bacalhau/shapes-1_u20ojn.svg
      alt: Shapes Illustration
    label: ''
    headline: Reinventing Science Through Reproducible Data Pipelines.
    subhead: ''
    body: >
      Bacalhau transforms Big Data processing by giving developers simple, low
      cost, “Distributed First” tools that unlock a new collaborative ecosystem.
    buttons:
      - label: Call to Action Link >
        link: '#'
        type: primary
    _template: feature
  - tailwind:
      section: pt-16 pb-16
      wrap: 'max-w-desktop-full mx-auto relative '
      imageWrap: ' pl-20'
      image: ''
      contentWrap: w-8/12 ml-auto  pr-20
      content: ''
      label: ''
      headline: absolute left-20 font-1 font-bold text-primary text-xl
      subhead: font-1 font-bold text-primary text-md mb-8
      text: font-1 text-md
      buttons: ''
    background:
      fillStyles: bg-accent3
    label: ''
    headline: Why Bacalhau?
    subhead: Bacalhau seeks to address deep rooted gaps in the research community
    body: |
      *   Cost & budget limitations for research departments
      *   Lack of easy to use tools for collaborative data processing
      *   Gravity of moving GB+ datasets, e.g. Landsat, Genome
      *   Challenges in building/collaborate with prior studies
    _template: tailwindFeature
  - style:
      alignment: 'flex-row text-left items-end items-start-vertical '
      featureContent: 'w-2/3 min-h-0 '
      padding: pt-0 pb-14 pr-20 pl-0
      featureImage: 'object-left object-scale-down '
      imagePadding: pt-0 pb-20 pr-0 pl-20
      labelStyles: 'text-black font-1 text-sm mb-0 '
      headlineStyles: text-primary font-1 text-xl mb-0 font-bold
      subheadStyles: text-primary font-1 text-base mb-8 font-bold
      textStyles: 'text-black font-1 text-base mb-0 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-accent3
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154093/bacalhau/shapes-2_v1e0y7.svg
    label: ''
    headline: ''
    subhead: >-
      The goal of the Bacalhau project is to give researchers and data engineers
      the ability to publicly reproduce data pipelines, thereby making their
      research more transparent and reusable. 
    body: "As a result, we hope to solve underlying problems for the scientific community including:\L\n\n*   Scientific record owned by a small set of publishers\n*   Unit of record is limited to a PDF\n*   Reproducibility/collaboration crisis\n*   DOI citation system is broken, insecure\n"
    _template: feature
  - tailwind:
      section: pt-16 pb-16
      wrap: 'max-w-desktop-full mx-auto relative '
      imageWrap: ' pl-20'
      image: ''
      contentWrap: w-8/12 ml-auto  pr-20
      content: ''
      label: ''
      headline: absolute left-20 font-1 font-bold text-primary text-xl
      subhead: font-1 font-bold text-primary text-md mb-8
      text: font-1 text-md
      buttons: ''
    background:
      fillStyles: bg-white
    label: ''
    headline: How does it work?
    subhead: >-
      Bacalahau is a network of open compute resources made available to serve
      any data processing workload.
    body: >
      • Lorem ipsum dolor sit amet, consectetur adipiscing elit.


      • Lorem ipsum dolor sit amet, consectetur adipiscing elit.


      Initially, the Bacalhau codebase will support execution of parallelizable
      jobs running on thousands of nodes. Then Bacalhau will be deployed as a
      testnet and later mainnet to support always available decentralized
      compute.
    _template: tailwindFeature
  - tailwind:
      section: pb-16
      wrap: flex max-w-desktop-full mx-auto relative items-end
      imageWrap: pl-20
      image: ''
      contentWrap: w-8/12 ml-auto pr-20
      content: ''
      label: ''
      headline: ''
      subhead: font-1 font-bold text-primary text-md mb-8
      text: bg-accent1 p-6 text-white text-sm font-3
      buttons: ''
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154093/bacalhau/shapes-3_ivg8gb.svg
    label: ''
    headline: ''
    subhead: Submitting Jobs is Easy
    body: >
      $ cid=$(ipfs add 10GB\_gps\_recordings.csv)


      $ bacalhau submit --cids=$cid --commands="sed
      /38.7\[2-4]....,-9.1\[3-5]..../"


      $ bacalhau results fetch 63dc96ee-429b-4301-8988-8729d54c6ead # job-id
    _template: tailwindFeature
  - style:
      alignment: 'flex-row-reverse text-left items-start items-start-vertical '
      featureContent: 'w-3/4 min-h-0 '
      padding: pt-20 pb-20 pr-20 pl-20
      featureImage: 'object-right object-scale-down '
      imagePadding: pt-20 pb-0 pr-20 pl-0
      labelStyles: 'text-black font-1 text-sm mb-0 '
      headlineStyles: text-primary font-1 text-2xl mb-5 font-bold
      subheadStyles: 'text-primary font-1 text-xl mb-5 '
      textStyles: 'text-black font-1 text-base mb-5 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-gray-light
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154094/bacalhau/shapes-4_t6tkoz.svg
    label: ''
    headline: Community
    subhead: Researchers
    body: >
      We're actively soliciting feedback from the scientific community, in
      particular researchers who:‍


      *   Publish (share) their research findings

      *   Collaborate on the research project with other individuals via Github
      or a similar platform

      *   Share their code and/or use code shared in Github as a starting point

      *   Have a multi-step process for their research data pipeline

      *   Please reach out via the Google Form button below and we'll engage
      with you directly!
    buttons:
      - label: Get In Touch
        link: /
        type: primary
    _template: feature
  - style:
      alignment: 'flex-row-reverse text-left items-center items-start-vertical '
      featureContent: 'w-3/4 min-h-0 '
      padding: pt-0 pb-20 pr-10 pl-20
      featureImage: 'object-center object-scale-down '
      imagePadding: pt-0 pb-0 pr-0 pl-0
      labelStyles: 'text-black font-1 text-sm mb-0 '
      headlineStyles: 'text-primary font-1 text-xl mb-5 '
      subheadStyles: 'text-primary font-1 text-lg mb-0 '
      textStyles: 'text-black font-1 text-base mb-5 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-gray-light
    label: ''
    headline: "For Developers / Contributors\L"
    subhead: ''
    body: |
      Jump into the source code on Github and participate on our Slack channels.
    buttons:
      - label: Cource Code
        link: /
        type: primary
      - label: Slack
        link: /
        type: primary
    _template: feature
meta:
  pageTitle: Bacalhau
  pageDescription: Reinventing Science through reproducible data pipelines
  siteImageSrc: ''
---

