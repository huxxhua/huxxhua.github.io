# 利用 Cloudflare Workers 自建 Docker 镜像


### 创建 Workers 项目

具体搭建workers过程 可参考： [hammal](https://github.com/ImSingee/hammal?tab=readme-ov-file &#34;Visit Github!&#34;)

{{&lt; figure src=&#34;https://cdn.guanhua.org/gh/huxxhua/huxxhua.github.io/cdnimg/CleanShot%202024-10-23%20at%2023.57.24%402x.png&#34; title=&#34;Workers&#34; &gt;}}

### 绑定一个自定义域名
&gt; 默认的 workers.dev 域名会被墙

二级域名的开通就不像其它服务商的域名解析那么简单。这一步当时搞了很久，因为本来在cloudflare就有一个域名，想通过新增一个二级域名，但是死活不生效。
最后还是注册一个新域名，然后新增一条DNS绑定workers即可
{{&lt; figure src=&#34;https://cdn.guanhua.org/gh/huxxhua/huxxhua.github.io/cdnimg/CleanShot%202024-10-23%20at%2023.59.50%402x.png&#34; title=&#34;Workers 自定义路由&#34; &gt;}}

在宝塔配置好加速URL，可正常拉取docker镜像
{{&lt; figure src=&#34;https://cdn.guanhua.org/gh/huxxhua/huxxhua.github.io/cdnimg/CleanShot%202024-10-24%20at%2000.03.12%402x.png&#34; title=&#34;宝塔配置加速URL&#34; &gt;}}

---


---

> 作者: guanhua  
> URL: https://www.guanhua.org/posts/90b85a7/  

