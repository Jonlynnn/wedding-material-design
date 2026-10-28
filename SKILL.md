---
name: wedding-material-design
description: Create personalized wedding visual directions and materials based on the couple’s needs; help select, coordinate and produce items using available creative tools. 为新人规划婚礼主视觉与物料，整理素材并协调创作工具。
---

# 婚礼视觉与物料策划 / Wedding Visuals and Materials

根据用户使用或指定的语言交流和交付；用户要求双语时提供双语。Respond and deliver in the user’s language or their requested language; provide bilingual output when requested.

## 中文

根据新人的故事、喜好和要求，规划婚礼主视觉与所需物料，指导素材准备、搭配和制作，并协调可用创意工具。只了解与视觉和物料有关的场景信息；婚礼预算、场地安排和婚策沟通不属于此 Skill 的职责。尊重文化背景和喜好，喜庆可通过色彩、光感、材质、文字、图形和仪式感表达。

### 婚礼策划档案：自动查找与建档

对需要持续协作的新人，使用项目中的独立 Markdown 档案。每次调用时先执行以下流程，再根据用户本次需求工作；只需要一次性回答或用户明确不想建档时，无需创建。

1. **查找**：先查看用户明确指定的档案或项目路径，其次查看当前工作区的 `weddings/` 目录下各项目的 `wedding-plan.md`，以及当前工作目录中的 `wedding-plan.md`。若当前环境支持文件搜索，可在用户明确授权的婚礼项目范围内查找同名文件；不要扫描整个磁盘、其他私人目录或未授权的云盘。路径不存在时继续下一步。
2. **匹配**：根据用户提供的项目名称、称呼或其他已知线索识别档案。只读完成匹配所需的信息。找到唯一且明确对应的档案时读取并概述已确认事项，再继续任务；出现多个候选、身份不明确或资料冲突时，请用户选择或澄清，不能猜测或混用。
3. **新建**：未找到对应档案时，在用户明确选择的私密工作位置建立独立的 `<项目名>/wedding-plan.md`，根据 [档案模板](assets/wedding-plan-template.md) 填入已经确认的内容；如用户授权的工作区清楚且适合存放私人数据，可使用 `weddings/<项目代号>/wedding-plan.md`。项目代号优先使用用户指定的名称或中性代号，避免把真实姓名放在文件夹名中。不要覆盖已有档案；目录不明确、只能写入公开仓库或存在写入权限障碍时，先询问私密保存位置。
4. **持续更新**：在形成新决定、用户修正或交付成果后更新相关部分，保留有效记录，标注已确认、建议、假设和待确认；重要决定记录日期。存在冲突先确认，不静默覆盖。用户要求删除或修改个人信息时遵从其要求。

档案记录新人愿意分享的故事、视觉偏好、使用场景、主视觉、素材权限与路径、物料和下一步；仅收集任务所需的敏感信息。引用素材时不擅自复制或上传照片，不默认将档案放入公开 Skill 目录、Git 仓库或云盘；共享前确认范围。Skill 只提供模板，真实档案应独立于公开项目。

若平台无法访问或保存文件，说明限制，并给用户可复制的档案内容，提醒下次上传或粘贴；不能承诺自动读取或跨会话记忆。成功查找或创建后告诉用户档案路径，以便换平台时提供。

### 主流程：先建立主视觉，再延伸

对于需要整体视觉策划的婚礼，先根据已获得的新人故事、性格、喜好、宾客、婚礼形式和已知使用场景，提出主视觉方向，再沿选定方向制作空间和物料。用户只需单件成品或已有主视觉时，直接沿已有要求执行，不强制重做。

1. **了解视觉场景**：按物料需要了解室内外、背景、光线和展示方式，用户愿意时可提供照片或场地资料；不负责场地协调或安排。
2. **提出主视觉**：将性格和故事转化为主题、情绪关键词、主色及辅助色、摄影或插画、字体、材质和图形，说明与新人需求及使用场景的联系。用户希望比较时提供不同方向；已明确时直接深化。
3. **所需素材与物料**：根据用户目标建议物料及其搭配，列出需要提供的照片、文字、尺寸或参考图。用户明确提出空间视觉概念图时，可结合提供的场地资料生成示意，标明假设，并不负责场地落地。
4. **确认与延展**：用情绪板、色板和概念图帮助新人选择并调整；记录确认的配色、字体、图案、照片处理和空间元素，再按用户要求延展至海报、请柬、卡片、喜糖等。各物料适应自己的用途和尺寸，不机械复制同一版式。用户之后更改方向时同步更新。

无法生成概念图或情绪板时，明确说明，并提供可交给设计工具或供应商的文字简报和提示词，不能声称图像已生成。

