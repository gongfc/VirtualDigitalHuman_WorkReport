# VirtualDigitalHuman_WorkReport
This is a work report repository about Virtual Digital Human, including 3D Human Head, 3D Human Bodies, 3D Human Motions, 3D Human Textures, and 3D Virtual Tryon. <br/>
I have compiled the research results into the work report in PDF format, PDF can be found [here](VirtualDigitalHuman_WorkReport.pdf).<br/>

This repository mainly contains one demos, as well as their implementation details and pipelines

## Demo1 : Using facial detail methods and contrastive learning methods to improve FFHQ-UV
1. The following image : <br/>
(a).FFHQ-UV method: The high fidelity and low fidelity human faces of the original FFHQ-UV algorithm  <br/>
(b).Face detail method: similarity is more than 90%, basically identical, and has strong adaptability <br/>
(c).Comparative learning method: 80% similarity, able to handle skin tone and lighting issues, only able to have a similar appearance <br/>
<p align="center">
<img src="FFHQ-UV改进方式的效果比较.jpg">
</p>
2. The following GiF-File : <br/>
(a).Using Facial-Detail-Methods to reconstruct 某人's 3D face,           <br/>
(b).Using contrastive learning methods to reconstruct 鲁迅's 3D face，   <br/>
and all Add mouth shaped voice broadcasting and actions to generate 3D digital humans. <br/>
<table><tr>
<td><img src=使用人脸细节方式重建XXX.gif border=0></td>
<td><img src=使用对比学习方式重建鲁迅.gif border=0></td>
</tr></table>

## Detail1 : Pipeline of 3D Human Reconstruction
<p align="center">
<img src="3D数字人重建流程.jpg">
</p>

## Detail2 : Flame-based Head Replacement
Different replacement methods were used to replace the heads of 27554smpl and smplx with flames.<br/>
27554Smpl is the body model of Demo1(3D Virtual Tryon), which contains 27554 vertices. Smplx is the body model of Demo2(3D Human Reconstruction).<br/>
The two replacement methods are as follows :
<p align="center">
<img src="Detail_FlameReplaceBodyHead.jpg">
</p>

## Reference
We have referred to many open source projects, and we have listed a few of them.<br/>
[SMPL](https://smpl.is.tue.mpg.de/)<br/>
[SMPLX](https://github.com/vchoutas/smplx)<br/>
[textured_smplx](https://github.com/qzane/textured_smplx)<br/>
[Mesh](https://github.com/MPI-IS/mesh)<br/>
[Flame](https://flame.is.tue.mpg.de/index.html)<br/>
[FLame2SMPLX](https://github.com/CvHadesSun/FLame2SMPLX)<br/>

[FACIAL](https://github.com/zhangchenxu528/FACIAL)<br/>
[FACEGOOD-Audio2Face](https://github.com/FACEGOOD/FACEGOOD-Audio2Face)<br/>
[voca](https://github.com/TimoBolkart/voca)<br/>
[meshtalk](https://github.com/facebookresearch/meshtalk)<br/>
[FaceFormer](https://github.com/EvelynFan/FaceFormer)<br/>

[Open3D](https://github.com/isl-org/Open3D)<br/>
[hifi3dface](https://github.com/tencent-ailab/hifi3dface)<br/>
[VideoPose3D](https://github.com/facebookresearch/VideoPose3D)<br/>
[RingNet](https://github.com/soubhiksanyal/RingNet)<br/>
[DECA](https://github.com/YadiraF/DECA)<br/>
[PIXIE](https://github.com/YadiraF/PIXIE)<br/>
[ICON](https://github.com/YuliangXiu/ICON)<br/>

[neural-blend-shapes](https://github.com/PeizhuoLi/neural-blend-shapes)<br/>
[deep-motion-editing](https://github.com/DeepMotionEditing/deep-motion-editing)<br/>
[RigNet](https://github.com/zhan-xu/RigNet)<br/>

[MultiGarmentNetwork](https://github.com/bharat-b7/MultiGarmentNetwork)<br/>
[TailorNet](https://github.com/chaitanya100100/TailorNet)<br/>
[pix2surf](https://github.com/aymenmir1/pix2surf)<br/>
[vto-garment-collisions](https://github.com/isantesteban/vto-garment-collisions)<br/>
[vto-learning-based-animation](https://github.com/isantesteban/vto-learning-based-animation)<br/>
[VirtualBones](https://github.com/non-void/VirtualBones)<br/>
[BCNet](https://github.com/jby1993/BCNet)<br/>

[squeezeformer](https://github.com/kssteven418/squeezeformer)<br/>
[TensorFlowASR](https://github.com/TensorSpeech/TensorFlowASR)<br/>
[TensorFlowTTS](https://github.com/TensorSpeech/TensorFlowTTS)<br/>
[Meta-TTS](https://github.com/SungFeng-Huang/Meta-TTS/)<br/>
[FastSpeech2](https://github.com/ming024/FastSpeech2)<br/>
