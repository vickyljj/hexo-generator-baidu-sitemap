# Sitemap generator

 Generate sitemap.
添加了百度移动协议
 ## Install

 if your hexo version is 2.x.x, you should install as follow:

 ``` bash
 $ npm install hexo-generator-baidu-sitemap@0.0.8 --save
 install process ...
 ```

 if version is 3.x.x, you should install as follow:

 ``` bash
 $ npm install hexo-generator-baidu-sitemap@0.1.4 --save
 install process ...
 ```

 ## Update

 ``` bash
 $ npm remove hexo-generator-baidu-sitemap
 install process ...
 $ npm install hexo-generator-baidu-sitemap --save
 ```

 if your hexo version is 2.x.x, you can configure this plugin in `_config.yml`.
 
 baidusitemap:
     path: baidusitemap.xml
 ```

 if version is 3.x.x, you should configure this plugin in `_config.yml`.

 ``` yaml
 baidusitemap:
 path: baidusitemap.xml

 ```

 - **path** - Sitemap path. (Default: baidusitemap.xml)

 ## Errors

 Maybe response is "hexo is not definded",then you should:

 ``` bash
 $ cd node_modules/hexo-generator-baidu-sitemap/
 node_modules/hexo-generator-baidu-sitemap/
 $ npm install
 ```
