---
draft: true
blocks:
  - style:
      alignment: 'flex-row-reverse text-left items-start items-start-vertical '
      featureContent: 'w-1/2 min-h-0 '
      padding: pt-52 pb-16 pr-0 pl-20
      featureImage: 'object-right object-scale-down '
      imagePadding: pt-52 pb-16 pr-20 pl-0
      labelStyles: text-white font-2 text-xl mb-0 font-bold
      headlineStyles: text-primary font-1 text-3xl mb-8 font-bold
      subheadStyles: text-gray font-1 text-xl mb-7 font-bold
      textStyles: 'text-black font-2 text-base mb-4 '
      contentOrder: labelHeadingsContent
    background:
      fillStyles: bg-white
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655320824/bacalhau/dlagram_lxg5zk.jpg
      alt: Shapes Illustration
    label: ''
    headline: High Level Architecture
    subhead: ''
    body: >
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Facilisis nec
      venenatis magna scelerisque amet id suspendisse sed natoque. Cras cursus
      ut suspendisse pretium augue erat ac. Praesent vel arcu nibh dictum
      egestas cum turpis nibh. Massa augue lacus risus est, pellentesque. Quam
      fusce id ut felis mauris. Tristique dictumst ultricies id at ultrices id
      in est. Lectus nullam malesuada neque aliquet nullam urna id. Donec
      aliquam volutpat dictum consectetur. Sed habitant scelerisque et sit.
      Scelerisque ut nam dis suspendisse nam quam nullam phasellus vitae.&#x20;


      Hendrerit purus lectus rhoncus aenean et elit. Etiam nulla adipiscing
      imperdiet pellentesque et, amet. Sed a viverra diam vitae, leo praesent
      aenean vel pellentesque. Neque, at ut nisl, eu pulvinar cursus tellus.
      Sapien facilisis nisl in sed aenean. Mauris quisque lectus lectus
      vestibulum.&#x20;
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
      headline: absolute left-20 font-1 font-bold text-white text-2xl
      subhead: font-1 text-white text-xl mb-8
      text: font-3 text-xs text-white bg-accent1 p-8
      buttons: ''
    background:
      fillStyles: bg-primary
    label: ''
    headline: Sample Code
    subhead: Submitting Jobs is Easy
    body: >
      $ cid=$(ipfs add 10GB\_gps\_recordings.csv)


      $ bacalhau submit --cids=$cid --commands="sed
      /38.7\[2-4]....,-9.1\[3-5]..../"


      $ bacalhau results fetch 63dc96ee-429b-4301-8988-8729d54c6ead # job-id
    _template: tailwindFeature
meta:
  pageTitle: Bacalhau
  pageDescription: Reinventing Science through reproducible data pipelines
  siteImageSrc: ''
---

