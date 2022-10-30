Malody社区是一个开放的谱面分享社区，并欢迎各种风格的谱面。其中，优质的谱面将会被标记为上架`Stable`，并且允许玩家在游玩这些谱面后获得永久成绩。社区也会积极帮助那些有志于提供可上架的谱面的作者。以下为上架规则，所有谱面的上架都必须以满足这些规则为前提。
# 术语
## 一般术语
- **规定（Rules）：**在**任何情况**下都必须遵守，**不允许**违反。
- **准则（Guidelines）：提倡性内容** ，在大部分情况下应遵守。处于**特殊情况**的条件下可以违反。  
***
# 谱面内容规定
## 元数据
*元数据指的是`歌曲名`、`标题原文`、`艺术家`、`艺术家原文`四个字段。*
### 规定
#### 技术性规定
- 同一套谱面集内的所有的必须**保持一致**。    
	- **歌曲名：** 指按照要求罗马音化且标准化后的歌曲名。  
	- **标题原文（原语种标题）：** 字面意思。  
	- **艺术家：** 指按照要求罗马音化且标准化后的艺术家名称。   
	- **艺术家原文（原语种艺术家名称）：** 字面意思。
- **必须参考由官方来源给出的元数据。** 除非由于标准化规则需要，请不要随意修改其内容。若此曲无可用的元数据来源时，可以使用最常见的或者最容易辨识的。
	- 最早收录此曲的媒体载体、官方Database/wiki、艺术家或厂牌的官网、CD Booklet扫图、作者亲自上传至Bandcamp/SoundCloud/YouTube/Bilibili/niconico的内容通常被视为官方元数据来源。  
	- 可信度较高的第三方Database/wiki（vndb、vgmdb、remywiki等）为次要的元数据来源。  
	- 音乐媒体服务商（Spotify、iTunes、Amazon、网易云音乐等）提供的元数据信息优先级最低。
- **音游曲经常会有同一作曲者使用不同名义作曲的情况，此时只能使用作曲家在此曲的元数据上表记的内容，而不是直接使用作曲家最常用的名义。**
- **歌曲的艺术家必须可以追溯到真实存在的人，但由虚拟角色组成的固定名义的团体以及艺术家字段长度过长而导致的缩短情况除外。** 如果作者已不可考，则应使用`Unknown Artist`。歌曲的唯一作者不能设为某个虚拟的角色或软件，除非此为作者的代号。

	- 比如，Vocaloid音源和角色歌的角色不能作为艺术家。

		> 正确示范：`黒うさP feat.初音ミク - 千本桜`、`イリス・フレイア(CV:日高里菜) ＆ 物部深月(CV:沼倉愛美) - Ray of bullet`  
	- 由虚拟角色组成的固定团体的例子：

		> `25時、ナイトコードで。 - 限りなく灰色へ`、`燐舞曲 - prayer[s]`、`μ’s - Snow Halation`、`Walküre - いけないボーダーライン`
- **若元数据字段长度超过了字段最大长度限制`（255 char）`，则必须缩短。** 建议优先保留便于搜索的内容。

#### 标准化规定
- **如果歌曲是由多首歌曲拼接而成，应在标题内将这些歌曲的名称清晰地列出，或使用一个概略性的标题。** 如果分隔列出的曲名标题过长，则必须使用概略性的标题。  
- **如果使用某些符号将标题中的部分词语连接为一组，则不能直接在该组词语内的符号前后添加空格，只能在整个分组前后添加空格。**  
- **歌曲名及标题原文内不应出现指示歌曲长度的内容，除非此曲的短版内含有其完整版不曾出现的元素，或者长版的元数据内含有不仅是标识歌曲是完整版的内容。**
	- 简单来讲，就是`TV size.`、`Extended mix`、`Full ver.`、`Cut version`这一类的字段是不应填写的内容，因为歌曲长度已经可以指明其版本。
	-  短版内含有完整版不曾出现的元素的例子：`Lia - 鳥の詩（short version）`
	- 长版的元数据内含有不仅是标识歌曲是完整版的内容的例子： `かめりあ - Dyscontrolled Galaxy ("Apoptosis" Long ver.)`
- **仅使用Vocaloid音源创作的曲目，且艺术家原文和标题原文均不包含所使用的Vocaloid音源名称时，应在艺术家原文后添加使用的音源名称**，格式为`%Artist% feat.%Vocaloid% - %Title%` [^1]。**使用了多个Vocaloid的情况下，以`&`符号作为分隔，且不用在其前后添加空格。**

	- `feat.`字段前面要用空格，后面不用空格

		> 举一个例子：`hinayukki@仕事してP feat.KAITO&MEIKO - 番凩-2019-`
