### 启动

1. 依次运行

2. 使用自定义方式启动webui，除了安全模式不勾选，其他的都要勾选。

   ```
   cd /root/autodl-tmp/stable-diffusion-webui && /root/miniconda3/envs/xl_env/bin/python launch.py --disable-safe-unpickle  --port=6006 --deepdanbooru --xformers --enable-insecure-extension-access --api --cors-allow-origins=https://www.painthua.com --no-half-vae --disable-nan-check --no-gradio-queue 
   ```

   

3. 加以下命令可以在公网使用：

   ```
   --share --listen
   ```

### 模型加载和文件下载

暂时用阿里云

本地目录：

```
D:\AI绘画
```



### 设置深色模式

关于StableDiffusionWebUi切换夜间模式的办法： 在网址后面加一个参数即可(?__theme=dark) 白天模式的参数是(?__theme=light) 

### 插件安装

其他插件用插件工具安装

controlnet在download.ipynb文件里运行安装

### prompt翻译工具

阿里云翻译好用



