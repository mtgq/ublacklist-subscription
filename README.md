# Google 中文搜索结果中屏蔽某些网站

###### 说明：这是自己使用的一个订阅规则，平常在使用谷歌搜索中文的时候碰到了垃圾网站就随手 black 了，然后把这个地址再更新到文件中。

#### uBlacklist 有什么作用

###### uBlacklist 是一个移除预定义规则中的网站出现在你的搜索结果中的一个浏览器扩展，目前支持的搜索引擎有 Google DuckDuckGo 等。使用它可以屏蔽垃圾网站或机器翻译网站出现在你的搜索结果中，从而可以让你更加高效的获取到有用的搜索结果，以及享受更好的搜索体验。

#### 安装

###### 应用商店下载地址如下: [Chrome Web Store](https://chrome.google.com/webstore/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe) / [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/ublacklist/)

#### 收集的其他人订阅地址

(推荐)https://github.com/cobaltdisco/Google-Chinese-Results-Blocklist

https://github.com/liubiantao/uBlacklist-Websites

https://github.com/kurikomoe/KurikoRulesets/blob/master/ublacklist.txt

https://github.com/gyli/Blocklist/blob/master/BLOCKLIST_uBlacklist


#### 自定义规则使用

一、拦截域名

对应的正则格式： `/\S+\.(it|pl|site|de|be|club|vn|mx|fr|buzz)/` 拦截以 it、pl、 site、de、 be，club 等结尾的域名

原文地址：https://github.com/cobaltdisco/Google-Chinese-Results-Blocklist/issues/45

二、屏蔽以 m. 开头的手机页面

对应的正则格式：`/^https?:\/\/m\./`

原文地址：https://github.com/cobaltdisco/Google-Chinese-Results-Blocklist/issues/46