- **若角色歌的官方元数据源没有给出能够追溯到真实存在的人的艺术家原文，则必须使用`%角色名%(CV: %角色配音演员姓名%)`格式表记。**
- **若歌曲为多人合作，且官方元数据源没有给出固定的艺术家原文表记形式，则必须使用`&`作为分隔，且需要在其前后添加空格**

#### 罗马音化规定

- **若官方元数据源内含有官方罗马音化方案或者英语翻译方案时，应直接使用。不存在的情况下，则必须按照原文顺序逐个罗马音化。**

	- 有时，有一些艺术家名义是罗马音化后的名前姓后的情况。只要该曲目的艺术家标记从来没有使用过姓前名后的本名名义，将其变更为姓前名后的状态就是违反本条规定的。 

		> 官方元数据源给出的罗马音化方案是名前姓后的例子：`光吉猛修（Takenobu Mitsuyoshi）`、`穴山大輔（Daisuke Anayama）`  
		> 作曲从来没有使用过姓前名后的本名名义的例子：`石渡大輔（Daisuke Ishiwatari）`、`藤森崇多（Sota Fujimori）`
- **若要罗马音化外来词，则应使用其原词的罗马音，而不是这个外来词的罗马音。**
- **当曲名或艺术家中使用表意重复的单词（一个是 Unicode字符，另一个是罗马音）时，罗马音化字段应只填写此罗马音，并移除重复字符。**

	> 一个例子：`DJ TOTTO VS 兎々 - 伐折羅-vajra-`→`DJ TOTTO VS TOTTO - Vajra`
- **本文未涉及的语言的罗马音化方案，应咨询对应语言的母语使用者。**
- **特殊的Unicode字符必须标准化成与其最相似的标准等效字符，或者从罗马音字段中删除。**`★ ☆ ⚝ ✪ `等替换为星号`*`。其他特殊字符则视情况沿用、替换或删除。

### 准则

- 中文标题罗马音化时，一般使用汉语拼音方案（但不标记声调）逐字罗马音化，字与字之间添加空格。注意来自港台的歌曲通常使用**繁体字**（除非此曲无论何时都仅使用简体字表记）。
- 日文元数据的罗马音化时，单个单词罗马音化后不应出现长音符号、隔音号。`へ`、`は`、`を`用作助词时，按照其变化后的读音罗马音化。
- 当一首歌曲被另一个艺术家翻唱或改编，且标题原文与原始歌曲不同时，需使用常识来辨认这是艺术家有意为之还是无意犯错。
- 存在多种可用的元数据时，应优先选择容易辨识、方便追溯到原曲或来源的较新元数据。

	> 相对较新的元数据的例子：EZ2DJ内曾收录过一曲*Black Bird*，最开始时其作者名义为*Infinity Poly*，但其系列作后来都直接标明作者为*M2U*了，因此元数据标记为`M2U - Black Bird`才是相对更优的选择。
- 应将单个符号罗马音化，并在它的前后添加空格（英文逗号前侧无需添加空格）。如果是艺术家有意使用特殊字符，并违反了通常的标准化规则，则可忽略此条准则。

	> 一个例子：`DM Ashura - ΔMAX`→`DM Ashura - Delta MAX`
***
## 谱面信息
### Version
#### 规定
- **严禁出现超过字段最大长度限制`（255 char）`的难度名。**
- Key
	- **必须按照** `%轨道数量%K %难度名% Lv.%难度等级%`**的格式填写。**  
- Catch
	- **同一时间有多个note的谱面后必须添加`+`加以区分。**

		> 一个例子：`Rain+`

#### 准则
- 难度名建议使用便于区分难度梯度的预设难度名模板填写。
- Catch
	- 推荐使用 `Cup`-`Salad`-`Platter`-`Rain`-`Overdose`，特殊难度可标记为`Special`。
- Pad
	- 推荐使用 `BASIC`-`ADVANCE`-`EXTREME`。
- Taiko
	- 推荐使用 `Easy`-`Normal`-`Hard`-`Extreme`-`Extra`或 `Kantan`-`Futsuu`-`Muzukashii`-`Oni`-`Ura Oni`。
- Ring
	- 推荐使用 `Beginner`-`Easy`-`Normal`-`Hard`-`Extend`。
- Slide
	- 推荐使用 `Beginner`-`Easy`-`Normal`-`Hard`-`Extend`。
- Live
	- 推荐使用 `Easy`-`Normal`-`Hard`-`Expert`。

### Creator
#### 规定
- **严禁出现超过字段最大长度限制`（255 char）`的Creator字段。**

#### 准则
- 建议填写能够明确表现出所有参与者的内容。

### 预览时间
#### 准则
- 建议设置合理的预览时间点。

### BPM与偏移
#### 规定
- **对于无变速的一般曲目，要求BPM和偏移必须准确无误；对于含有变速的曲目，则必须保证变速精准或变速误差不影响游玩。**

