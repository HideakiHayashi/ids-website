---
title: Nerve segmentation with deep learning from label-free endoscopic images obtained
  using coherent anti-stokes Raman scattering
date: '2020-07-01'
publishDate: '2022-09-05T07:39:55.921284Z'
authors:
- Naoki Yamato
- Mana Matsuya
- Hirohiko Niioka
- Jun Miyake
- Mamoru Hashimoto
publication_types:
- '1'
abstract: Semantic segmentation with deep learning to extract nerves from label-free
  endoscopic images obtained using coherent anti-Stokes Raman scattering (CARS) for
  nerve-sparing surgery is described. We developed a CARS rigid endoscope in order
  to identify the exact location of peripheral nerves in surgery. Myelinated nerves
  are visualized with a CARS lipid signal in a label-free manner. Because the lipid
  distribution includes other tissues as well as nerves, nerve segmentation is required
  to achieve nerve-sparing surgery. We propose using U-Net with a VGG16 encoder as
  a deep learning model and pre-training with fluorescence images, which visualize
  the lipid distribution similar to CARS images, before fine-tuning with a small dataset
  of CARS endoscopy images. For nerve segmentation, we used 24 CARS and 1,818 fluorescence
  nerve images of three rabbit prostates. We achieved label-free nerve segmentation
  with a mean accuracy of 0.962 and an F1 value of 0.860. Pre-training on fluorescence
  images significantly improved the performance of nerve segmentation in terms of
  the mean accuracy and F1 value (p<0.05). Nerve segmentation of label-free endoscopic
  images will allow for safer endoscopic surgery, while reducing dysfunction and improving
  prognosis after surgery.
featured: false
publication: '*Biomolecules*'
url_pdf: https://www.mdpi.com/2218-273X/10/7/1012
doi: https://doi.org/10.3390/biom10071012
links:
- name: URL
  url: https://www.mdpi.com/2218-273X/10/7/1012
---

