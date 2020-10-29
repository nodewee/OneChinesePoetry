# One Chinese Poetry
一首诗词，一个 JSON 文件，一个独立 URL。可直接通过 HTTP 读取单首诗词内容。方便各种终端的调用。

- 诗词来源：[chinese-poetry 项目](https://github.com/chinese-poetry/chinese-poetry)

<details>
  <summary>单首诗词 JSON 文件内容示例</summary>
<pre>
  {
    "title": "登戎州江樓閑望",
    "author": "幸夤遜",
    "period": "宋",
    "type": "诗",
    "paragraphs": [
        "滿目江山四望幽，白雲高卷嶂烟收。",
        "日回禽影穿疏木，風遞猿聲入小樓。",
        "遠岫似屏橫碧落，斷帆如葉截中流。"
    ]
   }
  </pre>
</details>

- 诗词访问路径示例：`https://nodewee.github.io/OneChinesePoetry/data/333/913.json`

- 诗词数量/目录：目录 1～332 各有1000首。目录 333 有 913 首。

- 诗词内容范围：诗（唐、宋）和词



## 应用

- iOS 桌面组件随机展示一条诗词（[Scriptable 脚本](https://nodewee.github.io/OneChinesePoetry/scripts/scriptable_RandomChinesePoetry/latest.js)）



## 授权

[MIT](/LICENSE.txt) LICENSE

