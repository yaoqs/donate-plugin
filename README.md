# donate-plugin

Donate &amp; Reward 大吉大利，今晚吃鸡

<image src="https://yaoqs.github.io/donate-plugin/kw7q5d.jpg" width="200px"/>

## code

在html中插入以下代码，并将js文件引入html的head标签中即可.

当鼠标移动到侧边栏时将弹框出现

```js
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/yaoqs/donate-plugin/zanzhu_yaoqs.min.js"></script>
/*!
* zanzhu_yaoqs JavaScript Library v1.0.0
* http://github.com/yaoqs
*
* Copyright 2021-, yaoqs[LordYao]
* Released under the MIT license
*
* 3rd Party Library:
* 1.jquery
* 2.jquery.qrcode
* or
* 3.d3js
*
* Date: 2021-10-01
*/
<script>
    $(function () {
        new Rewardtip(
            {
                "tiptext": "谢谢支持/Thanks...",
                "tipimg": { img: "/images/ali.gif", width: "50px", height: "50px" },  //可选
                "more": "/Donate",
                "tipshow": "<img src='/images/ali.gif'/>",                     //可选
                "list": [
                    { name: "微信收款码", qrimg: "/images/微信收款码.png" },
                    { name: "微信打赏码", qrimg: "/images/微信打赏码.png" },
                    { name: "支付宝收款码", qrimg: "/images/支付宝收款码.jpg" },
                    { name: "支付宝红包码", qrimg: "/images/支付宝红包码.jpg" }
                ],
                "link": [
                    { name: "paypal", desc: "paypal.me/LordYao", link: "https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=243292490@qq.com&currency_code=USD&amount=1&return=http://yaoqs.github.com/about&item_name=LordYao%27s%20Blog&undefined_quantity=1" }
                ]/*,
                    fn:(function(){
                        return alert("解放思想，发展生产力");
                    })()*/
            });
    })

</script>
```

## demo

- donate_sider
<img src="https://yaoqs.github.io/donate-plugin/donate_sider.png"/>

- donate_large
<img src="https://yaoqs.github.io/donate-plugin/donate_large.png"/>

## project

- [ ] 扩展sider主题、样式
- [ ] 打包封装
- [ ] 使用d3js封装代替jQuery（可选）

## License 许可证 & Copyright

- 版权声明：Copyright © 2019-2024 要庆生. All rights reserved. 未经本人同意请勿转载。经本人同意后转载时请注明出处。
- [![GitHub license](https://badgen.net/github/license/yaoqs/donate-plugin)](https://github.com/yaoqs/donate-plugin/blob/master/LICENSE) [![GitHub license](https://img.shields.io/github/license/yaoqs/donate-plugin.svg)](https://github.com/yaoqs/donate-plugin/blob/master/LICENSE)
知识共享许可协议 版权声明：署名，允许他人基于本文进行创作，且必须基于与原先许可协议相同的许可协议分发本文([Creative Commons](http://creativecommons.org/licenses/by-sa/4.0/ ))
- 业余时间所作，难免有不足及错漏之处，敬请包涵指正，可通过github仓库在线留言或Email <350788415@qq.com>告知；如需补充其他相关专业信息，亦可邮件通知或github仓库在线留言；同时欢迎各位热心人士star、fork或共同参与维护仓库
