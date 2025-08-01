# 关于本站

> ⚠️本站由**哔哩哔哩** @乗芷 搭建，采用docsfiy、github。未经允许不可擅自转发！！！
>
> md编辑：Typora
>
> 虽然说这个页面很小，但是是托管在GitHub上面的
>
> ## 个人联系方式

mail：wulitian2@outlook.com、wulitian2@gmail.com、18065180083@163.com

WeChat💬：H-Wu5301(备注来意）     QQ：2158924331(备注来意)     可以找我聊天🥰

QQ🐧群：519183126                        GitHub：wlw333554             项目：czweb

# 应用寻找

watt toolkit：[点我下载(蓝奏云密码：1234)](https://wwn.lanzouy.com/b01v4iz1g)

Typora(破解版)：[点我下载(蓝奏云密码：54dj)](https://wwen.lanzout.com/iM5Zl32bb4jg)

PianoTrans：[点我下载(阿里云盘)](https://www.aliyundrive.com/s/CLnB26tgkqS)

この雪が解けるまで：[点我下载(蓝奏云密码:47ha，不能下载与我无关)](https://wwen.lanzout.com/i7cIf32bndud)

龍舌蘭体验版：[点我下载(蓝奏云网盘密码：28dk,不能下载与我无关)](https://wwen.lanzout.com/b00hr1hzba)

Goddess体验版：[点我下载(蓝奏云密码:8mq2，不能下载与我无关)](https://wwen.lanzout.com/i7Ubw32boaja)

## Typora破解教程

1.在官网下载最新版Typora：[官网](https://typoraio.cn/)

2.点击开始15天试用，然后关闭

3.找到Typora安装目录，打开Typora\resources\window.html文件 在< head > 标签后加上以下代码：

<style>
         /* 选择 body 下一级的所有具有 role="button" 的 div，但排除那些在 content 内部的 div[role="button"] */
         /* body > div[role="button"]:not(content div[role="button"]) 存在冗余 */
         /* body > div[role="button"] 已经限定了选择 body 的直接子元素 div，并且这些 div 具有 role="button" 属性。 */
         /* :not(content div[role="button"]) 试图排除某些元素，但由于 content div[role="button"] 不是 body 的直接子元素，这部分实际上没有效果。 */
         body>div[role="button"] {
             visibility: hidden;
         }
 </style>
4.打开Typora\resources\page-dist\static\js\Licenselndex.****.****.chunk.js文件，进入后用ctrl+f 查找：`e.hasActivated="true"==e.hasActivated,`，将其改为：`e.hasActivated="true",`

5.找到Typora\resources\page-dist\static\js\0.99879679.chunk.js文件(未测)
在第二行添加如下代码：

`// 创建一个新的 div 元素`
`var div = document.createElement('div');`

`// 给 div 添加一个唯一的 ID`
`div.id = 'myOverlay';`

`// 设置 div 的样式`
`div.style.position = 'fixed';`
`div.style.top = '0';`
`div.style.left = '0';`
`div.style.width = '100vw'; // 使用 100% 宽度`
`div.style.height = '100vh'; // 使用 100% 高度`
`div.style.backgroundColor = 'rgb(54,59,64)'; // Night主题背景色`
`div.style.zIndex = '9999'; // 确保 div 在最上层`

`// 将 div 添加到 body 中`
`document.body.appendChild(div);`

`//window.resizeTo(1, 1); // 将窗口缩小大小，可要，也可以不要`

`// 设置定时器，在 360 毫秒后删除 div ，并关闭页面`
`setTimeout(function () {`
    `var overlay = document.getElementById('myOverlay');`
    `if (overlay) {`
        `overlay.remove(); // 删除 div`
    `}`

    // 点击关闭按钮，关闭页面
    //document.querySelector('.text-btn').click(); //未激活关闭按钮
    document.querySelector('.default-btn.secondary-btn').click(); //激活后关闭按钮

`}, 360); // 360 毫秒后关闭弹窗`

6.没了

# 音乐杂项

## 音频转MIDI

### 方法①：使用PianoTrans（还原度高）

1.打开PianoTrans，打不开就去目录开或者以管理员身份运行(我的win11就这样😡)

然后他会自动跳出来一个框，如果没有就点击 Add files to queue ,之后选择音频文件，耐心等待完成

**tips**:生成的mid文件存放在原始的音频文件目录😅

### 方法②：使用网页在线生成

#### 网页Ⅰ：[Basic Pitch: An open source MIDI converter from Spotify - Demo](https://basicpitch.spotify.com/)

Tips：这个比较适合乐器很多的

#### 网页Ⅱ：[将MP3转换成MIDI-音频转换器](https://audio-convert.com/cn/mp3-converter/mp3-to-midi)

Tips：这个会把任何细节还原，没事建议别用

#### 网页Ⅲ：[音频转MIDI-在线AI扒谱工具](https://qr9.net/audio-to-midi)

Tips：这个会把钢琴细节更还原一些

### 总结

建议用PianoTrans或者网页Ⅲ，亲测好用

# CONSIDER老师调查进展

## CONSIDER老师个人简介

名字：坂木カエ

网名：CONSIDER、Kae、坂木カエ

生日：1981.11.15

擅长：音乐

地区：日本

活跃：2003——2011

## CONSIDER目前已知网站

X：https://x.com/lidyriders

以前的音乐网站(已失效)：http://torio.mydns.jp/consider/

个人日记(未失效、已停更)：https://bluesdelusion.jugem.jp/

个人网站(已失效)：http://torio.tk.to/consider

## CONSIDER曲目出现的游戏

①直到这场雪融化为止（中文翻译）：https://bgm.tv/subject/373419

出现曲目：natume.mid、amane.mid、urou.mid

②Lethe（作者网站可下载）：https://bgm.tv/subject/219224

以上为同人作者yuniu:http://yuniu.web.fc2.com，网站可访问

③龍舌蘭

④Goddess

## CONSIDER已寻回曲目

目前已经寻回的有其第三张CD：GENESIS，consider个人网站(http://torio.tk.to/consider

)上的59首mid文件，1首mp3文件。声优剧2个，其中一个文件无法下载完整，停留在了18分。web小说音频文件4首，以及12首音乐文件：urou.mid、natume.mid、hikaruyoru.mid、seisyun.mid、natume2.mid、amane.mid、詩砂.mp3、戦笛-センテキ-.mp3、RasenGenso_st_style_rmx.mp3、ao.mid、rasengenso.rm、overflow.rm。据不完全统计，我们已经找回100多首曲目。

 

(截至2025/7/16 15:15) [我好像遗漏了2首曲子...只有57首mid]

| 来源：http://torio.tk.to/consider [57首mid文件，1首mp3文件] |                      |                |
| ----------------------------------------------------------- | -------------------- | -------------- |
| 子目录：mmain.html                                          |                      |                |
| 文件原名                                                    | 曲名                 | 位置/状态/备注 |
| houka.mid                                                   | 捧歌（ホウカ）       | 寻回           |
| tyouka.mid                                                  | 弔華（チョウカ）     | 寻回           |
| sirasa.mid                                                  | 白朝（シラサ）       | 寻回           |
| seosi.mid                                                   | 背押（セオシ）       | 寻回           |
| jazz-1.mid                                                  | 楽時（ラクジ）       | 寻回           |
| pk.mid                                                      | 伽世（トギヨ）       | 寻回           |
| koe.mid                                                     | 孤重（コエ）         | 寻回           |
| urou.mid                                                    | 羽蝋（ウロウ）       | 寻回           |
| kenbu.mid                                                   | 剣舞（ケンブ）       | 寻回           |
| aibu.mid                                                    | 逢無（アイブ）       | 寻回           |
| ousou.mid                                                   | 王葬（オウソウ）     | 寻回           |
| shimaizaki.mid                                              | 終咲（シマイザキ）   | 寻回           |
| katou.mid                                                   | 化踊（カトウ）       | 寻回           |
| yojima.mid                                                  | 世終（ヨジマ）       | 寻回           |
| hikaruyoru.mid                                              | 光夜（ヒカルヨル）   | 寻回           |
| seisyun.mid                                                 | 星瞬（セイシュン）   | 寻回           |
| megurimeguru.mid                                            | 巡々（メグリメグル） | 寻回           |
| koutei.mid                                                  | 皇/帝（コウテイ）    | 寻回           |
|                                                             |                      | ピアノ（18曲） |

 

| 子目录：omain.html |                      |                    |
| ------------------ | -------------------- | ------------------ |
| 文件原名           | 曲名                 | 位置/状态/备注     |
| org-kazami.mid     | 風深（カザミ）       | 寻回               |
| org-yuuyami.mid    | 夕闇（ユヤミ）       | 寻回               |
| org-zanka.mid      | 残夏（ザンカ）       | 寻回               |
| yukiokuri.mid      | 雪贈（ユキオクリ）   | 寻回               |
| hisan.mid          | 悲散（ヒサン）       | 寻回               |
| hanairo.mid        | 花色（ハナイロ）     | 寻回               |
| org-mayoi.mid      | 迷足（マヨイアシ）   | 寻回               |
| seisei.mid         | 星声（セイセイ）     | 寻回               |
| chg.mid            | 雨願（アメノネガイ） | 寻回               |
| yoka.mid           | 夜夏（ヨカ）         | 寻回               |
| sirata.mid         | 白綿（シラタ）       | 寻回               |
|                    |                      | オルゴール（11曲） |

 

| 子目录：amain.html |                      |                                                              |
| ------------------ | -------------------- | ------------------------------------------------------------ |
| 文件原名           | 曲名                 | 位置/状态/备注                                               |
| sizuna.mid詩砂.mp3 | 詩砂（シズナ）       | 寻回mid在audiolead寻回 mp3 (Lukewarm专辑) 第２２話　フィヨルド・もう… ＢＧＭ【詩砂】：ｂｙCONSIDER様[http://pieceofeternal.web.infoseek.co.jp/novel.htm](https://web.archive.org/web/20050913054845fw_/http://pieceofeternal.web.infoseek.co.jp/novel.htm) |
| zanka.mid          | 残夏（ザンカ）       | 寻回                                                         |
| komai.mid          | 古舞（コマイ）       | -目前遗失-                                                   |
| mayoiasi.mid       | 迷足（マヨイアシ）   | 寻回                                                         |
| kk.mid             | 花宴（ハナウタゲ）   | 寻回                                                         |
| amabi.mid          | 雨火（アマビ）       | -目前遗失-                                                   |
| sakadoki.mid       | 酒時（サカドキ）     | 寻回                                                         |
| odore.mid          | 踊々（オドレオドレ） | -目前遗失-                                                   |
| kanohikari.mid     | 彼光（カノヒカリ）   | 寻回                                                         |
| nagiuta.mid        | 凪唄（ナギウタ）     | 寻回                                                         |
| katariboshi.mid    | 語星（カタリボシ）   | 寻回                                                         |
| sekai.mid          | 世界（セカイ）       | -目前遗失-                                                   |
| enbu.mid           | 円舞（エンブ）       | -目前遗失-首次出现于2007 5 28快照                            |
|                    |                      | 楽曲（原13曲 寻回8曲）                                       |

 

| 子目录：gmain.html |                    |                  |
| ------------------ | ------------------ | ---------------- |
| 文件原名           | 曲名               | 位置/状态/备注   |
| hukamori.mid       | 深森（フカモリ）   | 寻回             |
| mori.mid           | 蒼森（アヲモリ）   | 寻回             |
| hyoudou.mid        | 氷洞（ヒョウドウ） | 寻回             |
| kooku.mid          | 古憶（コオク）     | 寻回             |
| kozoku.mid         | 小族（コゾク）     | 寻回             |
| beturi.mid         | 別離（ベツリ）     | 寻回             |
| jyouka.mid         | 城下（ジョウカ）   | 寻回             |
| enpou.mid          | 遠方（エンポウ）   | 寻回             |
| hurudami.mid       | 古民（フルダミ）   | 寻回             |
| kokuu.mid          | 黒空（コクウ）     | 寻回             |
|                    |                    | ゲーム風（10曲） |

 

| 子目录：umain.html         |                               |                   |
| -------------------------- | ----------------------------- | ----------------- |
| 文件原名                   | 曲名                          | 位置/状态/备注    |
| kessin.mp3                 | 欠心（ケッシン）              | -目前遗失-        |
| donshi.mp3                 | 鈍思（ドンシ）                | -目前遗失-        |
| jyakurenp.mp3jyakuren1.mp3 | 若恋（ジャクレン）ﾋﾟｱﾉ + 原曲 | -目前遗失-        |
| kazemati.mp3               | 風待（カゼマチ）              | -目前遗失-        |
| mienai.mp3                 | 無視（ミエナイ）              | -目前遗失-        |
| shirayuki.mp3              | 白雪（シラユキ）              | -目前遗失-        |
| syoudou.mp3                | 衝動（ショウドウ）            | -目前遗失-        |
|                            |                               | 歌っぽい（原6曲） |

 

| 子目录：hmain.html |                                                        |                      |
| ------------------ | ------------------------------------------------------ | -------------------- |
| 文件原名           | 曲名                                                   | 位置/状态/备注       |
| os.mid             | お正月(詩：東くめ 曲：瀧廉太郎)                        | 二创？故无DL         |
| BIRTH.mid          | ハッピーバースデー(詩：不明 曲：Mildred J. Hill)       | 二创？故无DL         |
| mafia.mid          | チャップスティック(採譜：ヒルスター)                   | 二创？故无DL         |
| jtv.mid            | ジュ・トゥ・ブ(エリック・サティ)                       | 二创？故无DL         |
| bigbridge.mid      | ビックブリッジの死闘(植松信夫FF5より)                  | 二创？故无DL         |
| NARUTO.mid         | 名不明(アニメナルトのBGMより)                          | 二创？故无DL         |
| kagome.mid         | カノン(パッハルベル)                                   | 二创？故无DL         |
| hanran.mid         | 反乱軍のテーマ(植松信夫FF2より)                        | 二创？故无DL         |
| hp.mid             | ゲッチュウ！らぶらぶぅ？！(ふたりはプリキュアより一部) | 二创？故无DL         |
| ac.mid             | 人々の誕生(古代祐三アクトレイザーより)                 | 二创？故无DL         |
| myst.mid           | 母なる神の爾座(森 彰彦ミスティックアークより)          | 二创？故无DL         |
| zebius.mid         | superxebiusメインテーマ(細野晴臣superxebiusより)       | 二创？故无DL         |
|                    |                                                        | 著作権云々（原12曲） |

 

| 子目录：kmain.html |                            |                                                              |
| ------------------ | -------------------------- | ------------------------------------------------------------ |
| 文件原名           | 曲名                       | 位置/状态/备注                                               |
| tukiuta.mp3        | 『月詩』（ツキウタ）       | -目前遗失-月の詩[月の詩](https://web.archive.org/web/20070521071523/http://moonsong.pinoko.jp/)(swf) |
| roman.mp3          | 『浪漫』（ロマン）         | 寻回RF kimi**                                                |
| BR1.mp3            | 『暗闇に黒い薔薇』kurobara | -目前遗失-                                                   |
| m.mp3              | 『違面』（イヅラ）         | -目前遗失-                                                   |
| HB.mid             | 『君街』（キミガマチ）     | -目前遗失-                                                   |
| omettosan.mp3      | 『祝福』                   | 寻回[http://torio.tk.to:80/consider/kmain.html](https://web.archive.org/web/20070420223355/http://torio.tk.to:80/consider/kmain.html)（"もちろん間違っても持ち出し禁止です。"）(此站本人寻回) |
| kurobara2.mp3      | 『仮想』（カソウ）         | -目前遗失-                                                   |
| -                  | 無題 OP + ED               | -目前遗失-                                                   |
| dd.mp3             | 『影王』（カゴウ）         | -目前遗失-                                                   |
|                    |                            | 自主企画（原10曲 寻回2曲）                                   |

 

| 子目录：bmain.html |                  | ”这是我曾参与过的一些企划， 虽然遗憾地被迫中止，或失去了联系， 但这些企划的歌曲实在太可惜了，不应该就此埋没， 所以我决定上传它们—— 这是一个出于这种想法的个人满足页面。“ 原文：“ここは私が参加させていただいた企画で 惜しくも打ち切りになってしまったり連絡が途絶えてしまった そんな企画たちの曲を埋めるのももったいないから上げておこう というそういった趣旨の自己満ページです。”https://web.archive.org/web/20070528035456/http://torio.tk.to:80/consider/bmain.html |
| ------------------ | ---------------- | ------------------------------------------------------------ |
| 文件原名           | 曲名             | 位置/状态/备注                                               |
| edfull.mp3         | Seraphinaite     | -目前遗失-                                                   |
| sop.mp3            | Seraphinaite(OP) | -目前遗失-                                                   |
| mos1.mp3           | 無題             | -目前遗失-                                                   |
|                    |                  | お墓（原3曲）                                                |

 

| 子目录：nmain.html |                 |                     |
| ------------------ | --------------- | ------------------- |
| 文件原名           | 曲名            | 位置/状态/备注      |
| 01.mid             | 始朝 -シサ-     | 寻回                |
| 02.mid             | 謀室 -ボウシツ- | 寻回                |
| 03.mid             | 市場 -イチバ-   | 寻回                |
| 04.mid             | 王家 -オウケ-   | 寻回                |
| 05.mid             | 不安 -フアン-   | 寻回                |
|                    | ...             |                     |
| 07.mid             | 陥落 -カンラク- | 寻回                |
| 08.mid             | 失意 -モヌケ-   | 寻回                |
| 09.mid             | 忌禁 -イミギ-   | 寻回                |
| 10.mid             | 古塔 -コトウ-   | 寻回                |
| 11.mid             | 契約 -ケイヤク- | 寻回                |
|                    | ...             |                     |
|                    |                 | （原？曲 寻回10曲） |

| 来源：http://torio.tk.to:500500/ [1首mid文件，1首mp3文件] |                    |                   |
| --------------------------------------------------------- | ------------------ | ----------------- |
| 子目录：kimi.html                                         |                    |                   |
| 文件原名                                                  | 曲名               | 位置/状态/备注    |
| roman.mp3                                                 | 『浪漫』（ロマン） | 「君ガ時」web小说 |
|                                                           |                    |                   |
| 子目录：/RF                                               |                    |                   |
| 文件原名                                                  | 曲名               | 位置/状态/备注    |
| hanairo.mid                                               |                    |                   |

 

| 来源：http://moonsong.pinoko.jp/ |                      |                                                           |
| -------------------------------- | -------------------- | --------------------------------------------------------- |
| 子目录：-                        |                      |                                                           |
| 文件原名                         | 曲名                 | 位置/状态/备注                                            |
| akizuki.swf                      | BGM「輝月」Terutsuki | 「月の詩」提供：くまっぷねっと様(BGM「輝月」:CONSIDER様） |

| 来源：http://www.alice-ridder.com                            |                                           |                                                              |
| ------------------------------------------------------------ | ----------------------------------------- | ------------------------------------------------------------ |
| 子目录：/download & /product/RasenGenso/ & /product/at_night_side |                                           |                                                              |
| 文件原名                                                     | 曲名                                      | 位置/状态/备注                                               |
| rasengenso.rm                                                | 「 螺旋幻想 」Title Song                  | 寻回                                                         |
| rasengenso st beat web edit.rm                               | 「 螺旋幻想 st style rmx 」 .c/w Song     | 寻回                                                         |
| RasenGenso_st_style_rmx.mp3                                  | 主題歌アレンジ版「螺旋幻想 st style rmx」 | 寻回                                                         |
| ボイスドラマ - 螺旋幻想.wma                                  | ドラマ本編                                | 声优剧 (仅留下6,488 KB 00:00~18:05)(此站本人寻回，从未下载完成的zip里面提取) |
| overflow.rm                                                  | 「 OVER FLOW 」                           | 寻回                                                         |
| overflow_piano.rm                                            | 「 OVER FLOW - Piano arrangement 」       | 寻回                                                         |
| at the night side.wma                                        | -                                         | 仅BGM(此站本人寻回)                                          |

 

| 来源：http://kuronowish.com |      |                |
| --------------------------- | ---- | -------------- |
| 子目录：/~erueruerumo       |      |                |
| 文件原名                    | 曲名 | 位置/状态/备注 |
| erumode-sum.mp3             |      | 试听版         |

 

| 来源：http://www.audioleaf.com                 |                 |                |
| ---------------------------------------------- | --------------- | -------------- |
| 子目录：/consider                              |                 |                |
| 文件原名                                       | 曲名            | 位置/状态/备注 |
| CONSIDER - インディーズ試聴サイトAudioleaf.mp3 | 戦笛 -センテキ- | 寻回           |
| CONSIDER - インディーズ試聴サイトAudioleaf.mp3 | 詩砂            | 寻回           |

 

| 来源：◆Goddessゲーム◆～秘められた真実～试玩版 (g1Geam.xpk) |      |                |
| ---------------------------------------------------------- | ---- | -------------- |
| 子目录：-                                                  |      |                |
| 文件原名                                                   | 曲名 | 位置/状态/备注 |
| o-1.mid                                                    |      | 寻回           |
| o-2.mid                                                    |      | 寻回           |
| o-3.mid                                                    |      | 寻回           |
| o-4.mid                                                    |      | 寻回           |
| o-5.mid                                                    |      | 寻回           |
| o-6.mid                                                    |      | 寻回           |
| o-7.mid                                                    |      | 寻回           |
| o-8.mid                                                    |      | 寻回           |
| o-9.mid                                                    |      | 寻回           |

| 来源：GENESIS / CONSIDER CD |                   |                |
| --------------------------- | ----------------- | -------------- |
| 子目录：-                   |                   |                |
| 文件原名                    | 曲名              | 位置/状态/备注 |
|                             | 起源 -origin-     |                |
|                             | 海母 -カイボ-     |                |
|                             | 地父 -チフ-       |                |
|                             | 生者 -セイジャ-   |                |
|                             | 失楽 -エデン-     |                |
|                             | 双児 -ソウジ-     |                |
|                             | 方舟 -ハコブネ-   |                |
|                             | 一葉 -イチヨウ-   |                |
|                             | 大成 -タイセイ-   |                |
|                             | 畏怖 -イフ-       |                |
|                             | 夢現 -ユメウツツ- |                |
|                             | 心退 -シンタイ-   |                |
|                             | 天戦 -アマイクサ- |                |
|                             | 静地 -セイチ-     |                |
|                             | 創世 -genesis-    |                |
|                             | -Repert-          |                |

待续...

