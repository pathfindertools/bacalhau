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
    body: "Bacalhau operates as a peer-to-peer network of nodes where each node has both a requestor and compute component.\_ To interact with the cluster - Bacalhau CLI requests are sent to a node in the cluster (via JSON over HTTP), which then broadcasts messages over the transport layer to other nodes in the cluster.\_ All other nodes in the network are connected to the transport layer and as such have a shared view of the world.\n"
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

