---
home: true
heroImage: /img/logo.svg
heroText: LiteFlow
tagline: 🚀Small but powerful rules engine
actionText: 🧩New version, New expression language!
actionLink: /pages/5816c5/
bannerBg: none # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量
features: # 可选的
  - title: 🍀Lightweight & Powerful
    details: The small body contains big energy, simple learning cost, a few minutes to get started. It can accomplish complex rule orchestration.
  - title: 🌸Elegant & Efficient
    details: All logic is component. Stable operation on the core systems of major companies with excellent performance.
  - title: 🌼Rich Support
    details: No matter what architecture you have, it's all supported. Rich features, including hot refresh, nested rules, external storage, etc.

# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表
postList: none

---

<Notice :data="$frontmatter.notices"/>

<br/><br/>

## 🌈Special Sponsors

::: cardList
```yaml
- name: ERD Online
  desc: Out-of-the-box database modeling, product version management software.
  avatar: /img/donate/erd.png
  link: https://portal.zerocode.net.cn/
  bgColor: '#f8c567' # 可选，默认var(--bodyBg)。颜色值有#号时请添加单引号
  textColor: '#1f2328' # 可选，默认var(--textColor)

```
:::
<br/>

<p align="center">
  <a class="become-sponsor" href="/pages/fb599d/">Become Sponsor</a>
</p>

<style>
.become-sponsor{
  padding: 8px 20px;
  display: inline-block;
  color: #E01E5A;
  border-radius: 30px;
  box-sizing: border-box;
  border: 2px solid #E01E5A;
}
</style>

<br/>

## 🍬Features
* **<font color=#E01E5A>Unified component definition:</font>** All logic is components, providing a unified way of component implementation for all logic, small size, big power.
* **<font color=#E01E5A>Lightweight rules:</font>** Based on the rules file to orchestrate the process, it only takes 5 minutes to learn the rules to get started.
* **<font color=#E01E5A>Multiple formats:</font>** The rules support xml, json and yml.
* **<font color=#E01E5A>Arbitrary arrangement:</font>** With LiteFlow rules you can easily do synchronous asynchronous mixing, and you can know how the logic works from the rules file.
* **<font color=#E01E5A>Rules can be loaded from anywhere:</font>** The framework provides local file configuration source and zk configuration source implementation, also provides an extension interface, you can store the rules anywhere.
* **<font color=#E01E5A>Hot Refresh:</font>** Rules change without restarting your application, changing the rules of your application instantly. Refreshing under high concurrency will not cause any misalignment.
* **<font color=#E01E5A>Wide support:</font>** LiteFlow works regardless of whether your project is built on Springboot, Spring or any other java framework.
* **<font color=#E01E5A>JDK Support:</font>** Support from JDK8 to JDK17. No need to worry about the JDK version.
* **<font color=#E01E5A>Scripting language support:</font>** Support for defining scripting language nodes, supporting both QLExpress and Groovy scripts. More scripting languages will be supported in the future.
* **<font color=#E01E5A>Rule nesting support:</font>** You can use simple expressions to accomplish complex logical arrangements with multiple nesting.
* **<font color=#E01E5A>Component Retry Support:</font>** Components can support retries, and each component can be customized with retries configuration and specified exceptions.
* **<font color=#E01E5A>Context isolation mechanism:</font>** Reliable context isolation mechanism, you don't need to worry about data misalignment in the case of high concurrency.
* **<font color=#E01E5A>Declarative Component Support:</font>** You can make any class into a component.
* **<font color=#E01E5A>Detailed step information:</font>** With the step information you can clearly know how the process is executed, how much time each component takes, what exceptions there are.
* **<font color=#E01E5A>Stable and reliable:</font>** Over 2 years of iteration, stable operation on the core systems of major companies.
* **<font color=#E01E5A>Excellent performance:</font>** LiteFlow consumes almost no additional performance, and performance depends on the efficiency of your component execution.
* **<font color=#E01E5A>Simple Monitoring:</font>** LiteFlow has a command line monitor to know the running time ranking of each component.

<br/>

## ✨Latest version

```xml
<dependency>
    <groupId>com.yomahub</groupId>
    <artifactId>liteflow-spring-boot-starter</artifactId>
    <version>2.8.3</version>
</dependency>
```

:::tip Is the new version stable?

Every time we release a version, we add a large number of test cases. Up to now, LiteFlow has more than 880 test cases, covering almost every detail point of existing features.

And we also run a lot of concurrent stress tests, we will carefully submit the code for release only after all the test cases passed.

You don't have to worry about the instability of the new version, we have a good community group. Questions will be answered as soon as possible, and if there are bugs, they will be solved the next day.

So, use it!
:::

<br/>

## 🎉Thanks