### 杂项
#### 规定
- Key
	- **轨道数量：仅允许轨道数量在[4,9]的闭区间内的Chart上架。**
- Catch
	- **下落速度：下落速度的值应包含在[5,10]的闭区间内。**
***
## 文件
### 所有内容都必须遵守的规定
- **文件名严禁过长，且严禁包含连续的空格 、非Unicode字符以及特殊符号 。**
- **严禁包含严重涉政、攻击性过强、含有任何18禁元素、引人不适或含有NSFW的内容。上传此类内容可能会导致您的账号永久`DIED`。** [^2]
- **对于有文件格式要求的内容，严禁单纯以修改后缀的形式上传至服务器。**

### 音频文件
#### 规定
- **所有音频文件必须为Ogg Vorbis（.ogg）格式。**
- **Rate必须为44100Hz。**
- **Bitrate必须在128-192kbps区间内。**
- **严禁使用由低质量歌曲文件而重编码成的高码率音频。[^3]**
- **Full-Keysounded Chart必须将所有音频文件打包为`data.zip`进行上传。此压缩文件不得包含任何子文件夹或任何与谱面无关的文件。以此方法上传图包的行为将会导致您的账号永久被BAN。**

#### 准则
- 音源应尽可能使用清晰度足够高的版本。一般来讲，OST音源为最优选择，其次是GST/各大音乐流媒体平台的音源，非常不建议使用视频抽取音源。

### 背景图
#### 规定
- **背景图片必须使用JPEG（.jpg）格式。**
- **图片体积必须在2M以内。**

#### 准则
- 背景图尺寸建议至少能大于1024*720，尽量尝试寻找原图，并避免不必要的放大操作。
- 不同的Chart可以使用不同的背景图。

### BGA
#### 规定
- **BGA文件中严禁出现不出场的节点。**
- **上传文件中严禁含有未被BGA引用的文件。**
***
## 网页端信息
### SID & Song Page
*SID即为对应的Song Page的ID。在Malody中，一个Song Page下可以挂载不同Creator的多个谱面，这些谱面具有相同的SID。*

#### 规定
- **采用了具有相同的元数据的歌曲的谱面应置于同一个Song Page下**。因此在上传您的谱面前应检查服务器是否存在该歌曲的Song Page（推荐直接使用该Song Page内已有的音源，而不是自行添加新音源）。请不要重复创建SID。服务器已经存在该歌曲时，可以在上传页面指定上传的SID；不存在时，填写0上传会创建新的Song Page和SID。
- **若音源仅为经过了简单的加速、或添加了某游戏由于游玩方式而添加的效果音，也应上传至同一SID，并且在Chart Page页面注明详情。**

	> 一些例子：SDVX不同难度下的FX音源，或单纯的几倍速音源。

- **必须为Song Page上传拥有足够清晰度的Cover** ，推荐使用大小为400*400的JPEG格式图片。
- **Cover不能与歌曲完全无关。**
- **Cover不允许包含Creator信息，除非您已经获得该曲Artist的授权，或者您是Artist之一。**

#### 准则
- Cover优选此曲独占封面，次选为专辑封面，都不存在时优选与曲目关联度高的内容。
- Tags内可以选择与歌曲相关的内容，以便搜索。

### CID & Chart Page
*CID既是对应的Chart Page的ID，也是谱面本身所对应的ID。填写0上传时会创建新的Chart Page和CID。
任何谱面都属于<font color=#cb665b>`alpha`</font>、<font color=#d5d332>`beta`</font>、<font color=#62b69c>`stable`</font>三种状态之一，但只有拥有`Assistant`及以上权限的用户才能更改谱面状态。*

#### 规定
- **Key模式Chart必须在Tags内勾选对应的轨道数量的Tag。**
- **非Uploader本人创作的谱面上架时，由Publisher将其Transfer至Creator。** 若Creator未拥有Mugzone账号，可挂载于Uploader名下。
- **多人合作谱面上架时，由Publisher将其Transfer至贡献最大的Creator。** 若Creator未拥有Mugzone账号，按照贡献程度依次顺延，均未拥有则挂载于Uploader名下。
***
## 谱面内容
### 规定
- **谱面必须是通过官方Editor制作的，仅使用官方Editor提供的功能。**
- **当一首歌曲下没有对应模式的Stable谱面时，需要有一个低于Lv.10的底难度谱面。** 已有时，你可以增加任意难度谱面，数量不限。
	- Key模式中，不同轨道数的谱面应当做不同的模式对待。
	- 此底难度必须是理论拇指可玩的（但`5K`、`6K`、`7K`、`IIDX SP(8K)` 、`pop'n(9K)`、`Pad`的底难度除外）。
