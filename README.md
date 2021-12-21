# awesome-3d-photography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A paper list of 3D photography / cinemagraph.

This list is non-exhaustive. Feel free to pull requests or create issues to add papers.

Following [this repo](https://github.com/timzhang642/3D-Machine-Learning), I use some icons to (imprecisely) differentiate the 3D representations:
* :leaves: Layered Depth Image
* :gem: Mesh
* :airplane: Multiplane Images
* :taxi: Nerf
* :cloud: Point Cloud
* :space_invader: Voxel

## Papers List 1
Here I include the papers for novel view synthesis with **a single input image** based on **3D geometry**. 
- `[arXiv 2021]` 3D Photo Stylization: Learning to Generate Stylized Novel Views from a Single Image [[paper]](https://arxiv.org/pdf/2112.00169.pdf) [[code]](https://github.com/fmu2/3d_photo_stylization) [[project page]](http://pages.cs.wisc.edu/~fmu/style3d/) :cloud:
- `[ICCV 2021]` Infinite Nature: Perpetual View Generation of Natural Scenes from a Single Image [[paper]](https://arxiv.org/pdf/2012.09855.pdf) [[code]](https://github.com/google-research/google-research/tree/master/infinite_nature) [[project page]](https://infinite-nature.github.io/) :gem:
- `[ICCV 2021]` MINE: Towards Continuous Depth MPI with NeRF for Novel View Synthesis [[paper]](https://arxiv.org/pdf/2103.14910.pdf) [[code]](https://github.com/vincentfung13/MINE) [[project page]](https://vincentfung13.github.io/projects/mine/) :airplane: :taxi:
- `[ICCV 2021]` PixelSynth: Generating a 3D-Consistent Experience from a Single Image [[paper]](https://arxiv.org/pdf/2108.05892.pdf) [[code]](https://github.com/crockwell/pixelsynth) [[project page]](https://crockwell.github.io/pixelsynth/) :cloud:
- `[ICCV 2021]` SLIDE: Single Image 3D Photography with Soft Layering and Depth-aware Inpainting [[paper]](https://arxiv.org/pdf/2109.01068.pdf) [[project page]](https://varunjampani.github.io/slide/) :gem:
- `[ICCV 2021]` Video Autoencoder: self-supervised disentanglement of static 3D structure and motion [[paper]](https://arxiv.org/pdf/2110.02951.pdf) [[code]](https://github.com/zlai0/VideoAutoencoder/) [[project page]](https://zlai0.github.io/VideoAutoencoder/) :space_invader:
- `[ICCV 2021]` Worldsheet: Wrapping the World in a 3D Sheet for View Synthesis from a Single Image [[paper]](https://arxiv.org/pdf/2012.09854.pdf) [[code]](https://github.com/facebookresearch/worldsheet) [[project page]](https://worldsheet.github.io/) :gem:
- `[CVPR 2021]` Layout-Guided Novel View Synthesis from a Single Indoor Panorama [[paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Xu_Layout-Guided_Novel_View_Synthesis_From_a_Single_Indoor_Panorama_CVPR_2021_paper.pdf) [[dataset]](https://github.com/bluestyle97/PNVS)
- `[WACV 2021]` Adaptive Multiplane Image Generation from a Single Internet Picture [[paper]](https://openaccess.thecvf.com/content/WACV2021/papers/Luvizon_Adaptive_Multiplane_Image_Generation_From_a_Single_Internet_Picture_WACV_2021_paper.pdf) :airplane:
- `[CVPR 2020]` Single-View View Synthesis with Multiplane Images [[paper]](https://single-view-mpi.github.io/single_view_mpi.pdf) [[code]](https://github.com/google-research/google-research/tree/master/single_view_mpi) [[project page]](https://single-view-mpi.github.io/) :airplane:
- `[CVPR 2020]` SynSin: End-to-end View Synthesis from a Single Image [[paper]](https://arxiv.org/pdf/1912.08804.pdf) [[code]](https://github.com/facebookresearch/synsin) [[project page]](https://www.robots.ox.ac.uk/~ow/synsin.html) :cloud: 
- `[CVPR 2020]` 3D Photography using Context-aware Layered Depth Inpainting [[paper]](https://arxiv.org/pdf/2004.04727.pdf) [[code]](https://github.com/vt-vl-lab/3d-photo-inpainting) [[project page]](https://shihmengli.github.io/3D-Photo-Inpainting/) :leaves:
- `[Trans. Graph. 2020]` One Shot 3D Photography [[paper]](https://arxiv.org/pdf/2008.12298.pdf) [[code]](https://github.com/facebookresearch/one_shot_3d_photography) [[project page]](https://facebookresearch.github.io/one_shot_3d_photography/) :leaves: :gem:
- `[Trans. Graph. 2019]` 3D Ken Burns Effect from a Single Image [[paper]](https://arxiv.org/pdf/1909.05483.pdf) [[code]](https://github.com/sniklaus/3d-ken-burns) :cloud:
- `[ICCV 2019]` Monocular Neural Image-based Rendering with Continuous View Control [[paper]](https://arxiv.org/pdf/1901.01880.pdf) [[code]](https://github.com/xuchen-ethz/continuous_view_synthesis)
- `[ECCV 2018]` Layer-structured 3D Scene Inference via View Synthesis [[paper]](https://arxiv.org/pdf/1807.10264.pdf) [[code]](https://github.com/google/layered-scene-inference) [[project page]](https://shubhtuls.github.io/lsi/) :leaves:
- `[SIGGRAPH Posters 2011]` Layered Photo Pop-Up [[poster]](https://richardt.name/publications/photopopup/LayeredPhotoPopup-poster.pdf) [[abstract]](https://richardt.name/publications/photopopup/LayeredPhotoPopup-abstract.pdf) [[project page]](https://richardt.name/publications/photopopup/)

## Papers List 2
Binocular input. Not a complete list.
- `[ICCV 2019]` Extreme View Synthesis [[paper]](https://arxiv.org/pdf/1812.04777) [[code]](https://github.com/NVlabs/extreme-view-synth)
- `[CVPR 2019]` Pushing the Boundaries of View Extrapolation with Multiplane Images [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Srinivasan_Pushing_the_Boundaries_of_View_Extrapolation_With_Multiplane_Images_CVPR_2019_paper.pdf) :airplane:
- `[SIGGRAPH 2018]` Stereo Magnification: Learning View Synthesis using Multiplane Images [[paper]](https://dl.acm.org/doi/pdf/10.1145/3197517.3201323) [[code]](https://github.com/google/stereo-magnification) [[project page]](https://tinghuiz.github.io/projects/mpi/) :airplane:

## Papers List 3
Some other interesting papers for novel view synthesis or cinemagraph.
- `[ICCV 2021]` Geometry-Free View Synthesis: Transformers and no 3D Priors [[paper]](https://arxiv.org/pdf/2104.07652.pdf) [[code]](https://github.com/CompVis/geometry-free-view-synthesis) [[project page]](https://compvis.github.io/geometry-free-view-synthesis/)
- `[ICCV 2021]` iPOKE: Poking a Still Image for Controlled Stochastic Video Synthesis [[paper]](https://arxiv.org/pdf/2107.02790.pdf) [[code]](https://github.com/CompVis/ipoke) [[project page]](https://compvis.github.io/ipoke/)
- `[ICCV 2021]` Learning to Stylize Novel Views [[paper]](https://arxiv.org/pdf/2105.13509.pdf) [[code]](https://github.com/hhsinping/stylescene) [[project page]](https://hhsinping.github.io/3d_scene_stylization/) :cloud:
- `[ICCV 2021]` Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis [[paper]](https://arxiv.org/pdf/2104.00677.pdf) [[code]](https://github.com/ajayjain/DietNeRF) [[project page]](https://www.ajayj.com/dietnerf) :taxi:
- `[CVPR 2021]` Animating Pictures with Eulerian Motion Fields [[paper]](https://eulerian.cs.washington.edu/animating_pictures_2020.pdf) [[project page]](https://eulerian.cs.washington.edu/)
- `[SIGGRAPH 2021]` Endless Loops: Detecting and Animating Periodic Patterns in Still Images [[paper]](https://storage.googleapis.com/ltx-public-images/Endless_Loops__Detecting_and_animating_periodic_patterns_in_still_images.pdf) [[project page]](https://pub.res.lightricks.com/endless-loops/)
- `[SIGGRAPH Asia 2019]` Animating Landscape: Self-Supervised Learning of Decoupled Motion and Appearance for Single-Image Video Synthesis [[paper]](https://arxiv.org/pdf/1910.07192.pdf) [[code]](https://github.com/endo-yuki-t/Animating-Landscape) [[project page]](http://www.cgg.cs.tsukuba.ac.jp/~endo/projects/AnimatingLandscape/)
- `[ICCV 2017]` Personalized Cinemagraphs using Semantic Understanding and Collaborative Learning [[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Oh_Personalized_Cinemagraphs_Using_ICCV_2017_paper.pdf)