LiteFlow won the "OSC Most Popular Chinese Open Source Software of the Year" award in [2021](https://www.oschina.net/project/top_cn_2021).

LiteFlow received the "Gitee Most Valuable Open Source Project" award (GVP) in 2022.

Thanks to OSCHINA and Gitee official platform for recommending and recognizing LiteFlow project.

<br/>

## 🏡Code hosting

<a href='https://gitee.com/dromara/liteFlow' target="_blank">
    <img class="no-zoom" src="https://img.shields.io/badge/Gitee-red?logo=gitee&logoColor=white&style=for-the-badge"/>
</a>

<a href="https://github.com/dromara/liteflow" target="_blank">
    <img class="no-zoom" src="https://img.shields.io/badge/Github-blue?logo=github&logoColor=white&style=for-the-badge"/>
</a>

<br/><br/>

## 🍭Architecture Diagram

<img :src="$withBase('/img/arch.png')" style="zoom: 120%" class="no-zoom">

<br/>

## 🐳Dromara Group Member
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/TLog" target="_blank">
        <img :src="$withBase('/img/dromara/tlog-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/liteFlow" target="_blank">
        <img :src="$withBase('/img/dromara/liteflow-logo.png')" class="no-zoom" style="height:40px;max-width:180px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/hutool" target="_blank">
        <img :src="$withBase('/img/dromara/hutool-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/sa-token" target="_blank">
        <img :src="$withBase('/img/dromara/satoken-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/hmily" target="_blank">
        <img :src="$withBase('/img/dromara/hmily-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/Raincat" target="_blank">
        <img :src="$withBase('/img/dromara/raincat-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/myth" target="_blank">
        <img :src="$withBase('/img/dromara/myth-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/cubic" target="_blank">
        <img :src="$withBase('/img/dromara/cubic-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/forest" target="_blank">
        <img :src="$withBase('/img/dromara/forest-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/Jpom" target="_blank">
        <img :src="$withBase('/img/dromara/jpom-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/sureness" target="_blank">
        <img :src="$withBase('/img/dromara/sureness-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/easy-es" target="_blank">
        <img :src="$withBase('/img/dromara/ee-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/northstar" target="_blank">
        <img :src="$withBase('/img/dromara/northstar-logo.png')" class="no-zoom" style="height:40px;max-width:180px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/hertzbeat" target="_blank">
        <img :src="$withBase('/img/dromara/hertzbeat-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/dynamic-tp" target="_blank">
        <img :src="$withBase('/img/dromara/dynamictp-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/mendmix" target="_blank">
        <img :src="$withBase('/img/dromara/mendmix-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/koalas-rpc" target="_blank">
        <img :src="$withBase('/img/dromara/koalas-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/MaxKey" target="_blank">
        <img :src="$withBase('/img/dromara/maxkey-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/gobrs-async" target="_blank">
        <img :src="$withBase('/img/dromara/gobrsasync-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/fast-request" target="_blank">
        <img :src="$withBase('/img/dromara/fastrequest-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/x-easypdf" target="_blank">
        <img :src="$withBase('/img/dromara/xeasypdf-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/image-combiner" target="_blank">
        <img :src="$withBase('/img/dromara/imagecombiner-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dromara/dante-cloud" target="_blank">
        <img :src="$withBase('/img/dromara/dantecloud-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>

<br/>

## 🧲Link
<span style="width: 150px;flex:1;text-align: left">
    <a href="https://gitee.com" target="_blank">
        <img :src="$withBase('/img/link/gitee-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://www.oschina.net" target="_blank">
        <img :src="$withBase('/img/link/oschina-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="http://www.layui-vue.com/zh-CN/index" target="_blank">
        <img :src="$withBase('/img/link/layui-vue.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="http://www.pearadmin.com/" target="_blank">
        <img :src="$withBase('/img/link/pearAdmin-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>
<span style="width: 150px;text-align: left">
    <a href="https://gitee.com/dotnetchina" target="_blank">
        <img :src="$withBase('/img/link/dotnet-china-logo.png')" class="no-zoom" style="height:40px;max-width:150px;margin: 10px;">
    </a>
</span>

<br/>

<!-- AD -->
<div class="wwads-cn wwads-horizontal page-wwads" data-id="129"></div>
<style>
  .page-wwads{
    width:100%!important;
    min-height: 0;
    margin: 0;
  }
  .page-wwads .wwads-img img{
    width:80px!important;
  }
  .page-wwads .wwads-poweredby{
    width: 40px;
    position: absolute;
    right: 25px;
    bottom: 3px;
  }
  .wwads-content .wwads-text, .page-wwads .wwads-text{
    height: 100%;
    padding-top: 5px;
    display: block;
  }
</style>