- **必须确保歌曲下至少有一张谱面处于适合一般水平玩家（Lv.10~Lv.20）游玩的难度**。
- **两相邻难度之间的等级差不应大于10。**
- **谱面的可游玩时间必须大于60秒。**
- **谱面必须能在Auto模式下达成Perfect Play，且不应存在理论上不可能手动游玩的内容。**
- **目前Effect只能被用于过于激烈的BPM变速或BPM不稳定的生演奏的缓冲。**
- **特定来源的曲目严禁上架。** 相关内容甚至可能会在不通知谱面作者的情况下被清理。

	> Rayark & lowiro：不允许使用其版权曲。  
	> NeLiME：应作者本人要求，不允许使用其曲。  
	> a_hisa：使用其乐曲需取得本人授权，否则不允许使用。  
	> m108：应作者本人要求，不允许使用其曲。  

### 准则
- 适当地在谱面内玩原谱的梗是可以接受的。**但是过于明显的抄袭会导致您的审核请求被拒，甚至直接被BAN掉账号。**

### 额外内容
- 各个Publisher针对谱面内容可能会有不同的要求。具体情况请联系对应Publisher的审核团队以了解详情。
***
## 审核团队
- Key

	> 🇨🇳 [YuzukiY](http://m.mugzone.net/accounts/user/61119)：`4K`  
	> 🇨🇳 [boomushroom](http://m.mugzone.net/accounts/user/5867)：`4K`  
	> 🇨🇳 [Shioriko_](http://m.mugzone.net/accounts/user/23095)：`4K`  
	> 🇨🇳 [AyaseEli](http://m.mugzone.net/accounts/user/42989)：`4K`  
	> 🇨🇳 [Arkman\_pku](http://m.mugzone.net/accounts/user/124916)：`6K`    
	> 🇨🇳 [Laddie\_Amoyensis](http://m.mugzone.net/accounts/user/14851)：`Thumb Style`  
	> 🇨🇳 [mdr9999](http://m.mugzone.net/accounts/user/138477)：`Dance Cube`  
	> 🇨🇳 [Astesia0](http://m.mugzone.net/accounts/user/759694)：`Dance Cube`  
	> 🇯🇵 [yoshilove](http://m.mugzone.net/accounts/user/429)：`4K`、`5K`、`6K`、`7K`、`IIDX SP(8K)`、`pop'n(9K)`  
	> 🇯🇵 [DPkaiden](http://m.mugzone.net/accounts/user/96060)：`4K`、`5K`、`6K`、`7K`、`IIDX SP(8K)`  
	> 🇯🇵 [tkdkendo](http://m.mugzone.net/accounts/user/149935)：`4K`、`5K`、`6K`、`7K`  
	> 🇯🇵 [Elaina-](http://m.mugzone.net/accounts/user/138265)：`4K`、`5K`、`6K`  

- Catch
	> 🇨🇳 [YakumoChen](http://m.mugzone.net/accounts/user/1004)  
	> 🇯🇵 [tkdkendo](http://m.mugzone.net/accounts/user/149935)（代理中）

- Pad
	> 🇨🇳 [xipigu](http://m.mugzone.net/accounts/user/4168)  

- Taiko
	> 🇨🇳 [xipigu](http://m.mugzone.net/accounts/user/4168)  
	> 🇨🇳 [laosibiniqiang](http://m.mugzone.net/accounts/user/21237)  
	> 🇨🇳 [Amami_A_Myamsar](http://m.mugzone.net/accounts/user/13698)  
	> 🇨🇳 [Zpm](http://m.mugzone.net/accounts/user/49836)  
	> 🇯🇵 [2nurupo_](http://m.mugzone.net/accounts/user/95645)  

- Ring
	> 🇨🇳 [Zero__wind](http://m.mugzone.net/accounts/user/374)  

- Slide
	> 🇨🇳 [xipigu](http://m.mugzone.net/accounts/user/4168)  
	> 🇨🇳 [Laddie\_Amoyensis](http://m.mugzone.net/accounts/user/14851)

- Live
	> 🇨🇳 [Pentlandite](http://m.mugzone.net/accounts/user/72727)  
	> 🇨🇳 [Laddie\_Amoyensis](http://m.mugzone.net/accounts/user/14851)
***
[^1]: 如果你经常使用各种根据文件名自动填写音乐文件metadata的软件的话应该会比较熟悉这种标注形式。假设一首歌曲的*Artist*为*woc2006*，*Title*为*MoemoeGirl*，按照`%Artist% - %Title%`填写的结果就是`woc2006 - MoemoeGirl`。后面的格式例举相同。
[^2]:此类内容的判定标准由`Admin`或`Organizer`决定，切勿碰瓷。
[^3]:这种情况可以使用[**Spek**](http://spek.cc/)对音频文件进行检查。如果中频段内有明显的截止的话，基本可以断定音源质量不合格。
