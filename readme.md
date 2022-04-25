# 三维全息、高保真、数字化科大校园

在当前虚拟现实、增强现实、元宇宙等领域高速发展并在各行各业应用落地的时代，仅采用简单图形标注的地图、局限于个别角度的全景图像等呈现方式已无法满足大众对于如大学校园等景点、园区的沉浸式观赏与浏览。自从2020年以来，受疫情等因素的影响导致校园封闭，因此校外人士无法自由进出校园来参观如樱花大道等校园景色；另外，对于身处外地，但对科大校园有憧憬的学生或社会人士，受限于距离、时间等因素，无法到学校来实际参观并体验校园内的自然风景与人文景点。为了解决上述痛点需求，中科大[USTC-3DV课题组](http://staff.ustc.edu.cn/~juyong/)启动了“数字化科大校园”项目，拟对整个科大校园进行三维全息、高保真数字化，为科大的宣传、招生、已毕业校友重温校园美好时光、校外人士了解科大校园等贡献科技力量。

### 科大校园地图现状

截止到当前这篇文章落成之时，笔者翻阅了整个科大学校主页，仅找到了如下两张简略地图。虽然该地图清楚地展示科大校园的位置坐标与校区组成，但功能非常有限，与科大的名校地位远远不符合。可以看出，该地图还仍然停留在缩略地图的颜色与标注，根本无法进一步浏览与如实观看科大校园内如少年班、老校门、郭沫若广场、樱花大道等老百姓心心向往的科大著名标志性景点。在如今手机地图高速且便捷的时代，以上两张地图无法给人们呈现出手机地图所能呈现的更多内容，而大众更加渴望的是观赏五彩缤纷的真实科大校园景色。

<table frame=void>	<!--使用table标签，且frame=void消除外边框-->
	<tr>		   <!--<tr>一行的内容<\tr>，<td>一个格子的内容<\td>-->
    <td><center><img src="./img/map.jpg"	
                     alt="科大地图"
                     width="427" height="240"/></center></td>	<!--<center>标签将图片居中-->
    <td><center><img src="./img/map2.jpg"
                     alt="科大地图"
                     width="427" height="240"/></center></td>
    </tr>
</table>

而通过其他途径所获得的科大校园展示，更多可能也只停留在照片与视频的层面上，在某种程度上既丧失了校园景色的立体真实美感、也缺少了身临其境的交互体验，仍然停留在“看一眼”的层面上，十分缺乏吸引力与审美性。

<table frame=void>	<!--使用table标签，且frame=void消除外边框-->
	<tr>		   <!--<tr>一行的内容<\tr>，<td>一个格子的内容<\td>-->
    		<td><center><img src="./img/fig1.jpg"	
                     alt="科大景色"
                     width="250" height="180"/></center></td>	<!--<center>标签将图片居中-->
    		<td><center><img src="./img/fig5.jpg"
                     alt="科大景色"
                     width="250" height="180"/></center></td>
		<td><center><img src="./img/fig3.jpg"
                     alt="科大景色"
                     width="250" height="180"/></center></td>
		<td><center><img src="./img/fig4.jpg"
                     alt="科大景色"
                     width="250" height="180"/></center></td>
    </tr>
</table>


再或者，对于前几年兴起的360度全景照片展示，也只能局限于固定尺度层面以及固定视角的效果展示，当浏览者想要拉近放大观看时就会出现模糊不清的问题，另一个致命的缺点是，若想查看不同尺度不同视角下的校园风景时，比如从俯瞰郭沫若广场到正面水平视角观赏，则需要切换不同的360度全景照片，增加了浏览者操作的不便性。



https://user-images.githubusercontent.com/78888718/164979683-75e0983d-e4b7-45bf-8b71-5fa7538cbbf4.mp4



综合当下不同途径的科大校园景色展示的诸多弊端，足见，我们亟需一个符合科大名校地位的高大上（高保真、大规模、多尺度）科大校园数字化地图与三维模型，以便满足校内外人士对科大校园的浏览与体验需求。

### 数字化校园目标

基于上述的实际应用需求，以及将科研成果写到祖国大地的愿景，中科大[USTC-3DV课题组](http://staff.ustc.edu.cn/~juyong/)启动了“数字化科大校园”这一项目，该项目拟达到以下目标：

- 目标一：对科大校园进行三维地图建模，以用于全景地貌、测量、导航等功能；
- 目标二：在任意地点对任意视角进行三维高保真全息渲染，其渲染真实性要达到高清相机所拍摄的图像效果。

我们以谷歌今年通过车载采集设备对旧金山市几个街区所做的全息高保真数字化工作为例来说明我们拟达到的效果，具体工作介绍见[旧金山市的高保真数字化](https://www.51cto.com/article/701350.html)：

   <center class="half">    
       <img src="./gif/video_4.gif" width="850" height="480"/> 
   </center>


课题组还会不断优化算法，以达到更加优秀的效果，努力追求校园景色的高逼真、多尺度还原，给使用者更佳的浏览与观赏体验！

- 目标三：将科大校园内具有特殊意义的地方单独重建恢复出来，如名人雕像、孺子牛、少年班、老北门等具有标志性建筑或景观。 

### 当前进展与工作安排

截止到目前，本项目已取得了部分进展：

1. 利用无人机与GoPro，对科大校园已经采集了部分用于重建工作的数据：科大校园内雕像的多视角视频与图像、樱花大道的多尺度与多视角视频、郭沫若广场的多尺度与多视角视频。
   

https://user-images.githubusercontent.com/78888718/164983941-3f9ae62a-bbf7-4d64-b6ab-00ec6668bf6b.mp4


2. 对校内的部分雕像已经完成了三维几何重建与全息渲染工作。

   <table frame=void>	<!--使用table标签，且frame=void消除外边框-->
   	<tr>		   <!--<tr>一行的内容<\tr>，<td>一个格子的内容<\td>-->
       <td><center><img src="./img/fig6.jpg"	
                        alt="杨振宁原图"
                        width="427" height="240"/></center></td>	<!--<center>标签将图片居中-->
       <td><center><img src="./gif/yzn.gif"
                        alt="杨振宁渲染"
                        width="427" height="240"/></center></td>
       </tr>
   </table>

3. 对郭沫若广场进行了三维全息渲染，效果逼真，高度还原现实真实场景。

   下面的视频展示了根据我们对郭沫若广场的三维全息重建进行自由漫走的展示效果：  
   
   
https://user-images.githubusercontent.com/78888718/164982423-0b84b76f-1f33-4f12-8c8d-4b8aa3c02f8d.mp4


   我们还对渲染的结果与真实拍摄图像进行对比，下图左侧为真实图片，**右侧为渲染图片**，可以看出由我们重建出来的模型可以得到高质量的渲染效果。
   <table frame=void>
   	<tr>
       <td><center><img src="./img/ori1.jpg"
                        alt="展示"
                        width="427" height="241"/></center></td>
       <td><center><img src="./img/res1.jpg"
                        alt="Typora-Logo"
                        width="427" height="241"/></center></td>
       </tr>
       <tr>	<!--第二行-->
       <td><center><img src="./img/ori2.jpg"
                        alt="Typora-Logo"
                        width="427" height="241"/></center></td>
       <td><center><img src="./img/res2.jpg"
                        alt="Typora-Logo"
                        width="427" height="241"/></center></td>
       </tr>
   </table>

   我们进一步给出动态的GIF对比图来说明我们三维全息渲染效果的优秀：
   <center class="half">    
       <img src="./gif/compare.gif" width="850" height="480"/> 
   </center>
   
  
   关于后续工作，课题组的安排如下：
   - 对已经采集的雕像（如：郭沫若、严济慈、钱学森、华罗庚等雕像）进行高精度三维几何重建、高保真全息渲染；
   - 在课题组购买所需的设备后，计划对科大校园进行多尺度、多视角、大规模的进行数据采集与处理工作，尤其针对少年班、老校门等标志性建筑进行重点采集；
   - 由采集到的多视角图像、激光雷达所采集到的点云图像对校园进行三维重建，再结合课题组所研发的三维重建、神经渲染等技术进行三维全息重建与渲染等；
   - 对标志性建筑、雕像等进行额外重建，并进行渲染。

### 所需资源

为了完成上述目标，课题组还需购买相应的采集设备与计算设备，以及在数据采集、数据标注等方面的协助，具体包括以下内容：
1. 用于采集多视角图像数据的各类型设备：运动型相机、多种型号的无人机、车载相机等；
2. 用于采集场景几何数据的设备：激光雷达；
3. 用于重建与渲染的计算设备：高性能服务器、高配置显卡电脑，GPU资源等；
4. 在采集过程中，还需要聘请一定数量的志愿者通过各种采集设备来对校园内的各个地方进行采集。
