
使用激光头需要在选型时进行正确的选型，使用时进行正确的参数配置，以下是在项目中激光
头型号选择需要注意的参数以及使用时根据使用场景需要配置的激光头参数

### 激光头选型参数说明 

![激光头选型](image-12.png)

类似2D相机镜头选型中需要注意的物距、焦距以及视野等，在3D激光头的选型中也需要根据项
目场景选择合适的激光头，下面对选型时需要注意的参数进行如下说明： <br>

**参考距离（CD）**： 表示激光头的安装高度（距离被测物上表面），在此安装高度下进行采
集才可以采集到有效数据，选型时也需要根据现场情况查看是否满足所选型号的安装高度，此数
据用作安装参考数据，后续使用高度还需要进行细调，详见： <br>
**Z 轴高度（FS）**：此数据表示可以检测的产品厚度，只有厚度之内的产品才可以采集到数据。 <br>
**X  轴  宽  度**：此数据表示可以采集的产品宽度，产品长度是由设置参数中的批处理点数
确定的；因激光是类似三角形式散发出去的，所以在有效的采集高度内，距离激光头越近扫描的宽
度越小，距离激光头越远扫描的宽度越大。 <br>
**Z  轴重复精度**：Z方向上同一产品反复多次采集时的重复采集精度。 <br>
**X  轴重复精度**：X方向上同一产品反复多次采集时的重复采集精度。 <br>
**X  轴数据间隔**：表示X方向上每两个采样点之间的间距，即X方向采样。<br> 
**X  轴轮廓点数**：X方向上采集点的最大数量。 <br>
**扫  描 速  度**：即采样频率，表示每秒可以扫描到的脉冲数量；取其倒数表示扫描一次使用的
时间，用此参数可以评估最短的检测周期，需要注意的是：采样频率在2500以内时Z方向扫描范围为
给出的完整范围，采样频率大于2500小于等于4500时Z方向扫描范围为给出范围的1/2，采样频率大于
4500小于等于8000时Z方向扫描范围为给出范围的1/4，需要考量满足检测周期的情况下是否满足测量
高度。 <br>
当然除此之外也需要注意一下安装尺寸，确保在给定的空间下可以安装激光头


