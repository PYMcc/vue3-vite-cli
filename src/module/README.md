 ## 阅读我！！
 
 此目录中配置多模块 每一个文件夹将视为一个模块内置包含 index.html（入口文件）   
 目的是将所有模块分开实现，当你需要某些模块的引入时，可直接接入路由使用不同的打包命令即可  

---
 
 当然此项目结构可根据业务不同进行修改,这里只是演示推荐。
 当前的模块区分 是基于vite的import.meta.env 实现，后续如果有更好的方法，我将替换。相对来说vite的多模块配置还是较为繁琐的。
  <hr/>
 
 ------- module 文件夹放置 所有模块目录  
 ---------- module1 文件夹放置 当前第一个模块  