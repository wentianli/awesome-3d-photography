# awesome-3d-photography [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A paper list of 3D photography and cinemagraph.

This list is non-exhaustive. Feel free to pull requests or create issues to add papers.

Following [this repo](https://github.com/timzhang642/3D-Machine-Learning), I use some icons to (imprecisely) differentiate the 3D representations:
* :leaves: Layered Depth Image
* :gem: Mesh
* :airplane: Multiplane Images
* :taxi: Nerf
* :cloud: Point Cloud
* :space_invader: Voxel

## 3D Photography
Novel view synthesis with **a single input image** based on **3D geometry**.
- `[arXiv 2023]` Novel View Synthesis with View-Dependent Effects from a Single Image [[paper]](https://arxiv.org/abs/2312.08071) [[project page]](https://kaist-viclab.github.io/monovde-site/)
- `[SA 2023]` SinMPI: Novel View Synthesis from a Single Image with Expanded Multiplane Images [[paper]](https://doi.org/10.1145/3610548.3618155) [[code]](https://github.com/TrickyGo/SinMPI) :leaves:
- `[TOG 2023]` ReShader: View-Dependent Highlights for Single Image View-Synthesis [[paper]](https://arxiv.org/abs/2309.10689) [[code]](https://github.com/avinashpaliwal/ReShader) [[project page]](https://people.engr.tamu.edu/nimak/Papers/SIGAsia2023_Reshader/index.html)
- `[NeurIPS 2023]` Diffusion with Forward Models: Solving Stochastic Inverse Problems Without Direct Supervision [[paper]](https://diffusion-with-forward-models.github.io/diffusion-forward-paper.pdf) [[code]](https://github.com/ayushtewari/DFM/) [[project page]](https://diffusion-with-forward-models.github.io/)
- `[ICCV 2023]` Diffuse3D: Wide-Angle 3D Photography via Bilateral Diffusion [[paper]](https://jianbojiao.com/pdfs/iccv23_diffuse3d.pdf) [[code]](https://github.com/yutaojiang1/Diffuse3D) :leaves:
- `[ICCV 2023]` LoLep: Single-View View Synthesis with Locally-Learned Planes and Self-Attention Occlusion Inference [[paper]](https://arxiv.org/abs/2307.12217) :airplane:
- `[arXiv 2023]` Generative Novel View Synthesis with 3D-Aware Diffusion Models [[paper]](https://arxiv.org/abs/2304.02602) [[project page]](https://nvlabs.github.io/genvs/)
- `[CVPR 2023]` Structural Multiplane Image: Bridging Neural View Synthesis and 3D Reconstruction [[paper]](https://arxiv.org/abs/2303.05937) :airplane:
- `[TIP 2023]` Single-view Neural Radiance Fields with Depth Teacher [[paper]](https://arxiv.org/abs/2303.09952) :taxi:
- `[ECCV 2022]` InfiniteNature-Zero: Learning Perpetual View Generation of Natural Scenes from Single Images [[paper]](https://infinite-nature-zero.github.io/static/pdfs/InfiniteNatureZero.pdf) [[project page]](https://infinite-nature-zero.github.io/)
- `[SIGGRAPH 2022]` Single-View View Synthesis in the Wild with Learned Adaptive Multiplane Images [[paper]](https://arxiv.org/pdf/2205.11733.pdf) [[code]](https://github.com/yxuhan/AdaMPI) [[project page]](https://yxuhan.github.io/AdaMPI/) :airplane:
- `[CVPR 2022]` Efficient Geometry-aware 3D Generative Adversarial Networks [[paper]](https://arxiv.org/pdf/2112.07945.pdf) [[code]](https://github.com/NVlabs/eg3d) [[project page]](https://matthew-a-chan.github.io/EG3D/)
- `[CVPRW 2022]` Artistic Style Novel View Synthesis Based on A Single Image [[paper]](https://openaccess.thecvf.com/content/CVPR2022W/CVFAD/papers/Tseng_Artistic_Style_Novel_View_Synthesis_Based_on_a_Single_Image_CVPRW_2022_paper.pdf) [[code]](https://github.com/Kuan-Wei-Tseng/ArtNV) [[project page]](https://kuan-wei-tseng.github.io/ArtNV) :cloud:
- `[CVPR 2022]` 3D Photo Stylization: Learning to Generate Stylized Novel Views from a Single Image [[paper]](https://arxiv.org/pdf/2112.00169.pdf) [[code]](https://github.com/fmu2/3d_photo_stylization) [[project page]](http://pages.cs.wisc.edu/~fmu/style3d/) :cloud:
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

**Binocular-input** novel view synthesis. This list is not exhaustive.
- `[CVPR 2022]` 3D Moments from Near-Duplicate Photos [[paper]](https://3d-moments.github.io/static/pdfs/3d_moments.pdf) [[code]](https://github.com/google-research/3d-moments) [[project page]](https://3d-moments.github.io/) :leaves::cloud:
- `[CVPR 2022]` Stereo Magnification with Multi-Layer Images [[paper]](https://arxiv.org/pdf/2201.05023.pdf) [[code]](https://github.com/SamsungLabs/StereoLayers) [[project page]](https://samsunglabs.github.io/StereoLayers/) :airplane::gem:
- `[ICCV 2019]` Extreme View Synthesis [[paper]](https://arxiv.org/pdf/1812.04777) [[code]](https://github.com/NVlabs/extreme-view-synth)
- `[CVPR 2019]` Pushing the Boundaries of View Extrapolation with Multiplane Images [[paper]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Srinivasan_Pushing_the_Boundaries_of_View_Extrapolation_With_Multiplane_Images_CVPR_2019_paper.pdf) :airplane:
- `[SIGGRAPH 2018]` Stereo Magnification: Learning View Synthesis using Multiplane Images [[paper]](https://dl.acm.org/doi/pdf/10.1145/3197517.3201323) [[code]](https://github.com/google/stereo-magnification) [[project page]](https://tinghuiz.github.io/projects/mpi/) :airplane:

3D photography of other kinds, such as relying on multi-view input, using modalities other than natural images, using generative methods without explicit 3D modeling.
- `[SIGGRAPH 2023]` ViP-NeRF: Visibility Prior for Sparse Input Neural Radiance Fields [[paper]](https://arxiv.org/abs/2305.00041) [[code]](https://github.com/NagabhushanSN95/ViP-NeRF) [[project page]](https://nagabhushansn95.github.io/publications/2023/ViP-NeRF.html) :taxi:
- `[CVPR 2023]` Painting 3D Nature in 2D: View Synthesis of Natural Scenes from a Single Semantic Mask [[paper]](https://arxiv.org/abs/2302.07224) [[project page]](https://zju3dv.github.io/paintingnature/) :gem:
- `[ICLR 2023]` Make-A-Video: Text-to-Video Generation without Text-Video Data [[paper]](https://arxiv.org/abs/2209.14792) [[project page]](https://make-a-video.github.io/)
- `[ECCV 2022]` SinNeRF: Training Neural Radiance Fields on Complex Scenes from a Single Image [[paper]](https://arxiv.org/pdf/2204.00928.pdf) [[code]](https://github.com/Ir1d/SinNeRF) [[project page]](https://vita-group.github.io/SinNeRF/) :taxi:
- `[CVPR 2022]` Look Outside the Room: Synthesizing A Consistent Long-Term 3D Scene Video from A Single Image [[paper]](https://arxiv.org/abs/2203.09457) [[code]](https://github.com/xrenaa/Look-Outside-Room) [[project page]](https://xrenaa.github.io/look-outside-room/)
- `[ICCV 2021]` Geometry-Free View Synthesis: Transformers and no 3D Priors [[paper]](https://arxiv.org/pdf/2104.07652.pdf) [[code]](https://github.com/CompVis/geometry-free-view-synthesis) [[project page]](https://compvis.github.io/geometry-free-view-synthesis/)
- `[ICCV 2021]` Learning to Stylize Novel Views [[paper]](https://arxiv.org/pdf/2105.13509.pdf) [[code]](https://github.com/hhsinping/stylescene) [[project page]](https://hhsinping.github.io/3d_scene_stylization/) :cloud:
- `[ICCV 2021]` Putting NeRF on a Diet: Semantically Consistent Few-Shot View Synthesis [[paper]](https://arxiv.org/pdf/2104.00677.pdf) [[code]](https://github.com/ajayjain/DietNeRF) [[project page]](https://www.ajayj.com/dietnerf) :taxi:
- `[ICCV 2017]` Personalized Cinemagraphs using Semantic Understanding and Collaborative Learning [[paper]](https://openaccess.thecvf.com/content_ICCV_2017/papers/Oh_Personalized_Cinemagraphs_Using_ICCV_2017_paper.pdf)

## 3D Photography Videos
3D Photography with dynamics. The works that use a single image as input:
- `[ACM MM 2023]` Make-It-4D: Synthesizing a Consistent Long-Term Dynamic Scene Video from a Single Image [[paper]](https://arxiv.org/abs/2308.10257) :leaves::cloud:
- `[IJCAI 2023]` Learning 3D Photography Videos via Self-supervised Diffusion on Single Images [[paper]](https://arxiv.org/abs/2302.10781)
- `[CVPR 2023]` 3D Cinemagraphy from a Single Image [[paper]](https://arxiv.org/abs/2303.05724) [[code]](https://github.com/xingyi-li/3d-cinemagraphy) [[project page]](https://xingyi-li.github.io/3d-cinemagraphy/) :leaves::cloud:

The works with multi-view input:
- `[arXiv 2024]` LoopGaussian: Creating 3D Cinemagraph with Multi-view Images via Eulerian Motion Field [[paper]](https://arxiv.org/abs/2404.08966) [[code]](https://github.com/Pokerlishao/LoopGaussian) [[project page]](https://pokerlishao.github.io/LoopGaussian/) :cloud:
- `[CVPR 2023]` 3D Video Loops from Asynchronous Input [[paper]](https://arxiv.org/abs/2303.05312) [[code]](https://github.com/limacv/VideoLoop3D) [[project page]](https://limacv.github.io/VideoLoop3D_web/) :airplane:

## Cinemagraph (Dynamics or Motion Generation)
**Landscape Animation**: running water, moving clouds, etc.
- `[CVPR 2024]` StyleCineGAN: Landscape Cinemagraph Generation using a Pre-trained StyleGAN [[paper]](https://arxiv.org/abs/2403.14186) [[code]](https://github.com/jeolpyeoni/StyleCineGAN) [[project page]](https://jeolpyeoni.github.io/stylecinegan_project/)
- `[TOG 2023]` Text-Guided Synthesis of Eulerian Cinemagraphs [[paper]](https://arxiv.org/abs/2307.03190) [[code]](https://github.com/text2cinemagraph/artistic-cinemagraph) [[project page]](https://text2cinemagraph.github.io/website/)
- `[SA 2022]` Water Simulation and Rendering from a Still Photograph [[paper]](https://dl.acm.org/doi/pdf/10.1145/3550469.3555415) [[project page]](https://rsugimoto.net/WaterAnimationProject/)
- `[ICCV 2023]` DiffDreamer: Consistent Single-view Perpetual View Generation with Conditional Diffusion Models [[paper]](https://arxiv.org/abs/2211.12131) [[project page]](https://primecai.github.io/diffdreamer)
- `[ICLR 2023]` Towards Smooth Video Composition [[paper]](https://arxiv.org/abs/2212.07413) [[project page]](https://genforce.github.io/StyleSV)
- `[ICCV 2023]` Simulating Fluids in Real-World Still Images [[paper]](https://arxiv.org/pdf/2204.11335.pdf) [[code]](https://github.com/simon3dv/SLR-SFS) [[project page]](https://slr-sfs.github.io/)
- `[CVPR 2022]` Controllable Animation of Fluid Elements in Still Images [[paper]](https://arxiv.org/pdf/2112.03051v1.pdf) [[project page]](https://controllable-cinemagraphs.github.io/)
- `[CVPR 2022]` StyleGAN-V: A Continuous Video Generator with the Price, Image Quality and Perks of StyleGAN2 [[paper]](https://kaust-cair.s3.amazonaws.com/stylegan-v/stylegan-v-paper.pdf) [[code]](https://github.com/universome/stylegan-v) [[project page]](https://universome.github.io/stylegan-v)
- `[CVPR 2021]` Animating Pictures with Eulerian Motion Fields [[paper]](https://eulerian.cs.washington.edu/animating_pictures_2020.pdf) [[project page]](https://eulerian.cs.washington.edu/)
- `[MultiMedia 2021]` Learning Fine-Grained Motion Embedding for Landscape Animation [[paper]](https://arxiv.org/pdf/2109.02216.pdf)
- `[ECCV 2020]` DeepLandscape: Adversarial Modeling of Landscape Videos [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123680256.pdf) [[code]](https://github.com/saic-mdal/deep-landscape) [[project page]](https://saic-mdal.github.io/deep-landscape/)
- `[ECCV 2020]` DTVNet: Dynamic Time-lapse Video Generation via Single Still Image [[paper]](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500290.pdf) [[code]](https://github.com/zhangzjn/dtvnet)
- `[SIGGRAPH Asia 2019]` Animating Landscape: Self-Supervised Learning of Decoupled Motion and Appearance for Single-Image Video Synthesis [[paper]](https://arxiv.org/pdf/1910.07192.pdf) [[code]](https://github.com/endo-yuki-t/Animating-Landscape) [[project page]](http://www.cgg.cs.tsukuba.ac.jp/~endo/projects/AnimatingLandscape/)
- `[CVPR 2018]` Learning to Generate Time-lapse Videos Using Multi-stage Dynamic Generative Adversarial Networks [[paper]](https://arxiv.org/pdf/1709.07592.pdf) [[code]](https://github.com/weixiong-ur/mdgan) [[project page]](https://sites.google.com/site/whluoimperial/mdgan)

Other papers.
- `[arXiv 2024]` Explorative Inbetweening of Time and Space [[paper]](https://arxiv.org/abs/2403.14611) [[project page]](https://time-reversal.github.io/)
- `[arXiv 2024]` Motion-I2V: Consistent and Controllable Image-to-Video Generation with Explicit Motion Modeling [[paper]](https://arxiv.org/abs/2401.15977) [[project page]](https://xiaoyushi97.github.io/Motion-I2V/)
- `[arXiv 2023]` AnimateAnything: Fine-Grained Open Domain Image Animation with Motion Guidance [[paper]](https://arxiv.org/abs/2311.12886) [[code]](https://github.com/alibaba/animate-anything/) [[project page]](https://animationai.github.io/AnimateAnything/)
- `[arXiv 2023]` LivePhoto: Real Image Animation with Text-guided Motion Control [[paper]](https://arxiv.org/abs/2312.02928) [[code]](https://github.com/XavierCHEN34/LivePhoto) [[project page]](https://xavierchen34.github.io/LivePhoto-Page/)
- `[arXiv 2023]` DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors [[paper]](https://arxiv.org/abs/2310.12190) [[code]](https://github.com/AILab-CVC/VideoCrafter)
- `[CVPR 2024]` Generative Image Dynamics [[paper]](https://arxiv.org/abs/2309.07906) [[project page]](https://generative-dynamics.github.io/)
- `[arXiv 2023]` DragNUWA: Fine-grained Control in Video Generation by Integrating Text, Image, and Trajectory [[paper]](https://arxiv.org/abs/2308.08089) [[project page]](https://www.microsoft.com/en-us/research/project/dragnuwa/)
- `[arXiv 2023]` Motion-Conditioned Diffusion Model for Controllable Video Synthesis [[paper]](https://arxiv.org/abs/2304.14404) [[project page]](https://tsaishien-chen.github.io/MCDiff/)
- `[CVPR 2023]` Conditional Image-to-Video Generation with Latent Flow Diffusion Models [[paper]](https://arxiv.org/abs/2303.13744) [[code]](https://github.com/nihaomiao/CVPR23_LFDM)
- `[CVPR 2023]` Blowing in the Wind: CycleNet for Human Cinemagraphs from Still Images [[paper]](https://arxiv.org/abs/2303.08639)
- `[ICCV 2021]` iPOKE: Poking a Still Image for Controlled Stochastic Video Synthesis [[paper]](https://arxiv.org/pdf/2107.02790.pdf) [[code]](https://github.com/CompVis/ipoke) [[project page]](https://compvis.github.io/ipoke/)
- `[CVPR 2021]` Stochastic Image-to-Video Synthesis Using cINNs [[paper]](https://arxiv.org/pdf/2105.04551.pdf) [[code]](https://github.com/CompVis/image2video-synthesis-using-cINNs) [[project page]](https://compvis.github.io/image2video-synthesis-using-cINNs/)
- `[CVPR 2021]` Understanding Object Dynamics for Interactive Image-to-Video Synthesis [[paper]](https://arxiv.org/pdf/2106.11303.pdf) [[code]](https://github.com/CompVis/interactive-image2video-synthesis) [[project page]](https://compvis.github.io/interactive-image2video-synthesis/)
- `[SIGGRAPH 2021]` Endless Loops: Detecting and Animating Periodic Patterns in Still Images [[paper]](https://storage.googleapis.com/ltx-public-images/Endless_Loops__Detecting_and_animating_periodic_patterns_in_still_images.pdf) [[project page]](https://pub.res.lightricks.com/endless-loops/)
- `[ECCV 2018]` Flow-Grounded Spatial-Temporal Video Prediction from Still Images [[paper]](https://arxiv.org/pdf/1807.09755.pdf) [[code]](https://github.com/Yijunmaverick/FlowGrounded-VideoPrediction)
- `[CVPR 2018]` Controllable Video Generation with Sparse Trajectories [[paper]](https://vision.cornell.edu/se3/wp-content/uploads/2018/03/1575.pdf) [[code]](https://github.com/zekunhao1995/ControllableVideoGen) [[project page]](http://www.cs.cornell.edu/~xhuang/publication/videogen/)
- `[CVPR 2018]` MoCoGAN: Decomposing Motion and Content for Video Generation [[paper]](https://arxiv.org/pdf/1707.04993.pdf) [[code]](https://github.com/sergeytulyakov/mocogan)
