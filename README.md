
typora-root-url: ".."

## HardCandy-Jekyll

### Now it's more than just a mod!!!


### Preview

[Online preview view demo →](http://jony-blog.github.io/)

![1](./screenshot/1.png)

![2](./screenshot/2.png)

![3](./screenshot/3.png)

To view the display on the mobile phone, scan the QR code browser below to open it.

![4](./screenshot/4.png)



### Theme feature

- Theme-based `jekyll 3.8.1`development
- Responsive layout
- Article tag index
- Article timeline index
- Blogger personal information display
- Support 9 kinds of code highlighting theme colors
- Support `dispus`, `laibili`, `Gitment`three kinds comment system
- Support `Baidu statistic ` , `Google Analytics` two website tracking systems
- Support 13 different social platform icons and link address pointing
- Support article sharing intersections on 11 different platforms
- **Full language Translation in English. including README.md and all code Documentation.**
- **Support sitemap.xml**
- **Support nice preloader (pure css) for better user experience**
- **Support mp3 embedder which can detects URL’s that point to mp3 files and replaces them with a default HTML5 player. And also support Auto-Play, looping**
- **Support Embeded Youtube, Vimeo Videos with Auto-Play, looping feature**
- **Support breadcrumd for cool navigational hierarchy.**
- **Added some Author Schema Data (ld+json) for better seo support.**
- **Support Integrated GUI editor. and CMS-style graphical interface name**



### What new in this Mod (2.2)?
- Improve sitemap.xml format
- font improvment in post content.
- Change 404 Page Now Created by me.
- boosted some vector & ruster file
- Added built in webmaster verifications
- Shifted some external Javascrip in /assets
- Beutify nav bar url. Now URL looks more stylish.
- Prettify parmalink now Web Url looks more fresh and dynamic.
- Aded nice preloader (pure css) for better user experience. Thanks to @akshaycodes
- Added seotag for imroving social media presence and providing more detail about particular entities on the page.
- The mp3 embedder can detects URL’s that point to mp3 files and replaces them with a default HTML5 player. more on Description.
- SEO (Search engine optimization) for increasing the quality and quantity of traffic to your website through organic search engine results.
- Added Breadcrumd for better indicate the current page’s location within a navigational hierarchy that automatically adds separators links.
- Added Author schema markup (ld+json seo_person.html) to helps search engines understand the information on web pages and provide richer search results.

### Previously added in this Mod (2.0)?

- Full language Translation in English. including README.md and all code Documentation.
- Change friendslink to reLink.
- Add a modified Background. you can revert back or change the background. but always use vector image as background for optimal performance.
- Add sitemap.xml support
- change 404 Page (svg taken from [Henry W](https://codepen.io/henrywr/pen/XezdRr)  )
- Future dated posts are not *automatically rendered* FIX !
- add a integrated GUI editor. and CMS-style graphical interface name **Jekyll Admin**. ([Check in bellow in Configuration document](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#Jekyll Admin))
- and many other small modification & bug-fix that i don't remember correctly.



### Upcomming in this Mod!!!

- Adding Optimization Script or plugin (Under Devlopment). which can speedup this blog into a another level.



### start using

#### Online deployment

First, `github`open a repository named on `your-github-username.github.io`. And `clone`your local repository. Then download `HardCandy-Jekyll-Mod`the [source code](https://github.com/JonyBepary/HardCandy-Jekyll-Mod) after the local, will `_config.yml`change the file to your own configuration (discussed next). After all of the files copied to the root directory of your local repository, and then uploaded to their `github`online repository, by domain name you can `https://your-github-username.github.io`access to see their blog pages.

####

#### Local deployment

First installed locally `Jekyll` [please poke](https://www.jekyll.com/docs/quickstart/)

After the installation is complete, use the command `jekyll -v`to view **jekyll version number** , if less than `jekyll 3.x.x`you need to upgrade to `jekyll 3.x.x`.

The source locally, in the terminal run:

```
git clone https://github.com/JonyBepary/HardCandy-Jekyll-Mod.git
```

 go to into the `HardCandy-Jekyll-Mod`root directory, in the terminal run:

```
cd HardCandy-Jekyll-Mod
```

for install required plugin,  in the terminal run:

```
bundle install
```



and finally run  `jekyll server`or `bundle exec jekyll serve`to open Jekyll service. Access through the browser [HTTP: // localhost: 4000](http://localhost:4000/) , you can see the local deployment of `HardCandy-Jekyll`the blog.

> Warning! Points worth noting:
>
> Since this topic is based on the `jekyll 3.8.1`development of version differences jekyll may lead to differences related to the display. Please refer to the official document for details: [news](https://jekyllrb.com/news/)



### Configuration document

- Start
  - [About blog](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#about-blog)
  - [write an essay](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#write-an-essay)
  - [Jekyll-Admin integrated GUI editor. and CMS-style graphical interface](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#jekyll-admin )
  - [Blogger personal information](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#blogger-personal-information)
  - [social media](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#social-media)
  - [Home display information](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#home-display-information)
  - [Navigation Bar](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#navigation-bar)
  - [Pagination](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#pagination)
  - [Code highlighting theme](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#code-highlighting-theme)
  - [Links](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#links)
  - [Footer](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#footer)
- Third party service
  - [Comment system switching](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#comment-system-switching)
  - [Article sharing intersection](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#article-sharing-intersection)
  - [Website traffic tracking configuration](https://github.com/JonyBepary/HardCandy-Jekyll-Mod#website-traffic-tracking-configuration)

> By modifying the `_config.yml` files in general  , you can easily build your own personal blog.
>
> Part of the configuration, the default is already configured, you only need to modify the contents listed below to complete the construction.

#### About blog

```
---
 # Site settings Configuring the site
title : ' your awesome title '
 description : ' your web description '
 keywords : ' your web keywords, another keywords '
 url : ' https://abc.github.io '  # your host
-- -
```

`title` : display content for the title tag of the page

`description` : Introduction to the website

`keywords` : Website Keywords

`url` : Website domain name

####

#### write an essay

Blog by parsing `markdown`to deploy the full text of the page, so users only need to write articles write a markdown, and placed in the site root `_post`folder. The specific markdown syntax searches online for learning, or writes using the markdown editor. Recommend a markdown editor: [typora](https://www.typora.io/) . Support windows, mac OSX, Linux.

About the article YAML header information:

```yaml
layout: post
title:  "post title"
subtitle: 'post subtitle'
date:   2018-05-29 08:44:13
tags: html js css
description: ''
color: 'rgb(154,133,255)'
cover: ''
typora-root-url: ".."
```

About color:

The color here is used for the background color of the top position of the post page. As shown above is shown in FIG `rgb(154,133,255)`color.

For writing color, if the color code `rgb`or `rgba`another or `英文单词`, you can not wrapped in quotes, but if the color code `#123456`this hexadecimal code, then it must be wrapped in quotation marks. Therefore, in use, it is recommended to use quotation marks in order to avoid misuse.

Of course, if you're writing articles, forget the color value is written, then the default theme will be filled in as you `rgb(154,133,255)`color. This is the color shown in the image above. Although it does not affect the display of the page, if you want more colorful page effects, it is recommended to write the color value in each header.

About cover:

Here you need to fill in an image `url`, the `url`value can be an image on the line, or it can be an image in the blog directory. The key is to write correctly. This image is used in the blog list under the home page, as shown below.



![5](/screenshot/5.png)

### Blogger personal information

```
#Author/Blogger
name: 'Jony Bepary'
NickName: 'Jhon :)'
webtitle: 'Code With Jhon'
bio: 'Student, Computer Programmer And a Scented Soul'
about: true
aboutyou: "
          your awesome story <br>
          use br tag for new line <br>
          and &\emsp for Chinese space
          "
portraits: '/assets/madara.png' # your portraits image file path


```

This section displays the About bloggers page, and social media with the following illustration shows.



![6](/screenshot/6.png)

About author:

​ Use true or false to turn the blog info card on or off. The default is true and the best experience is true .

About about:

​ Use true or false to turn blog owners on or off, that is, whether to display information about the aboutyou section. The default is true , this part needs to enter relevant information in aboutyou, support to fill in the html code here.



### Jekyll Admin

A Jekyll plugin that provides users with a traditional CMS-style  graphical interface to author content and administer Jekyll sites.

1. Start Jekyll as you would normally (`jekyll serve`)
2. Navigate to `http://localhost:4000/admin` to access the administrative interface



### social media

```yaml
# Social Network Service
SNS: true
SNS-icon: #['Facebook', 'weibo', 'qq', 'github', 'Dribbble', 'Twitter', 'instagram', 'weixin', 'Codepen']
  mail: 'mailto:yourname@example.com'
  github: 'https://github.com/example'
  Codepen: 'https://codepen.io/example/#'
  Twitter: 'https://twitter.com/@example'
  instagram: 'https://www.instagram.com/example/'
  Facebook: 'https://facebook.com/example'
  Google: 'https://plus.google.com/+example'
  weixin: '' # The address where your WeChat QR code is stored
  qq: '' # The address where your qq QR code is stored or http://wpa.qq.com/msgrd?v=3&uin='你的QQ号'&site=qq&menu=yes
  weibo: ''
  Dribbble: ''
  zhihu: ''
  juejin: ''
  twitch: ''

```

​ ~~A total of 13 kinds of theme configuration of social media icons, as long as the name of the need to open a social account fill your personal home page link, do not need to open it with the head of the line `#`to comment this line. Similarly, if you need to change the arrangement of each icon, you only need to change the order in which each row is arranged.~~

​ In the `SNS`fill `true`or `false`to open or close this part.

2018/09/28 update:

![7](/screenshot/sns-icon.png)

- Update social icons to online addresses for easy management and modification.
- Add Codepen icon
- Modify the original round icon as an irregular icon



####  Home display information

```yaml
---
layout: default
title: your awesome title
page-title: awesome page-title.
home-title: awesome home-title.
description: description
---
```

​ Which is located `index.html`, Modify `title`, `page-title`, `home-title` , `description`for the personal information desired, the default display configuration as FIG.

![7](/screenshot/7.png)



#### Navigation Bar

```yaml
# navigation bar：&emsp;
nav: # best experience six labels and preferably no more than 4 Chinese characters per label
  Home : '/'
  Tags : '/tags.html'
  Timeline: '/timeline.html'
  About: '/about.html'
  reLink: '/reLink.html' # you can use this for share important link. like project, book, article, or other awesome blog. add link in freinds

```

​ They are all enabled by default, of course, if you want to add them yourself, fill in the format below, of course, the page display order is related to the position of each line.



#### Pagination

```yaml
# Pagination
# the number of post you wanna show in a first page
paginate: 4
paginatepath: ['page:num']
```

With your personal hobbies, fill in the number of blogs you need to display at most on the first page of your page.

Local deployment requires the use  `gem install jekyll-paginate` or  `sudo gem install jekyll-paginate` installation of Jekyll's paging plugin.



#### Code highlighting theme

```yaml
#Highlight using rouge
highlighter : rouge
#Highlight theme using pygments theme: autumn\ default\ emacs\ friendly\ manni\ murphy\ pastie\ perldoc\ tango Choose one of your favorite theme names in the single quotes below
pygmentsTheme : ' default '
```

The code highlights the default highlighting engine after jekyll3.0 `rouge`. On the subject, only you need `pygmentsTheme`to fill in the name of the theme can be like after. There are 9 themes to choose from, the theme names are as above.

Code highlighting:

~~~markdown
``` css
*{
 margin:0;
 padding:0;
}
```
~~~

2018/09/28 update：

![7](/screenshot/博客代码高亮例子.png)

The above picture shows the code highlighting test case. Only html is used as a reference example. For other code, refer to the above figure, or switch the test yourself and choose your favorite code highlighting theme.



#### Links

```yaml
# reLinks
friends:
  Jony's blog: 'http://jony-blog.github.io/'
  XSeven's blog: 'http://xseven.me/'
  subeen's blog: 'http://subeen.com/'
  Corey Schafer: 'http://coreyms.com/'
```

Fill in the format, the sorting is related to the sorting in the configuration file.

you can use this for share important link. like project, book, article, or other awesome blog. add link in freinds

####



#### Footer

```yaml
# since
footer:
  since: 2018
```

Used for the footer display time.



#### Comment system switching

```yaml
# For Comments Best experience, Choose between disqus, liveRe and Gitment
# disqus
disqus: true
disqus_url: 'https://username.disqus.com/embed.js' #
# liveRe
livere: false
livere_uid: 'MTAyMC8zNDI2OS8xMDgwNg==' # MTAyMC8zNDI2OS8xMDgwNg==
# Gitment OAuth Application
Gitment: false
Gitment_owner: ''  # github用户名
Gitment_repo: ''  # github博客存放的仓库名
client_id: ''  # 注册 OAuth Application 后获得的 client_id
client_secret: ''  # 注册 OAuth Application 后获得的 client_secret
```

​ According to the application for the third-party comment, the relevant information obtained can be filled in the configuration file.

There are three to choose from comment, use `true`or `false`open or close a commenting system. Can be opened multiple or even fully open. Of course, the best experience, just open one.

The styles of the three reviews are as follows:



dispus：

![8](/screenshot/8.png)

来必力/laibili：

![9](/screenshot/9.png)

Gitment comment：

![10](/screenshot/10.png)



Each of the three comments has its own strengths and weaknesses. For the display style and mainland China network of environmental considerations, the topic turned on by default `来必力`commentary for the best experience. Of course, you need to fill up the relevant `livere_uid`code.



#### Article sharing intersection

```yaml
# Share : weibo, qq, wechat, tencent, douban, qzone, linkedin, diandian, facebook, twitter, google
social-share: true
social-share-items: ['facebook', 'twitter', 'google', 'linkedin',]
```



In order to make the article more convenient to share, the third-party sharing plug-in [Share.js is](http://overtrue.github.io/share.js/) used to support one-click sharing to Facebook, Twitter, Linkedin, Google+,  Weibo, QQ space, QQ friends, WeChat, Tencent Weibo, Douban and a little bit. And other social networking sites.

Simply fill in the relevant name in `social-share-items`the can, the display order from the writing order relevant.



#### Website traffic tracking configuration

```yaml
# Baidu statistics fill in the relevant url code in baidu-url
baidu: false
baidu-url: ''
# Google Analytics Fill in your own tracking ID in Google Analytics in google-ID:''
google: true
google-ID: '<UA-********-**>'
```

In `baidu-url`and `google-ID`the respective fill in the relevant information acquired by registration. Use `true`or `false`open or close them. For the Chinese mainland network environment, Baidu statistics are enabled by default, of course, you can open more.

### License

HardCandy-Jekyll is licensed under  [MIT](https://github.com/JonyBepary/HardCandy-Jekyll-Mod/blob/master/LICENSE) .

### Ask Star for attention

See here, if you like [his](https://github.com/xukimseven/) awsome project with [my](https://github.com/JonyBepary) little effort, welcome to download and use this, please also give a little star ![Stuck_out_tongue_winking_eye](https://assets-cdn.github.com/images/icons/emoji/unicode/1f61c.png) Thank you.
