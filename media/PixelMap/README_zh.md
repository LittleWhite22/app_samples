# 图像<a name="ZH-CN_TOPIC_0000001127379371"></a>

-   图像模块支持图像业务的开发，常见功能如图像解码、图像编码、基本的位图操作、图像编辑等。

    当然，也支持通过接口组合来实现更复杂的图像处理逻辑，详细如下：

    \* 图像解码：图像解码就是将所支持格式的存档图片解码成统一的 PixelMap 图像，用于后续图像显示或其他处理，比如旋转、缩放、裁剪等。

    当前支持格式包括 JPEG、PNG、GIF、HEIF、WebP、BMP。

    \* 图像编码：图像编码就是将 PixelMap 图像编码成不同存档格式图片，用于后续其他处理，比如保存、传输等。当前仅支持 JPEG 格式。

    \* 位图操作：位图操作就是指对 PixelMap 图像进行相关的操作，比如创建、查询信息、读写像素数据等。
