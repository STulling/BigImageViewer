# BigImageViewer
Big image viewer supporting pan and zoom, using python flask and leaflet.js

超大图像浏览，支持缩放和平移。

### 需求 where to use

- 医疗影像
- 卫星遥感影像
- 超大的全景图

### 支持格式 image format

- png
- jpg
- tif（遥感影像辐射定标之后）

### 用法 how to run

​	1、生成瓦片 generate image tiles

```bash
python tiles_generator/deepzoom.py <raw_big_image_path> -s 256 -d <tiles_save_path> -f jpg
```

***NOTES: python 2.7 with pillow(PIL) installed***

​	2、修改配置 modify web configurations





