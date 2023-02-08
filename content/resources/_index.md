---
id: resources

sections:
- OSF
- bids_bep16_conv
- bids_atlas
- zotero_library

OSF:
  enable: true
  partial: t-text_image
  title: "OSF page"
  size: 6
  content: >
    The project has an [OSF page](https://osf.io/u4g5p/) that brings all decentralized parts of it together in a central place for FAIR access. This includes the original [project proposal](https://osf.io/t4nxy), [software](https://osf.io/y3725/) generated within the project and [curated example datasets](https://osf.io/bz2vj/) (among others). Please feel free to have a look around and if you want to contribute, just let us know!  
  image: "img/osf_page.png"
  size: 4

bids_bep16_conv:
  enable: true
  partial: t-image_text
  title: "BIDS BEP16 conversions"
  content: >
    In order to facilitate the development and adaption of [BEP16, ie "Diffusion Weighted Imaging derivatives"](https://docs.google.com/document/d/1cQYBvToU7tUEtWMLMwXUCB_T8gebCotE1OczUpMYW60/comment), we created a `python` library called [bid_bep16_conv](https://github.com/PeerHerholz/bids_bep16_conv) which takes in `BIDS common derivative` - compliant data as input and applies one of two analysis approaches, either `DTI` or `CSD`, from one of three softwares, either `DIPY`, `MRTRIX` or `FSL`, subsequently res-structuring the outputs and adding respective metadata according to `BEP16`. The latter part will be constantly updated based on the latest changes in `BEP16`. Its processing/pipeline and conversion functionality is also available as a `BIDS-App`. Please have a look at the [documentation](https://peerherholz.github.io/bids_bep16_conv/index.html) to find out more.
  image: "img/bids_bep16_conv.png"
  size: 6

bids_atlas:
  enable: true
  partial: t-text_image
  title: "BIDS Atlas"
  content: >
    Focusing on [BEP, ie the Atlas specification](https://docs.google.com/document/d/1RxW4cARr3-EiBEcXjLpSIVidvnUSHE7yJCUY91i5TfM/edit?usp=sharing), we started to develop [bids_atlas](https://github.com/PeerHerholz/bids_atlas), a `python library` to access commonly used publicly available `atlases` and convert them to a `BEP`-compliant form. Interested users can simply indicate the atlas they want to utilize and specify its spatial reference, resolution and/or distinct version, with `bids_atlas` taking care of the rest. Besides providing `atlases`, it furthermore acts as a collection and characterization resource. For more information, please consult the [documentation](https://peerherholz.github.io/bids_atlas). 
  image: "img/bids_atlas.png"
  size: 6

zotero_library:
  enable: true
  partial: t-image_text
  title: "BIDS connectivity library"
  content: >
    Extending `BIDS` to capture and describe connectivity data, as well as developing the respective `BEP`s requires a lot of literature review. To also make this process as FAIR as possible, we created an open [zotero library](https://www.zotero.org/groups/4868686/bids_connectivity_project). Please feel free to have a look and if you want to contribute, contact us.
  image: "img/zotero_library.png"
  size: 4
---