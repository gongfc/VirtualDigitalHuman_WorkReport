# VirtualDigitalHuman_WorkReport(正在完善中)
This is a work report repository about Virtual Digital Human, including 3D Human Head, 3D Human Bodies, 3D Human Motions, 3D Human Textures, and 3D Virtual Tryon. <br/>
I have compiled the research results into the work report in PDF format, PDF can be found [here](VirtualDigitalHuman_WorkReport.pdf).<br/>
All materials provided by this repository, including MP4, GIF, PDF, JPG, have also been put on [pan.baidu.com](https://pan.baidu.com/s/1DAcX4ngI5wYj3Ad_goTp4w?pwd=7y69)<br/>

This repository mainly contains two demos, as well as their implementation details and pipelines

## Demo1 : 3D Virtual Tryon
Try on various clothes to different postures and shapes of body models, and replace their heads with Flames(with facial expression). <br/>
Finally, the 3D virtual human with voice broadcast function is generated.<br/>
The GIF of the final results and the implementation process are shown below : <br/>
(MP4 with sound of the final results, please download the [3DVirtualTryon.mp4](3DVirtualTryon.mp4) and [3DVirtualTryonTurn.mp4](3DVirtualTryonTurn.mp4). They are also included in the [pan.baidu.com](https://pan.baidu.com/s/1DAcX4ngI5wYj3Ad_goTp4w?pwd=7y69) )
<table><tr>
<td><img src=3DVirtualTryon_Fps50_W270H480.gif border=0></td>
<td><img src=3DVirtualTryonTurn_Fps50_W270H480.gif border=0></td>
</tr></table>
<p align="center">
<img src="3DVirtualTryon_Pipeline.jpg">
</p>

## Demo2 : 3D Human Reconstruction
Through the front and back pictures and action videos of the human body, Smplx body models and corresponding textures and actions are generated.
Replace the head with Flames(with facial expression) in a different way than above.<br/>
Finally, Another 3D virtual human with voice broadcast function is generated.<br/>
The GIF of the final results and the implementation process are shown below : <br/>
(MP4 with sound of the final results, please download the [3DHumanReconstruction.mp4](3DHumanReconstruction.mp4). It is also included in the [pan.baidu.com](https://pan.baidu.com/s/1DAcX4ngI5wYj3Ad_goTp4w?pwd=7y69) )
<table><tr>
<td><img src=3DHumanReconstruction_Fps50_W270H480.gif border=0 width=270 height=480></td>
</tr></table>

<p align="center">
<img src="3DHumanReconstruction_Pipeline.jpg">
</p>

## Detail1 : Voice generated flames facial expression
We generate voice through TTS based on text data and then generate flames facial expression (e.g., lips and wink) through VOCA. <br/>
Both demos use the flames face expression (e.g., lips and wink). <br/>
The text data we use is: "8日下午，习--总--在四川省宜宾市先后考察了三江口、宜宾学院、极米光电有限公司，了解长江流域生态修复保护、高校毕业生就业、企业自主创新等情况。". Sensitive words were replaced with ‘-’.<br/>
The GIF of the final results is shown below : <br/>
(MP4 with sound of the final results, please download the [VOCAOutput_XJPDY.mp4](VOCAOutput_XJPDY.mp4). It is also included in the [pan.baidu.com](https://pan.baidu.com/s/1DAcX4ngI5wYj3Ad_goTp4w?pwd=7y69) )
<table><tr>
<td><img src=VOCAOutput_XJPDY_Fps50_W800H800.gif border=0 width=400 height=400></td>
</tr></table>

## Detail2 : Flames-based Head Replacement
Different replacement methods were used to replace the heads of 27554smpl and smplx with flames.<br/>
27554Smpl is the body model of Demo1(3D Virtual Tryon), which contains 27554 vertices. Smplx is the body model of Demo2(3D Human Reconstruction).<br/>
The two replacement methods are as follows :
<p align="center">
<img src="Detail_FlameReplaceBodyHead.jpg">
</p>
## Reference