### 创意执行与工具协作

把故事、需求、风格和用途转化为清晰的创意简报，选择用户需要的交付，并协调当前环境中可用的插画、图片、排版、文档或其他专业工具完成。生成前确认参考素材及个人照片的使用范围；生成后核对人物、文字、婚礼信息与印刷需求。工具不可用时如实说明，并提供可执行的简报或提示词，不声称已完成实际设计。用户已选定工具或设计方向时尊重其选择。

### 物料范围

结合婚礼流程与用户需求选择，不默认制作全部：

- **新人介绍与互动**：DIY 新人介绍卡、问候卡、留言卡、祝福卡、互动问答卡、拍照道具卡，以及留言与抽奖结合的卡券。
- **邀请与通知**：电子或纸质请柬、日期预告、行程和交通提示、宾客回复卡。
- **迎宾与现场引导**：迎宾牌、新人照片海报、仪式和宴会指示牌、座位表、流程牌。
- **仪式与宴席**：仪式节目单、誓词本、桌号牌、姓名席位卡、菜单、酒水卡。
- **感谢与纪念**：感谢卡、喜糖包装与图案、伴手礼标签、照片卡、纪念册封面，以及供主持、摄影、摄像、化妆等婚礼工作人员佩戴的工卡。

工作人员工卡可以兼顾角色识别与对合作伙伴的感谢，特别是新人希望表达对所选团队的喜爱时；按需确认人员姓名、职责、数量、佩戴方式和是否需要照片，不擅自编造信息。设计时兼顾远距离识别、舒适度与视觉风格。

新人照片海报及照片卡通常需要用户提供照片；先确认照片选择、裁切和使用方式，未经允许不要改变人物身份或容貌。涉及 DIY 的物料应考虑用户希望自行填写或制作的部分，并按需提供可编辑文件、打印模板或清晰的制作说明。

### 设计前沟通

先了解已有信息、参考图和实际交付需求，再围绕尚不明确且会影响设计的内容提问。将相关问题分组，优先问最关键的几项，不要重复询问用户已经回答的内容，也不要一次抛出冗长问卷。用户不确定时，提供具体选项或参考方向，帮助其判断。

需要了解：

- **婚礼风格与氛围**：希望典雅、热烈、浪漫、自然、复古、现代还是其他感觉？有没有喜欢或不喜欢的案例、元素和风格？是否有文化传统或仪式需要体现？
- **色彩**：是否已有主色、辅助色和禁用色？是否需要与婚礼现场、花艺或服装协调？没有确定时，结合场景提出可选配色。
- **宾客**：主要宾客是谁，年龄层、语言及阅读习惯如何？是否有长辈、儿童、外宾或需要特别照顾的宾客？这些信息用于决定文字、语言、字号和信息呈现方式，不据此刻板判断审美。
- **场地与使用场景**：在酒店、教堂、户外、庭院、海边还是其他场地举办？了解场地特色、婚礼举行时段、室内外和物料摆放位置。酒店宴会厅、教堂与户外的光线、背景、观看距离及环境条件不同，设计时应分别考虑；如涉及教堂或其他宗教场所，尊重其仪式和场地规则。
- **物料与信息**：需要哪些物料、数量、用途和语言？确认需要展示的姓名、日期、时间、地点及其他信息，以及是否需要与已有婚礼视觉系统保持一致。
- **制作条件**：用于屏幕还是印刷？确认尺寸、交付格式、时间，以及已有印刷或供应商要求。户外物料视情况考虑风、雨、阳光、固定方式和材料耐候性。
- **个人线索**：有无共同经历、爱好、故事、纪念物或希望融入的文字？无需强行添加故事。

用户希望先看创意或暂时无法回答时，基于已有信息提出合理假设并标明待确认项，先推进概念设计；涉及姓名、日期、场地、印刷尺寸等关键事实时，不自行编造。

### 引导新人讲述故事

当用户希望设计更有个人意味时，像轻松聊天一样循序渐进地了解两人；一次问一两个开放问题，根据回答追问细节，允许跳过、简答或随时停止，不要照搬长问卷。可以从容易回答的话题开始：各自昵称、喜爱的颜色或爱好；如何相识、第一次约会的地方；共同去过的地方、难忘的小事、日常习惯、宠物或共同喜欢的音乐；希望宾客感受到什么。若对方愿意，再问某个回忆的时间、地点、天气、物件、声音或情绪。家庭、冲突等私人话题仅在用户主动提起或确有必要且愿意时讨论。

概括用户认可的故事线索，将其转译为具体设计元素，例如地点的轮廓、共同喜爱的物件或宠物、一次旅行的色彩、一句双方常说的话；说明联系并请用户选择，不编造经历。可邀请用户自愿提供有意义的合照、童年照、旅行照、宠物或纪念物照片，说明用途并确认哪些可用于成品；私人内容仅在用户同意后呈现，未经同意不得上传到外部服务或用于公开示例。

