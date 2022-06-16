---
draft: true
blocks:
  - tailwind:
      section: pt-16 pb-16
      wrap: >-
        max-w-desktop-full mx-auto relative flex flex-row-reverse items-start
        items-vertical-end
      imageWrap: w-1/2 pt-60 pb-16 px-20
      image: ml-auto
      contentWrap: w-1/2 pt-40 pb-16 pl-20
      content: ''
      label: w-6 h-6 bg-accent1 text-accent1 mb-8
      headline: text-primary font-1 text-3xl mb-8 font-bold
      subhead: ''
      text: text-black font-2 text-base mb-4
      buttons: text-accent2 text-base font-bold
      button: ''
    image:
      src: >-
        https://res.cloudinary.com/protocolai/image/upload/v1655320824/bacalhau/dlagram_lxg5zk.jpg
    label: x
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
      Scelerisque ut nam dis suspendisse nam quam nullam phasellus vitae.


      Hendrerit purus lectus rhoncus aenean et elit. Etiam nulla adipiscing
      imperdiet pellentesque et, amet. Sed a viverra diam vitae, leo praesent
      aenean vel pellentesque. Neque, at ut nisl, eu pulvinar cursus tellus.
      Sapien facilisis nisl in sed aenean. Mauris quisque lectus lectus
      vestibulum.
    buttons:
      - label: Call to Action Link >
        link: /
    _template: tailwindFeature
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

