---
draft: true
blocks:
  - tailwind:
      section: ''
      wrap: >-
        max-w-desktop-full mx-auto relative flex flex-row-reverse items-end
        items-start-vertical
      imageWrap: pb-16 pr-20
      image: object-right object-scale-down
      contentWrap: w-3/4 pt-52 pb-16 pl-20
      content: ''
      label: bg-accent4 text-accent4 w-6 h-6 mb-8
      headline: text-primary font-1 text-4xl mb-8 font-bold
      subhead: ''
      text: text-black font-2 text-base mb-8 max-w-lg
      buttons: 'text-accent2 font-bold text-base '
      button: ''
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154094/bacalhau/shapes-1_u20ojn.svg
    label: x
    headline: Reinventing Science Through Reproducible Data Pipelines.
    subhead: ''
    body: >
      Bacalhau transforms Big Data processing by giving developers simple, low
      cost, “Distributed First” tools that unlock a new collaborative ecosystem.
    buttons:
      - label: Learn More
        link: /architecture
    _template: tailwindFeature
  - tailwind:
      section: pt-16 pb-16
      wrap: 'max-w-desktop-full mx-auto relative '
      imageWrap: pl-20
      image: ''
      contentWrap: w-8/12 ml-auto pr-20
      content: ''
      label: ''
      headline: absolute left-20 font-1 font-bold text-primary text-xl
      subhead: font-1 font-bold text-primary text-base mb-8
      text: font-2 text-base
      buttons: ''
    background:
      fillStyles: bg-accent3
    label: ''
    headline: Why Bacalhau?
    subhead: Bacalhau seeks to address deep rooted gaps in the research community
    body: >
      *   Cost & budget limitations for research departments

      *   Lack of easy to use tools for collaborative data processing

      *   Challenges in building/collaborate with prior studies

      *   Performance limitations of moving large GB+ datasets (e.g. Landsat,
      Genome) across public networks
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
      textStyles: 'text-black font-2 text-base mb-0 '
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
      subhead: font-1 font-bold text-primary text-base mb-8
      text: font-2 text-base
      buttons: ''
    background:
      fillStyles: bg-white
    label: ''
    headline: How does it work?
    subhead: >-
      Bacalahau is a network of open compute resources made available to serve
      any data processing workload.
    body: >
      Bacalhau enables users to run arbitrary docker containers and wasm images
      as tasks against data stored in IPFS. This architecture is referred to as
      Compute Over Data (or COD). The Portuguese word for salted Cod fish is
      "Bacalhau" which is the origin of the project's name.


      Bacalhau operates as a peer-to-peer network of nodes where each node
      participates in executing (computing) jobs submitted to the cluster.
      Bacalhau CLI requests are sent to nodes in the cluster, which then
      broadcasts messages over the transport layer to other nodes in the
      cluster.
    _template: tailwindFeature
  - tailwind:
      section: pb-26
      wrap: flex max-w-desktop-full mx-auto relative items-end
      imageWrap: pl-20
      image: ''
      contentWrap: w-8/12 ml-auto pr-20
      content: ''
      label: ''
      headline: ''
      subhead: font-1 font-bold text-primary text-base mb-8
      text: bg-accent1 p-6 text-white text-xs font-3
      buttons: 'text-accent2 font-bold text-base '
      button: ''
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154093/bacalhau/shapes-3_ivg8gb.svg
    label: ''
    headline: ''
    subhead: Submitting Jobs is Easy
    body: |
      $ bacalhau run ubuntu echo hello

      $ bacalhau list --wide --sort-by=id --id-filter=\<JOB\_ID>&#x20;

      $ ipfs get \<RESULT\_CID>
    buttons:
      - label: Learn More
        link: /architecture
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
      textStyles: 'text-black font-2 text-base mb-5 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-gray-light
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655154094/bacalhau/shapes-4_t6tkoz.svg
    label: ''
    headline: Dive In!
    subhead: ''
    body: ''
    buttons:
      - label: Community
        link: /community
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
      textStyles: 'text-black font-2 text-base mb-5 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-gray-light
    label: ''
    headline: "For Developers / Contributors\L"
    subhead: ''
    body: |
      Jump into the source code on Github and participate on our Slack channels.
    buttons:
      - label: Source Code
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

