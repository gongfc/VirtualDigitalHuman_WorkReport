# VirtualDigitalHuman_WorkReport(正在完善中)

## 3DVirtualTryon
<script src="./hls.min.js"></script>
<video id="video" width="279" height="480" autoplay="autoplay" muted="muted" controls="controls">
</video>
 
<script>
    // 调用这个方法加载视频源
	function reload(src){
		var video = document.getElementById('video'); // 获取 video 标签
		var hls = new Hls(); // 实例化 Hls 对象
		hls.loadSource(src); // 传入路径
		hls.attachMedia(video);
		hls.on(Hls.Events.MANIFEST_PARSED,function() {
			      video.play(); // 调用播放 API
	    });
	    video.muted=false;
	}
</script>
reload("3DVirtualTryon.mp4")

<table><tr>
<td><img src=3DVirtualTryon_Fps50_W270H480.gif border=0></td>
<td><img src=3DVirtualTryonTurn_Fps50_W270H480.gif border=0></td>
</tr></table>
<p align="center">
<img src="3DVirtualTryon_Pipeline.jpg">
</p>

## 3DHumanReconstruction

<table><tr>
<td><img src=3DHumanReconstruction_Fps50_W270H480.gif border=0 width=270 height=480></td>
</tr></table>

<p align="center">
<img src="3DHumanReconstruction_Pipeline.jpg">
</p>