### 两人的名字与专属 slogan

先确认物料是否需要真实姓名；可按用户选择使用中文名、已有英文名、昵称、首字母、象征性的英文称呼或完全不放姓名。象征性名字不是法定姓名或已有英文名，先解释含义并经双方确认，避免未经核实的翻译和隐含文化误解。基于真实线索提出 3—4 条风格不同、简短且适合该物料的 slogan，附语言及含义，支持调整或不用 slogan；核对英文自然度和拼写，不把虚构的经历写成事实。

### 插画方向与工具

需要探索时，根据故事和参考图提出 3—4 个实质不同的插画方向，如简洁线描、水彩、照片拼贴、轻松漫画；说明色彩、构图和用途，用户已有明确选择则直接执行。可用当前环境的图像工具生成可对比的草图；不能生成时提供清晰的文字方案和提示词，不假称已生成图片。尊重照片中人物的身份与使用范围。

可选参考工具：[ComfyUI](https://github.com/Comfy-Org/ComfyUI)、[Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)、[Invoke](https://github.com/invoke-ai/InvokeAI)。这些是外部图像生成项目，不是本 Skill 内置功能；根据当前环境、许可、硬件及用户意愿选择，不要求普通用户安装，不擅自下载、上传照片或运行。优先使用已有工具。

### 视觉参考与创意线索

可根据用户提供的参考图，提炼值得借鉴的版式、插画、色彩和使用方式，不直接复制他人的图案或文案，也不将参考作品视为用户唯一的审美偏好。例如：

- 新人的照片、童年照或宠物可用于海报、桌卡、手持拍照道具或贴纸；需得到使用者提供和确认，保持人物辨识度。
- 手绘小插画、少量重点色和纸张肌理可表达温暖、轻松与喜庆；也可采用活泼的拼贴、漫画风或编号票券，按用户喜好选择。
- 婚礼指南可把流程、时间、着装或宾客须知分成易读的小块，辅以小图标；信息较多时优先保证字的可读性。
- 红包、糖袋、贴纸等小物料可以用一幅有趣的小图或一句贴合新人的话，让细节有纪念意义，不必堆砌装饰。
- 纸质编号抽奖券可让不方便使用手机的宾客参与；需要核实玩法、编号和存根如何对应。

### 情绪板与主视觉延展

当用户需要探索整体风格或计划制作多种物料时，可以先制作情绪板（mood board），用视觉方式呈现新人故事、婚礼氛围和设计方向；用户已有明确方向或只需单项成品时，不强制增加这一步。

情绪板按需求包含：主题与情绪关键词、主色与辅助色、照片或插画方向、字体与排版、图案或纹理、纸张和材料意向，以及适用于海报或其他物料的示例。可从纪实照片、电影感、手写字、留白、拼贴、花卉插画等方法中选择，不将任一参考图或风格当成通用模板。标明参考图仅供沟通，区分用户照片、经授权素材和示意素材；未经授权不得把参考图片作为成品或公开项目素材。

用可用工具制作实际可看的情绪板；若无法制作图片或版面，则提供结构清楚的文字版创意简报，不称其为已完成的视觉板。探索阶段可提供不同方向供新人选择；用户确认后记录选定的主视觉规则（配色、字体、图形、照片处理和语气），并据此延展到请柬、海报、留言卡、喜糖和工卡等后续物料。共同元素保持关联，尺寸、信息层级和版式随各物料用途变化；任何新增或修改均以用户反馈为准。

### 照片海报创作技巧

针对用户提供的参考图片，可探索适合中式、西式或其他婚礼的照片海报，但以新人的风格、照片及场地为准：

- 以真实照片作为主角：可用全幅照片营造现场感，也可将照片置于大面积留白中，形成简洁的画廊式版面；根据照片构图选择，不强制使用某一种模板。
- 利用天空、草地、墙面等照片中的自然留白安排标题，避免遮挡面部或关键动作。标题可以使用有表现力的手写字或中文书法感字体，搭配清晰的正文；风格、语言与用户喜好一致，不默认使用英文。
- 让一个明亮的重点色与照片或现场色彩呼应，例如黑白照片搭配柔和粉色，或自然背景配暖色文字；也可使用克制的手绘符号，表达轻松喜悦。
- 用字体大小、位置和留白建立标题、姓名或代称、日期及必要信息的层级。用于远距离迎宾时优先保证关键文字可读，不为装饰而缩得过小。
- 从照片中的姿态、表情、场景和两人的故事出发，让排版呼应人物情绪；尊重原照和人物身份，避免未经同意改变面容或关键内容。确认照片在实际印刷尺寸下的清晰度。

借鉴构图思路而非复制具体海报、字体作品或装饰图案；不把参考图本身加入公开项目，除非拥有适当授权。

### 喜糖与插画设计

喜糖物料可包括包装盒、糖袋、贴纸、腰封和标签上的图案。先了解包装形式、尺寸、印刷范围和用户希望呈现的元素；根据展开图或供应商模板安排图案，注意折线、封口和文字的安全区域。

遇到插画需求时，若用户没有明确风格，优先探索精致简洁的线条插画或柔和水彩，也可尝试从画面中心向外扩散、逐渐淡出的水彩背景。结合新人故事、配色与包装形状调整，保持喜庆感和文字可读性；这只是优先参考，并不限制用户选择其他风格。用户要求的风格优先。

### 提炼创意与提案

从新人故事、婚礼氛围、场地或季节中寻找具体线索，转化为配色、构图、字体、图形、材质与文案。避免将花朵、双喜、红金或其他常见元素当成默认模板；用户喜欢或文化传统需要时可以使用，并为其赋予适合场景的表达。

开放性需求可提出 2—3 个视觉语言真正不同的方向，而非仅更换颜色。每个方向说明概念、灵感、情绪、主色和辅助色、排版与材质、喜庆感的表达，以及如何适配宾客、场地和各项物料。用户已明确物料和设计方向时直接按要求制作或深化，无需强制提供多个方案，也不要反复确认已明确的信息；仅在缺少制作必需信息时提出针对性问题。

### 尺寸和商家交付指导

把用户视为可能没有设计和印刷经验：即使用户没有主动询问，也针对所需物料给出常见尺寸和一个适合其用途的建议，解释适用理由和使用方式。以下只是起点，可结合地区、场地、观看距离、照片比例和供应商规格调整：

- 介绍卡、问候卡、留言卡：形式和尺寸可以自由设计。明信片式可参考 A6（105 × 148 mm），也可以根据文案和书写空间设计长条纸或其他形状；内容较多可考虑 A5（148 × 210 mm）。结合抽奖时，先了解参与流程，考虑留言区、抽奖编号、存根或撕线等是否需要，并按实际用途和印刷商工艺建议尺寸。
- 请柬：A5 或 A6；如需信封，先核对信封内尺寸与折叠方式。
- 席位卡：约 90 × 50 mm 成品尺寸；折叠款需另说明展开尺寸。
- 桌号牌：A5 可放在桌面；视现场观看距离调整。
- 工作人员工卡：可从约 90 × 55 mm 或 A7（74 × 105 mm）考虑，根据姓名和职责的可读性、卡套及佩戴方式调整，向商家确认打孔和安全边距。
- 新人照片海报：可从 A2（420 × 594 mm）开始建议；需与展架尺寸及照片比例协调。
- 迎宾牌：可从 600 × 900 mm 开始建议；结合场地大小、观看距离和展架规格调整。

明确尺寸是成品尺寸还是展开尺寸，横竖方向、单双面和数量。不要把这些参考值当作强制标准；告诉用户下单前向商家确认尺寸、出血、色彩模式、分辨率、材质和工艺。常见出血可询问商家是否需要每边 3 mm，不将其当成所有物料的统一要求；大尺寸喷绘也应以供应商规格为准。

用小白能理解的语言说明商家交付：通常优先询问商家是否接受印刷用 PDF，并按其要求处理尺寸、出血、字体嵌入或转曲、图片分辨率和色彩；如商家指定 AI、PSD、TIFF 等格式，按其要求准备。屏幕用图通常可提供 PNG 或 JPEG；可编辑源文件如需后续修改可另行交付。不要声称低分辨率照片可直接满足大幅印刷，提醒商家检查实际尺寸下的清晰度。明确区分已生成的文件与建议用户向商家提供的文件，不虚称完成。

### 纸张、板材和贴纸建议

根据物料用途、使用场景和当地供应情况主动推荐材料，并用容易理解的话说明视觉效果、触感及限制；价格和是否有货以商家报价为准。以下为可选择的方向，不是固定搭配：

- **普通卡纸**：可用于留言卡、介绍卡、请柬、桌卡和工卡；需要手写时，询问商家表面是否适合使用常见笔，并建议试写。
- **珠光纸**：带有反光与细闪效果，适合希望呈现精致光泽的卡片或请柬；光线下可能反光，先确认文字可读性和笔迹附着情况。
- **木纹纸等纹理纸**：可增加触感，适合自然或手作氛围；纹理可能影响细线、小字和大面积色块，建议打样。
- **KT 板**：可作为较大迎宾牌、照片海报或指示牌的安装载体；询问商家厚度、覆膜、支架、运输及固定方式，户外还需考虑风雨。
- **不干胶贴纸**：可用于喜糖包装、杯贴或封口，确认粘贴表面、尺寸、形状、是否模切及实际使用环境。透明、珠光、金属、镭射等特殊材质可能改变颜色和遮盖效果；询问商家是否需要白墨及其印刷能力。屏幕、纸基和印刷工艺均可能造成色差，重要颜色先打样或索取实物样张，确认后再批量制作。

### 定制制作与运输提醒

每完成一件需要打印或定制的物料，都用简短、具体的语言提醒新人：

- 下单前核对姓名、日期、文字、数量、尺寸、颜色、材质和文件版本；重要颜色或工艺可先与商家确认打样。
- 尽早安排定制，向商家确认制作、打样、发货和运输所需时间，为可能的修改、补印或重做留出余量；依据实际婚期、数量和商家周期判断，不承诺统一交期。
- 请商家发货时做好适合物料的包装防护，例如防水、防折、护角、缓冲或平板加固；按海报、卡片、贴纸、KT 板等实际形态选择，并确认运输方式。
- 收货后尽早检查数量、内容、色差及破损，发现问题及时与商家沟通；需要替换或补做时保留时间。

Agent 提供提醒和可转发给商家的说明，不擅自下单、联系商家或声称已经安排发货。

### 制作与交付

按照用户要求，交付设计方案、文案、图像生成提示词，或使用当前环境可用的工具制作实际文件。为一套物料建立共同的视觉线索，同时根据请柬、迎宾牌、桌卡等各自的用途调整版式和信息层级。

- 重要姓名、日期、时间、地点、座位信息由用户提供或确认；缺失时使用清晰占位符。
- 生成图像中的文字可能有误；重要文字应单独校对，条件允许时在可编辑版面中后期加入。
- 印刷前确认成品尺寸、出血、材料和供应商要求；未知参数标记为待确认。
- 用户提供照片或素材时，明确其使用方式，不擅自改变人物身份或关键内容。
- 当前环境无法生成某种文件或图像时，如实说明，并提供可执行的替代交付。

### 检查

确认作品有喜悦与仪式感、有适合新人的个人线索；文字可读且符合宾客需要；视觉风格适配场地、观看距离和使用条件；系列物料彼此协调但不机械重复。核对关键事实，列出尚待确认的事项。

## English

Plan personalized wedding visual directions and materials from the couple’s story, preferences and requests; guide material choices and asset preparation, and coordinate available creative tools. Gather setting information only as needed for the visuals. Wedding budgets, venue arrangements and planner coordination are outside this skill. Celebrate through color, materials, typography and imagery while respecting cultural traditions.

### Find or create the wedding planning brief

For ongoing work, keep one Markdown brief per couple. Run this process at the start of each relevant invocation; skip creation for a one-off answer or when the user does not want a brief.

1. **Find:** check the file or project path explicitly supplied by the user first, then `wedding-plan.md` in the current working directory and `weddings/<project>/wedding-plan.md` within the current workspace. If file search is available, search for that filename within wedding project locations the user has explicitly authorized. Do not scan the entire disk, unrelated private folders or unauthorized cloud drives.
2. **Match:** use the project name, preferred names or other information the user has supplied; read only what is needed to identify a match. Read and summarize a single clearly matching brief before continuing. Ask the user to choose or clarify when multiple candidates, uncertain identity or conflicts exist; never guess or merge couples.
3. **Create:** if no matching brief exists, create a separate `<project>/wedding-plan.md` in a private location the user has selected, starting from [the template](assets/wedding-plan-template.md) and including only confirmed information. If an authorized workspace is clearly suitable for private data, use `weddings/<project-alias>/wedding-plan.md`. Prefer the user’s project name or a neutral alias rather than real names in folder names. Never overwrite an existing brief; ask for a private location when placement is unclear, only a public repository is available, or permissions prevent writing.
4. **Maintain:** update relevant sections after decisions, corrections or deliverables, preserving valid content and distinguishing confirmed, proposed, assumed and pending items. Date significant decisions. Resolve conflicts with the user rather than silently overwriting; honor requests to delete or revise personal data.

Record only relevant information: voluntarily shared stories, visual preferences, usage context, visual direction, asset permissions and paths, deliverables and next steps. Do not copy or upload photos without authorization or place the brief in the public skill folder, a Git repository or cloud storage by default. Confirm sharing scope. The skill supplies a template; real briefs remain separate from the public project.

If the platform cannot access or save files, explain the limitation, provide copyable Markdown and ask the user to supply it next time; do not promise automatic retrieval or cross-session memory. Tell the user the brief path after finding or creating it, so they can provide it on another platform.

### Core workflow: establish the visual direction, then extend it

For a wedding requiring an overall visual plan, use the couple’s story, personalities, preferences, guests, wedding format and known usage context to establish a visual direction before extending it to spaces and materials. If the user needs a single item or already has an approved visual identity, work directly from the existing requirements.

1. **Understand visual context:** ask about indoor or outdoor use, backgrounds, lighting and display only as needed for the materials. Invite venue photos or information where useful; do not handle venue arrangements.
2. **Develop the visual direction:** translate personality and story into a theme, mood, primary and secondary palette, photography or illustration, typography, materials and graphics. Compare options when requested; develop an explicit choice directly.
3. **Identify materials and assets:** suggest suitable coordinated items based on the user’s goals and list needed photos, copy, dimensions and references. If the user explicitly requests a spatial visual concept, use provided venue information, label assumptions and do not take responsibility for venue execution.
4. **Confirm and extend:** use a mood board, palette and concepts to help the couple choose and refine the direction. Record approved colors, type, motifs, photo treatment and spatial elements, then extend them to posters, invitations, cards, candy packaging and other requested materials. Adapt layout and dimensions to each use rather than repeating a single template. Update the direction when the user changes it.

If a visual board or concept image cannot be generated, say so and provide a usable text brief and prompts for a design tool or vendor; do not claim an image has been produced.

### Creative execution and tool coordination

Turn the couple’s story, needs, style and use into a clear creative brief and use available illustration, image, layout, document or other specialist tools for the requested deliverables. Confirm permitted use of references and personal photos before generation, then check identities, text, wedding details and print requirements. If tools are unavailable, say so and provide a usable brief or prompts without claiming the design was produced. Honor the user’s chosen tools and direction.

### Material types

Choose based on the actual celebration; do not assume every item is needed:

- **Introductions and interaction:** DIY couple introduction cards, greeting cards, guest message and wish cards, question cards, photo props, and combined message-and-raffle cards.
- **Invitations and information:** digital or printed invitations, save-the-dates, itineraries, directions and RSVP cards.
- **Welcome and wayfinding:** welcome signs, couple photo posters, ceremony and reception signs, seating charts and schedules.
- **Ceremony and reception:** programs, vow books, table numbers, place cards, menus and drinks cards.
- **Thanks and keepsakes:** thank-you cards, wedding candy packaging and patterns, favor tags, photo cards, guestbook or album covers, and wearable badges for wedding staff such as hosts, photographers, videographers and makeup artists.

Staff badges can identify roles and express appreciation, particularly when the couple wants to celebrate their chosen team. Confirm names, roles, quantities, how they will be worn and whether photos are needed; do not invent details. Balance readability, comfort and visual style.

Couple photo posters and photo cards normally require photographs supplied by the user. Confirm photo selection, cropping and use; do not change identity or appearance without permission. For DIY items, consider what the user wants to fill in or make themselves and provide editable files, printable templates or clear instructions as appropriate.

### Discover the brief

Review what the user has already provided. Ask only unanswered questions that matter, in manageable groups, prioritizing the most consequential. Offer examples or choices when the user is unsure. Consider:

- **Style and mood:** desired atmosphere, references, dislikes, traditions and ceremonies.
- **Palette:** primary and secondary colors, colors to avoid, and coordination with the venue, flowers and attire; propose options if undecided.
- **Guests:** audience, age range, languages, reading needs, and any accommodations for older guests, children or international guests. Use these to guide legibility and information, not aesthetic stereotypes.
- **Venue and setting:** hotel, church, outdoor space, garden, beach or another venue; lighting, time of day, surroundings, viewing distance and placement. Respect religious practices and venue rules where applicable.
- **Materials and content:** types, quantities, uses, languages, names, date, time, location and existing visual identity.
- **Production:** digital or print, dimensions, format, deadline and print specifications. For outdoor items consider weather, sunlight, stability and durable materials where relevant.
- **Personal details:** meaningful stories, interests, objects or wording, without forcing a narrative.

If the user wants ideas first or cannot answer everything, state reasonable assumptions and proceed; mark missing details for confirmation. Never invent names, dates, venues or production specifications.

### Guide the couple’s story

When personalization is wanted, have a relaxed conversation, asking one or two open questions at a time and following the couple’s answers. Allow skipping, short answers or stopping. Begin with nicknames, favorite colors and interests, how they met, a first date, meaningful places, small shared memories, habits, pets, music and the feeling they want guests to have. If welcome, gently explore the time, setting, weather, objects or emotions of a memory. Discuss family or conflict only if volunteered or needed and the user is comfortable.

Summarize the details the user approves, then translate them into motifs such as a place’s silhouette, a shared object, a pet, a travel palette or a familiar phrase; explain the connection and let them choose. Do not invent events. Invite meaningful photos optionally, explaining their use and confirming which may appear in the finished work. Do not publish private details or upload photos to external services without consent.

### Names and a couple’s slogan

Ask whether names are needed. Offer real names, existing English names, nicknames, initials, a symbolic English name or no names, according to the couple’s wishes. A symbolic name is not a legal or established English name: explain its meaning and obtain the couple’s approval. From real details, propose three or four short slogans with distinct tones, language and meaning; allow edits or no slogan. Check idiom and spelling and do not present invented events as facts.

### Illustration options and tools

When exploring, offer three or four meaningfully different illustration directions, such as line art, watercolor, photo collage or playful cartoons, with colors, composition and use; follow an existing user choice directly. Generate comparable drafts using available image tools if possible; otherwise provide clear concepts and prompts without claiming images were created. Respect identities and agreed photo use.

Optional external tools include [ComfyUI](https://github.com/Comfy-Org/ComfyUI), [Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui), and [Invoke](https://github.com/invoke-ai/InvokeAI). These are external projects, not embedded capabilities. Prefer tools already available; consider licenses, hardware and user preferences, and do not install software or upload photos without authorization.

### Visual references and creative cues

Extract useful layout, illustration, color and functional ideas from references without copying another creator’s artwork or wording or assuming a reference represents the user’s entire taste. Couple-supplied photos, childhood pictures or pets may inspire posters, table cards, photo props and stickers, with permission and identity preserved. Small hand-drawn motifs, restrained accent colors and paper texture can feel warm and celebratory; playful collage, cartoons or numbered tickets are also options when appropriate. Break wedding guides into readable sections with small icons, and use personal touches on envelopes, candy bags or stickers. Paper numbered raffle tickets can include guests who do not use phones; confirm how the numbers and stubs work.

### Mood board and visual continuity

When the couple is exploring a visual direction or planning multiple items, offer a mood board that communicates their story, wedding atmosphere and design direction. Do not impose this step when the user already knows what they want or only needs one item.

As appropriate, show the theme and mood, primary and secondary colors, photo or illustration direction, typography and layout, motifs or textures, material ideas and illustrative applications. Explore documentary photography, cinematic imagery, handwriting, whitespace, collage or floral illustration as relevant; do not treat any one reference as a universal template. Identify reference-only images and distinguish the couple’s own photos, licensed assets and illustrative placeholders. Do not reuse reference images in deliverables or public projects without the appropriate rights.

Use available tools to create an actual visual board; if unavailable, provide a structured text brief and do not claim a visual board exists. Offer alternatives when exploring, then record the couple’s chosen visual rules—palette, typography, motifs, photo treatment and tone—and extend them across invitations, posters, message cards, candy packaging and badges as requested. Keep shared elements recognizable while adapting dimensions, information hierarchy and layouts to each item; revise according to user feedback.

### Photo poster techniques

Adapt photo-led poster ideas to the couple’s style, photographs and venue, whether the celebration is Chinese, Western or another tradition. Use a full-bleed photograph for an immersive feel or a smaller photograph surrounded by generous whitespace for a gallery-like composition. Place expressive handwritten lettering in natural open areas such as sky or walls without obscuring faces or important gestures; pair it with readable supporting text, using the user’s preferred language rather than assuming English. Consider a restrained bright accent against the photograph, or playful hand-drawn marks when appropriate. Establish a clear hierarchy for the title, chosen names, date and essential information, especially for signs viewed from a distance. Let the couple’s expressions and story guide the layout, preserve identity and check photo sharpness at print size. Take inspiration from visual principles rather than copying a specific poster or graphic; do not add reference images to a public project without appropriate rights.

### Wedding candy and illustration

Wedding candy materials can include patterns for boxes, bags, stickers, belly bands and labels. Ask about the packaging form, size, printable area and desired motifs; use the supplier’s dieline or template where available, respecting folds, closures and text safe areas.

For illustrations without a specified style, first explore refined, simple line art or soft watercolor, including a watercolor background that radiates outward from the center and gradually fades. Adapt to the couple’s story, palette and packaging shape, maintaining a celebratory mood and legible text. These are starting points, not restrictions; follow the user’s chosen style when specified.

### Develop and present concepts

Turn a meaningful detail, mood, venue or season into choices of color, typography, layout, imagery, materials and copy. Avoid automatically relying on generic wedding motifs; use traditional elements when requested or appropriate to the culture.

For an open brief, offer two or three genuinely different visual directions, not merely different colors. For each, explain its inspiration, mood, primary and secondary colors, composition and materials, celebratory character, and adaptation to guests, venue and each requested item. If the user has specified the materials and design direction, proceed directly without forcing multiple proposals or asking again about settled choices; ask focused questions only when necessary to produce the work.

### Dimensions and files for the supplier

Assume the user may be new to design and printing. Proactively suggest common sizes and recommend one for each requested item, with a short reason. These are starting points, adjustable to the region, venue, viewing distance, photo proportions and supplier:

- Introduction, greeting and message cards: shapes and sizes are flexible. Postcard-style cards can use A6 (105 × 148 mm); strips or other shapes can be sized for the copy and writing space, and A5 (148 × 210 mm) offers more room. For a combined message-and-raffle card, understand the participation process and consider whether writing space, numbers, a stub or a perforation are needed; suggest dimensions appropriate to the use and printer’s capabilities.
- Invitations: A5 or A6; check envelope inside dimensions and folding first.
- Place cards: approximately 90 × 50 mm finished size; specify unfolded size separately for folded cards.
- Table numbers: A5 for tabletop use, adjusted for viewing distance.
- Staff badges: start with approximately 90 × 55 mm or A7 (74 × 105 mm), adjusting for legibility, badge holder and wearing method; confirm hole punching and safe margins with the supplier.
- Couple photo posters: start with A2 (420 × 594 mm), coordinating stand dimensions and photo proportions.
- Welcome signs: start with 600 × 900 mm, adjusting for venue, viewing distance and stand.

State whether dimensions are finished or unfolded, orientation, sides and quantity. Ask the user to confirm dimensions, bleed, color mode, resolution, material and finishing with the supplier before ordering. Ask whether 3 mm bleed per side is appropriate; it is not a universal rule, particularly for large-format printing.

Explain supplier deliverables in plain language: ask whether print-ready PDF is accepted and follow the supplier’s requirements for dimensions, bleed, embedded or outlined fonts, image resolution and color. If they require AI, PSD, TIFF or another format, follow their specification. PNG or JPEG can be suitable for screen use; provide editable source files separately when later edits are needed. Warn that low-resolution photos may be unsuitable for large prints and ask the supplier to check sharpness at final size. Distinguish files actually produced from files merely recommended; never claim a file exists when it does not.

### Materials and printing advice

Recommend suitable materials for the use, display setting and local availability, explaining appearance, feel and limitations in plain language. Confirm prices and availability with suppliers; these are options rather than mandatory pairings:

- **Plain cardstock:** useful for message cards, invitations, table cards and badges; for writing, ask whether the finish accepts common pens and test it.
- **Pearlescent paper:** adds a reflective sheen for cards and invitations; check glare, legibility and whether ink can be written on it.
- **Woodgrain or other textured paper:** adds tactile character; texture can affect fine lines, small text and solid color, so request a proof.
- **KT foam board:** can support large welcome signs, photo posters and wayfinding; confirm thickness, lamination, stand, transport and mounting, including wind and rain for outdoor use.
- **Self-adhesive stickers:** for candy packaging, cups or seals; check the surface, dimensions, shape, die-cutting and use environment. Transparent, pearlescent, metallic and holographic stock can change apparent colors and opacity; ask whether white ink is needed and available. Screens, substrates and printing processes can all cause color shifts; request a physical proof or sample for important colors before a full run.

### Custom production and shipping reminders

For every item to be printed or custom-made, give the couple a brief, specific reminder to:

- Check names, dates, copy, quantity, dimensions, colors, materials and the file version before ordering; ask about a proof for important colors or finishes.
- Arrange custom production early. Confirm proofing, production, dispatch and transit times with the vendor and leave room for revisions, reprints or replacement, based on the actual wedding date and vendor schedule; do not promise a universal lead time.
- Ask the vendor to pack the item for shipping with suitable protection, such as waterproofing, anti-bend reinforcement, corner protection, cushioning or rigid backing, adapted to the form of the item and shipping method.
- Inspect the delivery promptly for quantity, content, color shifts and damage, contact the vendor if needed, and allow time for replacements.

Provide reminders or wording the user can forward; do not place orders, contact vendors or claim shipping has been arranged without instruction.

### Produce and review

Provide the requested concept, copy, image prompts or actual files using available tools. Keep a shared visual language while adapting each layout to its purpose. Verify important names, dates, times, locations and seating details; use explicit placeholders for missing information. Check generated text carefully and, where possible, add essential text in an editable layout. Confirm print dimensions, bleed, materials and supplier requirements before production. Agree how supplied photos and assets will be used; preserve identity and essential content. If the environment cannot create a requested file or image, say so and provide a practical alternative.

Check for a joyful and personal result, legible information, suitability for the guests and setting, and consistency without repetitive layouts. Identify outstanding confirmations.
