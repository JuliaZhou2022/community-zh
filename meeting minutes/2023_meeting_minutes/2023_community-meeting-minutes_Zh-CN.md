# 2023-12-26开源指南针会议纪要
## 时间
北京时间2023年12月26日下午14:15~14:25
## 与会人
[王晔晖](https://github.com/eyehwan)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass前后端、运营事项进展讨论
### 前端
1. 三维评估体系图增加了“统计中”文字提示。
2. 移动端贡献者模型不能点击的bug已修复。
3. 项目深度洞察贡献次数分布饼图标题中添加了贡献总次数值。
4. Compass协作已有的5个案例已做缩放，待添加2个新案例。
    - **AP：赖兴友尽快添加。**
### 后端
1. 后端模型已优化，跑数据的速度提升5-10倍。
2. 需要统计跑完已收录社区全局数据的时间。
    - **AP：覃华添进行统计。**
### 运营
1. 本周发布近期功能更新详细介绍文章。
   - **AP：李升保、赖兴友录屏、整理介绍文字初稿，周冉编辑视频、优化文字并发布。**
2. 年会回顾视频、文案已发。
3. 年报1月份发布。
   - **AP：周冉尽快整理内容。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-12-19开源指南针会议纪要
## 时间
北京时间2023年12月19日下午14:15~14:31
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass产品方案及前后端、运营事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察）方案
    - 评估体系三维图挂件里未统计或统计中的指标值显示为 0 ，需要添加文字提示。
      - **AP：赖兴友与覃华添核对进行修改Compass侧，覃华添修改Gitee侧。**
2. Compass协作
   - 新增两个南京大学的案例，需要重新设计展示形式。目前建议把原来已有的5个案例缩小，直接加，以节省修改时间成本，后面有需要时再重新设计。
      - **AP：赖兴友尝试修改，看是否可行。**
### 前后端
1. 部分重跑后的模型数据需要优化。
    - **AP：李升保尽快优化。**
2. 近期不再进行大规模更新，专注修补最近功能更新的bug。
### 运营
1. Board会议及年会顺利召开，反馈很好。
2. 开始社区年报的内容整理与设计工作。
    - **AP：周冉整理内容，钟峰设计。**
3. 公众号认证、B站号注册。
    - **AP：张盛翔尽快完成。**
4. 年会回顾文案尽快发布。
    - **AP：周冉尽快完成视频及文案发布。**
5. 需要出文章介绍如何在Github的readme嵌入compass评估体系三维图挂件。
    - **AP：周冉尽快完成相关文章并发布。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-12-07开源指南针会议纪要
## 时间
北京时间2023年12月07日下午14:15~14:59
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)、南大-司徒凌云
## 主题——Compass产品方案及前后端、官网事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察）方案
    - 贡献者三个模型今天完成。
    - 新增图表数据接口已完成。
    - 治理仓与软件制品仓对比分析bug待解决。
       - **AP：赖兴友、覃华添本周内尽快解决。**
    - OpenHarmony、openEuler、openGauss、MindSpore这4个社区2周内的数据已上灰度，目前在跑3个月内的数据。
       - **AP：覃华添尽快跑完，并及时分配资源给GVP仓。**
2. Compass学术
   - 名称改为Compass协作。
   - 已有北大、南大、openEuler等6个案例。
    - 文本国际化已完成。
    - 收集问卷暂时改邮箱联系，修改原有文案。
       - **AP：王晔晖提供修改内容，赖兴友修改前端。**
    - 立即体验前端已OK，后端待提交数据。
       - **AP：李升保今天提交。**
   - 南大提供的工具是私有项目，工具可部署到Compass。建议打包成web服务。
       - **AP：李升保跟覃华添讨论解决。**
3. Gitee指数替换
    - 已部署到灰度，有些小bug，后续再修复。
    - OpenHarmony、openEuler、openGauss、MindSpore这4个社区的Gitee GVP仓原有Gitee指数图备份。
      - **AP：李升保进行备份。**
### 官网
1. 文档页尽快更新：
    - 评估体系文档结构改为与看板页面类似的结构。
        - **AP：李升保尽快更新文档结构、王晔晖补充内容。**
     - 公众号已发布的三篇关于评估体系的文章需要翻译并在本周五更新到网站。
       - **AP：周冉翻译文章，王晔晖提供图片翻译，赖兴友更新前端。**
2. 日历前端已添加例会与年会事件，待后端部署。
### 前后端
- opensearch深度查询scroll id数量异常问题已解决。
### 运营
1. 年会过程需要制作3页ppt，作为会前、茶歇、结束时LED展示的内容。
   - **AP：周冉创建issue，钟峰设计制作。**
2. 全部功能上线后进行demo录屏，作为年会开场视频素材。
   - **AP：王晔晖周末提供录屏素材，周冉制作视频。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-12-05开源指南针会议纪要
## 时间
北京时间2023年12月05日下午14:15~15:03
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)、悬镜安全-奇秋月、悬镜安全-陈超
## 主题——Compass产品方案及前后端、官网事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察）方案
    - 三个新模型的数据需尽快跑完。
         - **AP：李升保尽快把数据列表提供给覃华添。**
    - OpenHarmony、openEuler、openGauss、MindSpore这4个社区最近半年数据尽快跑完。其他社区根据情况，尽量全部跑完，可以先只跑半年内的。
         - **AP：李升保尽快把以上4个社区的数据表格提供给覃华添。**
    - 部分模型数据有问题，需要修正。
         - **AP：王晔晖跟覃华添、李升保确认修改。**
    - 贡献者模型增加贡献次数图。
    - 明年需要允许管理者、用户更改贡献组织信息。具体实施需要再讨论。
        - **AP：王晔晖组织相关讨论。**
    - 领域画像的5个类别用不同颜色区分。
        - **AP：赖兴友进行修改。**
    - 新增的三个模型需要补充文案。
        - **AP：王晔晖提供文案。**
    - 新增图表数据需要出接口，
        - **AP：赖兴友整理具体需求，李升保协助覃华添尽快提供。**
2. Compass学术
    - 前后端已基本完成。
    - 需进一步拓展功能，为开源社区改进提供学术研究成果或者工具解决方案。
        - **AP：王晔晖补充文案。赖兴友进行前端更新。**
3. Gitee指数替换
   - 本周进行，周末完成。
    - 周末或下周进行Compass替换Gitee指数的宣传。
### 官网
1. 评估体系三维图部署中。
    - **AP：钟峰查看前端，给出优化建议。**
2. 文档页先更新已有的内容，其他内容年会后再补充。
### 前后端
1. opensearch深度查询scroll id数量异常，导致多个队列争抢scroll id资源。
    - **AP：覃华添、李升保查看原因并解决。**
2. 二级分类目前新PR合入速度放缓，待Gitee指数替换完成后再提高合入速度。
3. 数据查询时间限制需要在社区Board会议中详细讨论。
    - **AP：王晔晖安排Board讨论。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-30开源指南针会议纪要
## 时间
北京时间2023年11月30日下午14:15~14:45
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[齐国强](https://github.com/guoqiangqi)、[周冉](https://github.com/JuliaZhou2022)、止戈
## 主题——Compass产品方案及前后端、官网事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察）方案
   - 界面名称改为“项目深度洞察”。
   - 重新设计的方案确认OK，前端可开始。
      - **AP：赖兴友尽快开始前端工作。**
    - 详细化指标饼图颜色需再调整。
       - **AP：赖兴友进行相应调整。**
2. Compass学术
    - 合作流程已完成，研究领域部分需确认文案，前端按目前设计开始。
      - **AP：周冉与张盛翔确认最终文案。赖兴友开始前端开发。**
    - 申请验证页面设计方案尽快提供给前端。
      - **AP：钟峰尽快提供这部分设计方案。**
### 官网
- 评估体系三维图已调整，整体效果已优化，可继续前端开发。
   - 图下方不显示数据。
   - 接口已创建，前端可导入真实数据。
   - 设计需要与Gitee前端同步。
     - **AP：钟峰跟Gitee侧前端沟通。**
### 前后端
1. 生产中出现的bug已修复，贡献者画像今天完成。
2. OpenSearch已扩容。
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-28开源指南针会议纪要
## 时间
北京时间2023年11月28日下午14:15~14:56
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[齐国强](https://github.com/guoqiangqi)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass产品方案、官网前后端事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察） 方案
   - 前端已删除没有的模型，增加了贡献者相关模型。
   - 删除了指标表格页面中的滚动条。
   - 指标模型展示形式需要适配Gitee需求。
     - **AP：覃华添确认需要进行哪些调整。**
   - 指标表格太长，需要冻结首列。
     - **AP：赖兴友进行前端修改。**
   - 里程画像模型后端已完成，待测试。
     - **AP：李升保尽快完成测试。**
   - 年会前完成贡献者画像三个模型即可，其他模型后续再完成。
   - 领域画像表格筛选
     - **AP：赖兴友与覃华添核对具体数据。**
2. Gitee 指数方案讨论 （token）
   - 方案已定，后端进行中。
   - 将会对推荐的2万多个仓库进行Gitee指数替换。
     - **AP：覃华添与李升保核对OpenHarmony、openEuler相关仓库，确认具体sig与仓库清单。**
3. Compass学术方案
   - token已增加至60多个。
   - 页面设计已初步完成。
     - **AP：张盛翔补充合作流程内容。周冉创建腾讯问卷账号，用于创建问卷、收集信息。赖兴友开始前端开发。**
### 官网
1. 评估体系三维图前端开发进行中，Gitee侧也用图表展示。
   - **AP：赖兴友与钟峰核对具体设计调整。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-23开源指南针会议纪要
## 回放 
https://meeting.tencent.com/user-center/shared-record-info?id=bd439590-0e7b-4955-9612-375ea7f99b04&from=7
## 时间
北京时间2023年11月23日下午14:15~15:02
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察） 方案
   - 标题及文字说明已更新，贡献者页面前端重构进行中。
       - **AP：赖兴友尽快完成重构并部署到灰度上。**
   - 后端工作已完成并通过验证。
2. Gitee 指数方案讨论 （token）
   - 新增10个token，总共需要60-70个。
      - **AP：张盛翔现在开始每天增加token供应。李升保跟进后端进度。**
3. Compass学术方案
   - 南大项目预测模型后端代码已合入，前端设计与开发待开始。
      - **AP：张盛翔尽快提供文字说明，王晔晖与钟峰讨论具体呈现方式，钟峰尽快提供前端设计方案。**
### 官网
1. 首页三维评估体系架构图是以图表还是挂件的形式展示需决策。
   - 三维挂件无法实现SVG渲染，需要在前端库中进行绘制，会出现不同项目的版本兼容性问题。
   - 建议Compass官网直接用图表形式展示，Gitee网站可以考虑用挂件形式。
      - **AP：钟峰与黄超群确认最终解决方案。**
2. 网站上未上线的模型相关中英文文档已提交[PR](https://github.com/oss-compass/docs-zh/pull/7)进行删除。
3. 文档页内容分工需尽快进行。
    - **AP：李升保与周冉跟进分工与内容更新。**
### 前后端
1. 详细化指标后端完成。
2. 网站需进行opensearch扩容。
    - **AP：覃华添尽快进行扩容。**
### 运营
1. 权限管理界面需要进行设计和开发，以满足不同数据访问权限要求。建议：年会后开始进行。
2. 芝加哥大学的一位研究者（台湾人）请求访问Compass数据进行学术研究，需要决策。
   - 建议：了解清楚国家、企业数据出境的规则，以及对方需要多少数据，这种合作能够提供给Compass什么价值。
      - **AP：王晔晖与该研究者用邮件保持沟通，12月组织Board进行讨论。**
3. 龙文选公司接入Compass数据后，使用中暂无问题，后续有问题再讨论。
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-21开源指南针会议纪要
## 时间
北京时间2023年11月21日下午14:15~15:05
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察） 方案讨论
    - **AP：王晔晖向赖兴友提供相关标题及文字说明调整方案。**
2. Gitee 指数方案讨论 （token）
   - 新增20个token。
3. Compass学术方案讨论
    - **AP：王晔晖、钟峰、张盛翔再讨论。**
### 官网
1. 评估体系架构图进展：设计方案初步成型，正在从平面图转换为3D图，仅首页展示，项目报告页不需要进行展示。
    - **AP：钟峰尽量周三出设计稿，赖兴友周三中午前修改前端。**
2. 官网首页前端调整进行中，图片轮播目前先放项目分析和详细化指标两个页面。
    - **AP：赖兴友尽快完成前端调整。**
3. 文档页大纲已创建[PR](https://github.com/oss-compass/docs-zh/pull/5)，待周四开会分工。
### 前后端
1. 仓库多标签数据抓取方案[Issue](https://github.com/oss-compass/compass-projects-information/issues/787)已创建，需讨论。
    - **AP：王晔晖与张盛翔再讨论。**
###   运营
1. 12月13日社区Board会议议程安排已发给Board；年会邀请函已发，听众邀约已完成，参会者预计50人左右。
2. 年会活动流程细节设计进行中，会场布置物料设计制作进行中。
    - **AP：周冉与钟峰商量签到墙海报设计及LED屏播放海报设计。**
3. 年会活动结束后合作宣发媒体待沟通确认。
    - **AP：周冉与龚宇华商量媒体宣传事宜。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-16开源指南针会议纪要
## 时间
北京时间2023年11月16日下午14:15~16:05
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)、汪亮-南大、李小明-开源社、刘天栋-开源社、SamHu（建裕）、王婕、胡宇齐-港科大
## 主题——Compass产品方案、前后端开发、官网及运营事项进展讨论
### 产品方案
1. Project Deep Dive Insight（项目深度洞察） 方案讨论
   - 项目报告页的详细化指标部分命名为“项目深度洞察”产品。
   - 项目深度洞察界面主页设计已调整，主要展示贡献者、Issue、PR三个维度的指标，二级页面饼图颜色风格及顺序已重新设定。
      - **AP：赖兴友调整前端后再请大家看是否合适，王晔晖重新从用户角度考虑并提供相关标题及文字说明。**
2. Gitee 指数方案讨论 （token）
   - Gitee指数替换初步方案已出，需要讨论如何让用户更容易理解新的指标以及如何与之前的Gitee指数做对应，替换过程中Compass未收录的仓库需要设置收录门槛。
     - **AP：王晔晖、张盛翔、钟峰再讨论如何展示新指标以及新旧指标的关系，王晔晖、张盛翔确认仓库收录门槛。**
   - 张盛翔今天给覃华添一批Github的token，Gitee不需要额外token。
3. Compass学术方案讨论
   - Compass学术方案已出，大致方案OK，集成到Compass Lab。
      - **AP：钟峰稍后与张盛翔沟通，并提供设计方案。**
### 官网
1. 首页轮播图片展示“项目分析”、“详细化指标”、“学术研究（目前还没有该页面，待出）”三个部分，文字已更新到Issue里，可以开始进行前端修改。
    - **AP：赖兴友尽快修改前端，周冉协助确认文字。**
2. 首页展示的Compass架构图需要英文文案。
    - **AP：王晔晖提供文案。**
3. 导航栏更新方案之前已讨论过，需尽快开始前端修改。
    - **AP：赖兴友尽快修改前端。**
4. 动态页英文标题精简版本已提交前端，需尽快修改。
    - **AP：赖兴友尽快修改前端。**
5. 文档页大纲OK，需转成markdown格式上传仓库，并开始分工协作撰写具体内容。
    - **AP：龙文选转换markdown文档，周冉协助上传仓库，下周开会大家讨论分工，再开始协同写作。**
### 前后端
1. 用户提交完项目后以及在账号设置页面中，添加“我的订阅”页面链接。未合并的PR可添加提示，告知用户什么时候可以在“我的订阅”页面看到提交的项目。已创建issue，需修改前后端。
   - **AP：覃华添提供后端数据、黄超群更新前端。**
2. 详细化指标页面前端已完成，已上灰度测试。
3. 详细化指标信息访问权限已更改。
4. 尽快执行仓库的多标签分类。
    - **AP：覃华添尽快输出数据结构方案。**
5. 目前的项目技术分类存档在仓库中的collection文档中，可通过PR申请添加其他分类。
### 运营
1. 社区例会以后提前在[飞书文档](https://giteecode.feishu.cn/docx/J968dXuvBoMSSoxLRa6cBDbYn6g?from=from_copylink)中填写议题。
    - **AP：大家各自填写。**
2. 12月13日社区Board会议：议题需尽快收集、邀请信尽快发送。
    - **AP：王晔晖尽快提供议题，周冉给各位Board发邀请信。**
3. 12月13日社区年会：议题收集、嘉宾邀约基本完成，听众邀约待开始。
    - **AP：王晔晖、周冉完善嘉宾、议题信息，尽快开始听众邀约。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-14开源指南针会议纪要
## 回放
https://meeting.tencent.com/v2/cloud-record/share?id=5b082afe-9400-4f45-95fa-0c5aac830c34&from=3&is-single=true
## 时间
北京时间2023年11月14日下午14:15~15:25
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[邱睿桥](https://dune0310421.github.io/)、[齐国强](https://github.com/guoqiangqi)、止戈
## 主题——Compass前后端开发、官网及运营事项进展
### 官网
1. Compass评估体系架构图已重构。
    - **AP：钟峰根据重构图进行官网展示设计。**
2. 首页顶部设计更新：目前更新方案总体可以，图片部分轮播展示Compass的不同功能。
    - **AP：钟峰更新设计方案。**
3. 首页顶部文案根据展示方案进行了调整。
    - **AP：周冉确认调整后的文案。**
### 运营
1. Gitee指数替换、学术落地Compass事宜待推进。
    - **AP：张盛翔尽快推进相关事宜。**
2. 近期一些高校表达了与Compass合作的兴趣，待后续推进。
    - **AP：张盛翔跟进相关合作。**
3. 12月13日年会上将公布Compass新进展：Gitee上线Compass、详细化指标上线、Compass学术界面上线。
### 前后端
1. 详细化指标前端快完成，待上灰度测试及调整；表格需要支持下载。
    - **AP：赖兴友添加表格下载选项、尽快完成剩余前端工作，并部署到测试服务器。**
    - **AP：钟峰对图标、颜色、展示形式等给出调整方案，赖兴友根据方案进行修改。**
    - **AP：王晔晖提供各个指标及描述文字的调整方案。**
2. 详细化指标信息获取权限需根据相应社区角色进行区分，普通用户登录后默认看到1个月内的数据，其他用户可额外申请。
    - **AP：钟峰提供申请权限的界面设计方案；王晔晖组织Board对详细化指标信息使用权限问题进行讨论和决策。**
3. 收录的开源项目仓库新建多标签分类：仓库原有标签可做分类参考，建议直接抓取。
    - **AP：覃华添输出数据结构和方案，张盛翔推进后续工作。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-09开源指南针会议纪要
## 时间
北京时间2023年11月09日下午14:15~14:20
## 与会人
[王晔晖](https://github.com/eyehwan)、[龙文选](https://github.com/hncslwx)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[邱睿桥](https://dune0310421.github.io/)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展
### 官网
1. Compass架构图及文档进行中。
    - **AP：王晔晖尽快完成，下周请钟峰设计展示方式。**
### 前后端
1. 详细化指标前端进行中。
    - **AP：兴友尽快完成。**
### 运营
1. 12月13号年会前推进Gitee指数替换及学术研究落地Compass事宜。  
    - **AP：王晔晖与张盛翔尽快推进。**
2. 12月13号年会邀请函设计、嘉宾邀约、议题整理、会务安排等事宜进行中。
    - **AP：周冉推进相关事宜，钟峰提供设计支持。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-07开源指南针会议纪要
## 时间
北京时间2023年11月07日下午14:15~14:20
## 与会人
[王晔晖](https://github.com/eyehwan)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展
### 官网 & 前后端
1. sitemap已更新，前端需要把关键词和报告里的仓库信息提取出来。文档加sitemap插件自动生成sitemap信息。
    - **AP：兴友与华添沟通，进行前端支持。**
### 运营
1. 12月13日在北京召开Compass年会，具体安排周四再讨论。
    - **AP：周冉提前准备相关讨论事项。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-11-02开源指南针会议纪要
## 时间
北京时间2023年11月02日下午14:15~14:45
## 与会人
[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)、刘天栋-开源社
## 主题——Compass前后端开发、官网及运营事项进展
### 官网
1. 导航栏调整方案完成，前端可进行修改。
     - **AP：兴友修改前端。**
2. 首页调整方案已出，暂时按方案进行，细节再讨论。
     - **AP：兴友修改前端，周冉与峰哥再讨论细节修改。**
### 前后端
1. sitemap信息更新需尽快推进。
     - **AP：华添尽快修改。**
2. 对比分析页面弹窗前端已修改。
### 运营
1. 12月13日上午在北大燕园开Board会议。
     - **AP：周冉通知各位Board，收集议题，尽快发会议邀请。**
2. 12月13日下午在北大旁边组织Compass社区迷你峰会，面向高校、开源项目、OSPOs、开发者、企业等，围绕Compass Lab，讨论学术研究成果落地Compass及Compass在开源评估领域的新进展等。
     - **AP：周冉尽快出策划方案。**
3. 指标模型接口token，下周可以给到50多个。
4. 下周出gitee指数替换方案。
5. 开源社年报数据篇希望与OSS Compass合作，展现国内外开源项目社区发展状况。
     - **AP：盛翔、晔晖与开源社再讨论。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-10-31开源指南针会议纪要
## 时间
北京时间2023年10月31日下午14:15~15:00
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展
### 官网
1. 官网首页修改Issue已创建，设计进行中。
     - **AP：峰哥尽快出设计稿，周冉补充所需内容。**
2. 文档页面补充内容，确认是否需要重新设计布局。
     - **AP：周冉跟龙老师确认内容补充任务，请龙老师重新梳理用户文档；周冉跟峰哥确认是否需要重新设计该页面。**
3. 动态页面左侧已加分割线、时间戳，英文标题需要精简及调整大小写。
    - **AP：周冉精简英文标题，确认长度与大小写，兴友修改前端。**
4. 对比分析页弹窗展示，重新调整。
    - **AP：兴友调整前端。**
### 前后端
1. 详细化指标的接口已完成，前端尽快完成。
    - **AP：兴友这周完成前端。**
2. 其他企业和学术机构访问Compass的需求：目前基本都是公开GraphQL接口，可以对外提供。
    - **AP：兴友提供GraphQL接口给龙老师，龙老师测试使用。**
### 运营
1. 12月中旬CHAOSS和Compass迷你峰会及Compass社区Board会议策划。
    - **AP：周冉跟各位Board确认时间，联系场地，确定峰会主题、参与嘉宾、活动流程、活动礼品、晚宴等具体方案。**
2. 活动礼品定制：连帽衫或其他，少而精。
    - **AP：周冉确定预算及方案，提前安排制作。**
3. 社区年度总结小册子：确认内容及设计，尽快推进。
    - **AP：峰哥确认设计方案及设计周期，周冉确认具体内容、提前安排制作。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-10-26开源指南针会议纪要
## 时间
北京时间2023年10月26日下午14:15~15:05
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展
### 前端
暂无更新。
### 后端
1. 详细化指标开发完成，目前在测试。
    - **AP：华添提供接口，尽量下周完成。**
2. 南大、北大合作token需要扩容。
    - **AP：盛翔尽快处理。**
### 运营
1. 学术成果落地Compass的方案设计：
    - **AP：晔晖与盛翔尽快确定方案。**
### 官网
1. 官网sitemap信息需要更新，以便搜索引擎抓取官网内容。
    - **AP：华添、升保进行后端支持，兴友、超群提供前端支持。**
2. 官网首页修改建议：
   - slogan部分的文字按照“我是谁+为什么选择我们”的逻辑重新梳理，现在图标改为Compass logo演绎的动画和报告页图表美化版。
     - **AP：周冉创建Issue，添加梳理好的文字，升保提供图表，峰哥重新设计图标、图像和展示方式。**
   - slogan和图表下方，展示案例，包括与CHAOSS、南大、北大、部分社区等的合作内容，显示Compass的价值。
     - **AP：周冉梳理明确要展示的内容，创建Issue，峰哥设计展示方式。**
   - 导航栏加“文档”一栏，把部署文档、用户文档等内容放在这个页面。
     - **AP：周冉创建Issue，晔晖、龙老师进行文档梳理以及内容补充。**
   - 导航栏名称和顺序调整：（中文）文档>项目>Compass实验室>加入社区>动态>关于，（英文）Documentation>Projects>Compass Lab>Join Community>News>About
     - **AP：周冉创建Issue。**
   - 删除现有开源评估体系全景图，提供最新Compass全景图。
     - **AP：周冉创建Issue，晔晖提供全景图。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-10-24开源指南针会议纪要
## 时间
北京时间2023年10月24日下午14:15~14:20
## 与会人
[王晔晖](https://github.com/eyehwan)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)
## 主题——Compass前后端开发、官网及运营事项进展
### 前端
暂无更新。
### 后端
详细化指标后端开发进行中，github的已完成，gitee的本周四完成。
### 运营
1. Compass替换Gitee指数事宜：
    - **AP：晔晖与盛翔再单独讨论进展。**
2. 学术成果落地Compass事宜：
    - **AP：晔晖与盛翔尽快讨论具体方案。**
### 官网
1. 官网文字修改：
    - **AP：周冉尽快提供文字调整方案。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1
 
# 2023-10-19开源指南针会议纪要
## 时间
北京时间2023年10月19日下午14:15~14:52
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)
## 主题——Compass前后端开发、官网及运营事项讨论
### 运营
1. Compass替换Gitee指数年底前完成。
    - **AP：盛翔跟进此事，月底前提供反馈，看哪些仓库优先级高，可以先进行替换。**
2. 学术成果落地Compass：暂时先放在Compass Lab。
    - **AP：晔晖、盛翔尽快讨论出具体方案。**
### 官网
1. 新闻动态展示方案：先加时间戳和分割线，后续再调整为卡片形式。
    - **AP：兴友先按目前要求调整，后续根据需要再演进。**
2. 导航菜单名称优化，需要让用户一目了然知道各个菜单下面是什么内容。
    - **AP：周冉提供优化的名称，大家再讨论，确定后再优化。**
3. 二级分类页面对比分析后返回：以弹窗的形式新开一个页面。
    - **AP：兴友在前端进行修改。**
4. 主页导航增加“文档”栏，用户文档放在此页面，并完善这部分内容，
    - **AP：晔晖完善用户文档，系统介绍Compass的开源评估体系与SaaS服务。**
5. 梳理跟开源评估相关的搜索关键词或者句子，在官网首页文字中加入这些词，并根据这些短语、句子撰写相关文档放在“动态”页，引导搜索引擎的流量至官网。
   - **AP：盛翔查找相关关键词和句子发给周冉，周冉梳理后请晔晖、汪亮老师等撰写相关文章。**
6. 官网首页：增加轮播动态效果，吸引眼球；修改文字内容，清晰展示Compass的价值和功能。
   - **AP：峰哥设计动效，周冉提供相关文字，晔晖审核。**
### 后端
1. 学术成果落地Compass时，如果论文中指标与Compass现有指标不一致的情况怎么处理：可以在Compass中增加没有的指标或者另做说明。
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-10-17开源指南针会议纪要
## 时间
北京时间2023年10月17日下午14:15~14:45
## 与会人
[王晔晖](https://github.com/eyehwan)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[黄超群](https://github.com/nanzm)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[齐国强](https://github.com/guoqiangqi)、[邱睿桥](https://dune0310421.github.io/)
## 主题——Compass前后端开发、官网及运营事项讨论
### 前后端
1. 详细化指标前后端开发继续进行。
2. Compass部署文档已完成测试，只剩邮箱邀请部分有问题，待修复后会在仓库公开该文档并交付给CHAOSS进行部署。
    - **AP：升保尽量今天完成该文档的测试，并上传docs仓库。**
3. 图表下载与分享自定义时间前后端完成，已上线。
### 官网
1. 首页Compass功能全景图设计，需要文字说明。
    - **AP：周冉提供文字说明，晔晖进行审核后交给钟峰设计。**
2. 动态页更新的内容需要设计展示方式，如分界线、标题加时间戳等。
    - **AP：钟峰提供展示方式，前端根据更新的设计进行优化。**
3. 基于Compass的学术研究成果如何展示在Compass社区：是跟Compass Lab合并，还是单独开辟一个Compass Research页面，钟峰建议前期内容不多的情况下先跟Lab合并。
   - **AP：会后晔晖与盛翔再讨论，钟峰根据讨论结果设计展示方式。**
### 运营
1. CHAOSS正在准备部署Compass的SaaS服务，投资安排已到位。
2. 工信部电子一所、深圳工信局等机构组织深圳1024程序员节，将联合Compass发布中国开源评估指数。
3. 欧洲开源项目Open Review Toolkit想要集成Compass，希望改进Compass官网及SaaS服务的易用性。
    - **AP：周冉尽快提交改进方案给晔晖。**
4. Gitee指数替换，待详细化指标页面完成后进行。
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-10-12开源指南针会议纪要
## 时间
北京时间2023年10月12日下午14:15~14:26
## 与会人
[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[杨文昊](https://yangwenhao3906.github.io/)
## 主题——Compass前后端开发及运营事项讨论
### 后端
1. 详细化指标页面后端开发、接口创建进行中，PR、Issue列表已经上灰度，预计全部后端开发下周完成。
   - **AP：升保尽快完成后端指标开发，华添尽快完成接口创建。**
2. 技术分类已有300多个，部分新分类待审核。
   - **AP：王晔晖尽快审核。**
### 前端
1. 图表下载与分享前端已完成，该功能已经上线。
2. 详细化指标静态页面开发进行中，等后端开发完成后大约一周完成。
   - **AP：兴友根据后端进度尽快完成前端开发。**
### 运营
1. Compass部署文档架构图已完成，英文文档已写完，在复核阶段。
   - **AP：升保尽快完成复核。**
2. 针对详细指标页面呈现的客观数据给与特定社区改进建议一事需要尽快推进，以便在年底峰会上面呈现Compass的价值。
   - **AP：文昊尽快做洞察，尽快分享相关学术研究成果，后续根据研究成果再讨论技术落地方案。周冉与王晔晖确认目标社区。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-09-21开源指南针会议纪要
## 时间
北京时间2023年9月21日下午14:15~14:24
## 与会人
[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[黄超群](https://github.com/nanzm)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)
## 主题——Compass前后端开发及运营事项讨论
### 后端
1. 因gitee海外带宽已满导致官网oss-compasss.org访问速度慢, 现已从华为云加了一个10M的带宽作为海外入口。
2. 报告页的概览图表增加了下载与分享功能。
3. 详细化指标：
      - Issue、PR接口已加。
      - GitHub贡献者列表已完成，Gitee的进行中。
### 前端
1. 官网动态页面增加了一些功能更新及新闻。
2. 项目二级分类标签已完成添加。
3. 图表下载与分享功能前端正在进行，明天完成后上灰度。
     - **AP：兴友明天完成后，华添上灰度测试。**
### 运营
整理公众号已发布的中英文文案给前端上传官网，进行中。
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-09-12开源指南针会议纪要
## 回放
https://meeting.tencent.com/user-center/shared-record-info?id=e04f3283-e507-4ad5-9464-89328ea3933d&from=7&reload=1
## 时间
北京时间2023年9月12日下午14:15~15:09
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[钟峰](https://github.com/poorfish)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[周冉](https://github.com/JuliaZhou2022)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、汪亮、符芬菊、Zline、中国电信陈泳、聂黎明
## 主题——Compass前后端开发及运营事项讨论
### 运营
1. 9月最后两周例会改为每周一次，周四进行。
   - **AP：周冉更新微信群、Slack、官网通知。**
2. 需要设计Compass服务全景图，在9月中旬欧洲开源峰会上晖哥进行展示。
   - **AP：峰哥设计，周冉跟进进展，9月21日前完成。**
3. Lab详细指标页面的名称需要好好定义，建议加入营销口号语，如“90天改变社区”。
   - **AP：王晔晖与张盛翔再讨论。**
4. Lab详细指标页面呈现的客观数据要如何使用，建议以文章、视频等运营的方式呈现，可针对特定社区提供咨询服务、给与改进建议。
   - **AP：（1）周冉与王晔晖选择5个社区策划改进建议讨论活动，可提前发文征求意见。（2）文昊协助汪亮老师从文献层面给与改进建议。（3）文昊从软工层面或者github action等方面给与改进所需工具（precommit）的自动化部署建议，王晔晖辅助跟进。**
5. 华为HC大会上华为将联合艾瑞咨询发布中国基础软件白皮书，数据来自Compass，目前升保和兴友在提供数据支持。
   - **AP：升保、兴友下周完成这部分工作。**
### 前端
1. 详细指标页面设计已更新，单仓项目基本逻辑OK，多仓社区的详细化指标需要与社区管理相结合，后续再逐步完善。
   - **AP：兴友、升保、华添开始前后端开发。9月21日前完成。**
2. 详细化指标页建议显示标准值，对于低于标准的数据给与标记。
   - **AP：峰哥增加这部分设计方案，升保提供标准值，兴友进行前端部署。9月21日前完成。后续升保定期收集低于标准值的数据给晖哥。**
3. 详细化指标页每个模型建议添加讨论区，待后续时间充裕再进行相关工作。
4. 项目二级分类设计已完成，前端开发待开始。
   - **AP：兴友进行相关开发工作，本周完成。**
5. 探索页面已支持直接跳转至仓库，点击项目下方Github或Gitee图标即可跳转。
   - **AP：周冉通知提这个需求的用户。**
### 后端
1. 前后端国际化文件已经更新到单独仓。后续相关文档都放在这个仓库。
2. 图表嵌入后端参数已经完成，前端待开始。
   - **AP：峰哥设计界面，兴友做前端开发。尽快完成。**
3. 部分社区得分有问题，后端已修改，前端待更新。
   - **AP：兴友配合修改前端参数。尽快完成。**
4. Compass与LLMs：睿桥在调研怎样在开源社区使用LLMs。
   - **AP：睿桥与晖哥保持关于这个话题的讨论。**
5. Compass能力私有化部署探讨。
   - **AP：王晔晖与中国电信陈泳会后讨论。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-09-07开源指南针会议纪要
## 时间
北京时间2023年9月7日下午14:15~15:05
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[齐国强](https://github.com/guoqiangqi)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass Lab前后端开发进展、官网设计及运营事项讨论
### Lab前后端
1. 第一批获取事件的token测试正常。**AP：盛翔继续提供其他token给华添，优先处理详细化指标对应的token。**
2. 详细化指标已经梳理完成。
3. 详细化指标呈现方式：在报告页显示入口，点击后进入一个页面统一呈现社区变化趋势相关的所有指标的变化细节，而不是每个指标分别呈现细节。**AP：峰哥调整设计思路，下次会议再次呈现。**
4. 图表嵌入功能已完成，需要提供入口给用户，允许用户选择格式。**AP：峰哥设计入口形式，可以加水印，盛翔、华添讨论对部分参数的显示优化。**
### 官网
1. 社区头像自定义相关的前后端工作已完成，盛翔建议：外围框线颜色再浅一些，网速慢的时候，GitHub、Gitee图标与社区头像不同步显示，这些后续可再优化。
2. 探索页面项目分类需要整理。**AP：盛翔建Issue，优化探索页面的二级分类。**
### 运营事项
1. 晔晖最近在探索Compass发展大模型评估业务的途径，已进行了一些访谈，收集了一些需求。**AP：晔晖跟盛翔分享访谈内容。**
2. 晔晖9月中旬会去欧洲开源峰会上讲Compass的价值，建议加上社区洞察报告。**AP：周冉跟晔晖一起完成社区洞察内容。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-31开源指南针会议纪要
## 时间
北京时间2023年8月31日下午14:15~14:54
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[龙文选](https://github.com/hncslwx)、[钟峰](https://github.com/poorfish)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass Lab前后端开发进展、官网设计及运营事项讨论
### 官网
1. 主页周活跃榜里的项目没有显示社区头像，建议创建社区时默认显示第一个仓库，用户可以选其他仓库的头像。目前已提交的几十个社区建议进行手动修改头像。**AP：超群提PR，兴友、超群、晖哥、盛翔一起手动修改。**
2. 官网需要添加龙文选老师及其同事的信息。**AP：龙老师尽快发个人介绍给周冉，超群更新到官网。**
3. 报告页的关键字需要能搜索到，可帮助引流。后续有空再做。 
### Lab前后端
1. 获取事件的token已更新一部分，需要测试更新的token。**AP：华添进行测试。**
2. 图表嵌入需要后端重构完成后才能进行。
3. Lab文字国际化的bug修复中。
4. 报告页显示指标明细事宜需要在9月21日前完成初版。**AP：升保下周中把细化指标捋清楚，峰哥再设计指标明细页面。**
5. 数据集分类错误还没完全修复，目前删除旧有信息有延迟，满足时间期限后才能真正删除，建议手动修改。**AP：需要修改时华添提PR进行手动修改。**
6. 需要管理好Compass后端内部数据看板。**AP：华添维护。**
### 运营
1. 华为请艾瑞咨询在做中国基础软件白皮书，数据来自Compass，目前确认按协作开发指数和活跃度两个维度进行梳理。**AP：升保与华添按照两个维度输出数据，这一部分数据先不呈现，晖哥与相关社区沟通后再呈现并进行数据整理，周冉与艾瑞咨询对接相关宣传工作。**
2. 周冉已完成Lab英文介绍发给CHAOSS，目前CHAOSS已修改完，即将发布在CHAOSS的Blog和Twitter上。Lab中文介绍这周五发微信公众号。**AP：周冉发布中文版到微信公众号，转发CHAOSS的Twitter英文版。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-29开源指南针会议纪要
## 时间
北京时间2023年8月29日下午14:15~14:51
## 与会人
[王晔晖](https://github.com/eyehwan)、[钟峰](https://github.com/poorfish)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[齐国强](https://github.com/guoqiangqi)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass Lab前后端开发进展、官网设计讨论
### 官网
1. 热门项目区域Gitee图标已经支持，Github图标需要继续添加。**AP：华添与超群添加。**
2. 周活跃榜单显示形式已经设计好。**AP：华添与超群按设计进行开发。**
3. 官网首页开源生态评估体系图可放在评估模型页面，首页可考虑重新设计图片展示Compass能够提供的SaaS服务内容。**AP：超群先把开源生态评估体系图移到评估模型页面，峰哥后续重新设计。**
### Lab前后端
1. 优化了一些指标和指标分析时间，修复了一些界面显示bug。
2. 重构报告页接口代码后，再支持图表嵌入。**AP：华添尽快完成重构，再进行图表嵌入支持工作。**
3. 每个指标图表后续要展示详细注解，比如贡献者数量指标可展示具体哪些贡献值、组织信息等等，需要在Gitee指数替换工作开始之前进行展示。**AP：峰哥考虑展示形式。**
4. 报告页数据集公开，需要放在一个仓库，通过API接入。**AP：华添进行相关操作。**
5. Compass Lab已发布，近期需要收集新建模型数量、新建看板数量、用户数量等数据进行观测。**AP：华添进行收集。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-24开源指南针会议纪要
## 时间
北京时间2023年8月24日下午14:15~14:35
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass Lab前后端开发进展、官网设计及运营事件讨论
### Lab前后端
1. Lab前端基本OK，在修复数据集错乱等Bug，登录错误需要修复。**AP：华添修复。**
2. Lab后端功能基本OK，在做旧模型重构以及优化指标分析时间。
3. 重新定义token进行事件收集也在进行中。
4. Lab前端内容国际化进行中。
### 官网设计
1. 官网热门项目区域不支持项目及Gitee或Github图标显示，需要修复。**AP：兴友与华添沟通后处理。**
2. 官网最近热点区域需要手动部署内容，建议后台放在仓库，自动部署。**AP：兴友与华添确认。**
3. 官网动态页面尽快补充内容。**AP：周冉尽快提供相关内容给前端。**
4. 官网腾讯会议链接下面加仓库会议纪要链接。**AP：兴友添加。**
### 运营
1. 8月23号下午社区Board第一次会议召开，各位Board认可Compass Lab的价值，并对它的发展方向提出了很多建议。**AP：周冉尽快发出会议纪要，大家一起看如何落地相关建议。**
2. 8月23号晚上社区举行了直播活动，进行了Compass Lab演示，后续要看如何推广Lab，促进更多开源社区使用。**AP：周冉尽快补充运营规划相关内容，与相关Board一起讨论推广计划。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-22开源指南针会议纪要
## 时间
北京时间2023年8月22日下午14:15~15:00
## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[龙文选](https://github.com/hncslwx)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass Lab前后端开发进展、官网设计、运营事项讨论
### 官网
1. 热门领域和新闻动态区域今天调整好，部署一版给大家看。**AP：兴友部署、周冉提供新闻动态内容。**
2. 热门项目从二级分类里面选择项目，LLM项目需要加到一级分类中。**AP：升保更新一级分类，兴友更新前端内容。**
### Lab前后端
1. 我的模型页面，“模型默认版本”暂时调整为“模型默认展示版本”，后续再做设计调整。**AP:超群修改文案。**
2. 报告页支持截图，可将截图添加至评论中。
3. 系统默认算法区域图片和文案需更新。**AP：兴友尽快上传更清晰的算法图片和相关文案。**
4. 数据集有重复。**AP：超群跟华添确认。**
5. 数据集与指标名称需要调整大小写。**AP：超群调整。**
6. 权重调整目前限制为只能向右调，保留小数点后两位；阈值后显示的限定范围目前是动态的，需要调整为固定值。**AP：超群修复bug。**
7. 评论区右上角的超链接点击没有任何反应且与第二个#号有重复、默认排序应该显示最新的评论等小问题后续修改。
9. 名称一行显示不完可按两行，后续考虑取名长度限制。
10. 今天完成Lab前后端修改后再上灰度测试。**AP：前后端协同。**
### 运营
Compass Lab正式发布后需要有介绍文案发布。**AP：周冉尽快完成文案并发布。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-17开源指南针会议纪要
## 时间
北京时间2023年8月17日下午14:15~14:45
## 与会人
[王晔晖](https://github.com/eyehwan)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[齐国强](https://github.com/guoqiangqi)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)
## 主题——Compass Lab前后端开发进展、官网设计、运营事项讨论
### Lab前端
1. Lab本周Demo基本逻辑流畅，下周三正式发布，创建模型失败问题需要解决。**AP：超群查看原因并调整。**
2. 我的模型页面，已显示上次分析的时间，每次触发分析，状态都会更新，正在分析时，触发分析按钮不可点击。
3. 打开Lab页面，会显示某个模型下可以公开显示的项目，同时可以筛选数据集，点击项目可进入项目Dashboard页面。
4. Lab页面公开的项目需要显示版本，允许用户自由选择公开哪一个。**AP：峰哥更新界面设计。**
5. Lab页面Discuss按钮直接链接到页面显示的第一个项目的评论区。
6. 大语言模型二级分类还没有提交到总目录中。**AP：兴友跟华添核对。**
### Lab后端
1. 项目Dashboard页面每个指标下面的参考性指标先隐藏，后续再做拆分后展示，且命名需要修改。**AP：升保23号之前先隐藏未拆分的参考性指标，并尽量在Lab上多显示一些细化指标。**
2. Lab后端修Bug中，模型重构工作暂停，等指标继续原子化后再继续进行。
### 官网
热门领域设计已完成。**AP：下周三兴友更新前端。**
### 运营事项
1. 8月23号直播物料已出完。**AP：周冉跟峰哥对接。**
2. Compass定制T恤稍后发给大家。**AP：周冉处理此事。**
## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-15开源指南针会议纪要

## 时间
北京时间2023年8月15日下午14:15~14:50

## 与会人
[王晔晖](https://github.com/eyehwan)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[齐国强](https://github.com/guoqiangqi)、[龙文选](https://github.com/hncslwx)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)

## 主题——Compass Lab前后端开发进展、官网设计、运营事项讨论

### Lab前端
1. 我的模型页面大致内容都已OK，部分内容及功能还要继续添加。**AP：兴友尽快在创建模型页面底部加使用条款。**
2. 触发分析选项应显示上次分析完的时间戳，建议放在按钮下方，**AP：峰哥调整界面设计**。
3. Lab主界面还在联调，今天可以部署，整体工作本周内可完成。以英文版为主，中文版进度稍慢。**AP：超群部署以后告知大家试用。**
4. 用户使用条款里面的联系邮箱需要确认后更新，**AP：周冉跟盛翔确认**。

### Lab后端
1. 图表默认提供最近半年的数据，部分数据集内容不完善，用户如果选用可能跑不出来结果。
2. 目前默认任何人都可以试用Lab，后面再调整权限。
3. 新建一个模型触发分析限制次数为10次，已限制创建模型个数。

### 官网
热门领域设计更新，**AP：峰哥今天更新设计，兴友把国强把筛选出来的项目及二级分类放上去**。

### 运营
23号直播海报设计已大致完成，**AP：峰哥稍后根据调整意见再修改主题，并添加直播二维码，周冉提供调整意见和二维码给峰哥**。

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-10开源指南针会议纪要

## 时间
北京时间2023年8月10日下午14:15~14:57

## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[齐国强](https://github.com/guoqiangqi)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)

## 主题——Compass Lab前后端开发进展、官网设计讨论

### Lab前端
1. Lab还在联调评论区，**AP：华添8月15号需要完成所有联调工作，保证Lab能够demo**。
2. 邮件邀请加入Lab，点确认后会跳出签署条款页面，然后会进入我的模型页面，**AP：周冉下周二前确认英文用户条款OK，届时兴友上线该条款**。
3. 评论区缩进只有两个层级。
4. Lab图表部分，**AP：需要升保、华添这边给接口**。

### Lab后端
1. 指标index一样的进行了修改，加了前缀。
2. 改指标index后所有项目需要重新用模型跑一遍，以便重新计算中位数等其他数据，**AP：华添先完成目前工作，等正式上线后再重新跑数据**。
3. 组织活跃度字段与层级都已修改，数据结构发生了改变，也需要重新获取数据，**AP：升保与华添对一下**。
4. 指标拆分后代码基本没问题，可以合并，**AP：晖哥合并代码**。

### 官网
1.  Lab里面的用户条款会在新建模型和邮件邀请加入模型协作时以勾选的形式显示。
2.  首页热门领域这一块内容要换掉，可展示人工挑选出来的热门领域和相关项目，可选择大语言模型工具类、框架类等相关项目，后续要支持自动更改，**AP：峰哥重新设计界面展示效果**。

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-08开源指南针会议纪要

## 时间
北京时间2023年8月8日下午14:15~14:43

## 与会人
[王晔晖](https://github.com/eyehwan)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[齐国强](https://github.com/guoqiangqi)、[杨文昊](https://yangwenhao3906.github.io/)、[邱睿桥](https://dune0310421.github.io/)、[周冉](https://github.com/JuliaZhou2022)

## 主题——Compass Lab前后端开发进展、官网设计、运营事项讨论

### 官网
1. 更新官网社区成员信息，添加文昊、睿桥，**AP：超群操作**。
2. 联系我们页面错误已修复
3. 动态一栏下面需要把微信公众号发布的内容更新上去，**AP：兴友操作**。

### Lab前端
1. 我的模型页面这周完成，数据集不需要限定行业，权重没有默认值，阈值有默认值带说明，**AP：超群创建任务尽快完成修改和遗留任务，下周二demo**。
2. Lab页面显示创建我的模型入口，**AP：超群跟峰哥对一下前端设计**。

### Lab后端
1. 明天指标拆分任务可全部完成
2. 合规审核差不多对完，等指标拆完后调模型页面，**AP：华添尽快开始模型页面联调工作**。

### 运营
Lab需要有用户使用条款给用户在使用Lab前进行签署，**AP：周冉准备这个条款，下周完成，可问盛翔要模板，请峰哥设计这个条款的展示方式**。

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-03开源指南针会议纪要

## 时间
北京时间2023年8月3日下午14:15~15:00

## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[齐国强](https://github.com/guoqiangqi)、杨文昊、邱睿桥、[周冉](https://github.com/JuliaZhou2022)

## 主题——Compass Lab前后端开发进展、官网设计、运营事项讨论

### 官网
1. 首页周榜中项目头像右下角显示Gitee、Github图标。
2. 项目二级分类标签除了在首页展示，报告页、选择数据集等页面也会进行展示，多个分类的情况只显示最主要分类，其余以数字展示，**AP：峰哥创建task，兴友进行相关操作**。
3. 提交社区时默认提取第一个仓库的头像，用户可自定义头像，后期需要改头像时提PR进行，修改头像的流程需要再讨论，**AP：晖哥、盛翔讨论修改头像的流程，峰哥创建task**。
4. 报告页的得分分布雷达图设计方案Ok，属于Gitee指数替换工作的一部分，等Lab的工作结束后，再开始进行。

### Lab前端
1. Dashboard有图表曲线断层，**AP：升保修复**。
2. 部分组织不在库中，部分指标不能显示分析结果，需要手动输入。
3. Lab前端开发进行中。
4. 嵌入图表前端工作进行中，下周完成。

## Lab后端
1. 图片存储基本完成，内容审核待开始。
2. 管理后台：是否需要设置超级管理员，**AP：晖哥与盛翔讨论**。
3. 部分指标已拆完，8月8号左右完成所有指标可以拆分，**AP：升保与文昊、睿桥继续分工拆分其他指标**。

### 运营
1. 晖哥在写指标模型解读的文章，目前已完成中英文各一篇。
2. 之前讨论的官网需要根据运营需求调整的事项都已创建task，分配给相关人员。

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-08-01开源指南针会议纪要

## 时间
北京时间2023年8月1日下午14:15~15:15

## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[龙文选](https://github.com/hncslwx)、[齐国强](https://github.com/guoqiangqi)、杨文昊、邱睿桥、[周冉](https://github.com/JuliaZhou2022)

## 主题——Compass Lab前后端设计进展、官网设计讨论

### 官网
1. 首页热门区域调整为项目分类及推荐项目，直接从项目报告页获取相关分类和项目数据
2. 首页单仓提交项目周活跃榜显示项目图标，要显示Github或Gitee图标，**AP：峰哥更新设计**
3. 首页社区提交项目周活跃榜显示用户提交社区时自定义的组织头像，**AP：超群创建task，明确用户自定义头像的规则，峰哥进行相应界面设计**。
4. 首页周榜上面的项目显示二级分类，这些分类可能有多个，按字母排序，**AP：峰哥更新设计**
5. 社区动态展示
   - 目前设计为三块区域排列。
   - 在首页底部，放在Compass生态系统图前面。
   - 左侧两块需要做可以更改的适配设计，根据需要可调整为一块内容。
   - 右边第三块内容为日历日程，需要提供订阅服务，允许社区成员把日程加到自己的日历中，建议中英文网站使用统一设计，**AP：兴友操作，峰哥调整设计**
6. 首页导航条加动态一栏，直接把“社区”里的“博客”调到上面去，改为动态，**AP：周冉创建任务，超群修改后端，把最近文章都放上去**。

### Lab前端
前端进行中，图表需要指标拆完后才能进行，其他这周可完成。

### Lab后端
1. 后端第一版接口基本OK，报告页评论功能以图片和纯文本分开的形式展示，图片数量限制为5张，**AP：峰哥考虑多图设计**
2. 内容合规，**AP：华添根据国内外要求进行相关操作**
3. 指标拆分进行中，Lab/Hub要加添加其他指标，**AP：华添提前配置采集器，采集新指标要用到的底层数据**
4. 软件项目分类调整：做两级分类，操作系统分类已做完，支撑软件分类正在做，应用软件等其他软件有待细分，分类颗粒度尽量小，**AP：龙老师把分类图放到project information里面，保持更新**

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-07-27开源指南针会议纪要

## 时间
北京时间2023年7月27日下午14:15~14:33

## 与会人
[王晔晖](https://github.com/eyehwan)、[张盛翔](https://github.com/normal-coder)、[黄超群](https://github.com/nanzm)、[赖兴友](https://github.com/coder-sett)、[覃华添](https://github.com/EdmondFrank)、[李升保](https://github.com/lishengbao)、[钟峰](https://github.com/poorfish)、[龙文选](https://github.com/hncslwx)、[齐国强](https://github.com/guoqiangqi)、杨文昊、邱睿桥、[周冉](https://github.com/JuliaZhou2022)

## 主题——Compass Lab前后端设计进展、官网设计及运营事项讨论

### 前端
1. 官网链接社交媒体（微信公众号、Twitter）入口需要提供，**AP：峰哥在Project里创建Task**  
2. Lab静态页面进行中，图表嵌入任务（图表作为前端接口在后端调用）进行中，**AP：超群与后端同步在两周内（8月15号前）完成**
### 后端
1. 指标拆分方案已提交，两周内可以完成拆分，**AP：升保按照方案拆一两个指标出来，请睿桥和华添一起看看**
2. 开发者贡献价值分析
   - 如何识别社区贡献者的价值，**AP：文昊分享相关学术研究，在群里与大家讨论**
3. 后端已重构，前端后续只需要通过接口调用后端
4. Lab接口两周内可完成。
### 运营
1. 会议纪要与会人加GithubID链接，**AP：周冉添加**
2. 会议纪要链接加到官网上，**AP：前端实现**

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-07-25开源指南针会议纪要

## 时间
北京时间2023年7月25日下午14:15~15:00

## 与会人
王晔晖、黄超群、赖兴友、覃华添、李升保、钟峰、龙文选、齐国强、杨文昊、邱睿桥、周冉

## 主题——Compass Lab前后端及官网设计方案研讨及运营规划

### 前端设计
1. 我的模型页面，**AP：要设置后台管理账号，前后端协同**。
2. 官网底部右下角显示微信公众号和Twitter图标。
3. Lab的静态页面前端本周五大致完成，后端进行中。
4. 提交项目时，默认社区名称为项目名称，需要允许提交者修改名称。

### 后端
1. 模型管理，**AP：华添创建Issue**
2. 指标模型已分类，**AP：升保与华添在北大交流群讨论指标拆分方案**
3. 为了防止抓取数据保存到ES失败，抓取数据后缓存最大值目前由10000改为3000，**AP：创建Issue跟踪修改值**
4. Dashboard页单个指标图表支持以挂件的形式展示，**AP：华添与超群讨论是否单独嵌入到页面或者README.md，峰哥根据后端修改UI**

### 运营
1. 官网
   - “热门领域”模块内容需要更新：内容改为探索页面分类及二级目录中的项目，轮播，**AP：峰哥确认是否展示项目logo**
   - 社区动态：4类动态——活动、新闻、洞察报告、访谈，首页展示，与功能性动态分开展示，**AP：峰哥设计UI**
   - 博客：单独列为一个栏目，分类归档所有社区动态
2. 目前社区沟通渠道和宣传渠道可满足现阶段诉求，保持不变
   - 沟通渠道：Slack（面向国际），微信（面向国内）
   - 宣传渠道：微信公众号、Twitter

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-07-20开源指南针会议纪要

## 时间
北京时间2023年7月20日下午14:15~15:30

## 与会人
王晔晖、张盛翔、黄超群、赖兴友、覃华添、李升保、钟峰、龙文选、齐国强、杨文昊、邱睿桥、周冉

## 主题——Compass Lab前后端设计方案研讨及运营规划

### Github仓库增加Issue模板
申请Compass Lab使用权限，通过在Community project 使用Issue提交申请，**AP：峰哥设计Issue模版。** 

### Lab前端设计
1. 目前Lab下面的页面基本都已设计完。
2. 模型页面
   - 展示风格：模型页面以卡片的形式展示。
   - 新建版本与全局编辑的区别：新建版本是基本配置（所属生态维度、模型名称、行业属性、是否公开、所选数据集），右上角三个点下面的全局编辑是对版本里模型的指标、算法等具体参数进行编辑。
   - 选好的数据集以卡片形式展示，编辑数据集以弹窗形式展示。
   - 对来自于CHAOSS的指标进行标识
   - 新建模型页面Submit改为Save或Confirm，**AP：峰哥跟盛翔确认**。
   - 权重和阈值设置：表格形式展示，拖动条调节，阈值的显示需要设定默认值并加文本提示，有些是绝对值，有些是比例值，给用户权限改，指定范围是0-100或0-100%。
   - 选择算法：需要展示默认算法的公式，建议加链接展示。
   -  模型页面外框删除，用色块。
3. 新增模型协作用户
主动邀请用户或用户被动申请，账号设置使用邮箱，提示需要Compass Lab账号，并引导到社区交流并联系我们。
4. Dashboard页面
   - 首次打开默认打开讨论区，不想看可以关闭。
   - 图表——Y轴缩放功能，**AP：超群改文案，兴友后端，周冉下周发推文，峰哥删除指标下面的解释文案**。
5. Lab设计前后端同步进行，**AP：华添、兴友讨论后开始协作**。

### 后端
**AP: 华添根据前端改进意见修改后端代码；升保下周开始对现有模型指标进行拆分成指标集**。

### 运营
1. 公众号、Twiteer封图设计
   - 周冉已提需求并建任务，**AP：请钟峰这周完成**。
2. 社区动态如何在官网展示
   - **AP: 周冉梳理社区动态需要在官网上面展示的内容，下次会议前跟峰哥对一下如何展示**。 

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1

# 2023-07-18开源指南针会议纪要 

## 时间
北京时间2023年7月18日下午14:15~15:30

## 与会人
王晔晖、张盛翔、黄超群、赖兴友、覃华添、李升保、钟峰、龙文选、齐国强、杨文昊、邱睿桥、周冉

## 主题——Compass Lab前后端设计方案研讨及规划

### 后端 
1. High-Level Design用户自定义模型分析报告数据与现有报告内容分开存储。 
2. 数据集与指标都要控制用户选择数量，建议按项目选择，可设置一些分类。 
3. 用户提交没有用我们的模型跑过的数据不允许提交，必须新建项目。 
4. 版本号设计：默认时间戳或自己选择，版本号与模型映射。 
5. 评论区默认当前版本，加一个可以切换到所有版本的选项。 
6. 官网站点在国内，评论要接受敏感词扫描——**AP：王晔晖与张盛翔继续讨论怎么解决**。 
7. 用户自定义指标需要把指标模型中所有指标全部拆除来，新建指标集，把拆除来的一个个指标放进去，根据需要调用，拆出来的指标和索引需要进行mapping——**AP：李升保、华添再讨论，细化这部分操作，明确所需时间以及如何与OpenSearch交互等问题，这一块讨论全都放在北大交流群**。 
8. 业务层逻辑跟指标分拆同步进行还是等分拆后再做，等明确指标分拆过程时长后决定。 
9. 后端工作从今天开始进行。 

### 前端
1. 首页已把博客放进社区下。 
2. 社区动态如何展示——**AP：周冉规划社区运营内容，下次开会讨论如何显示**。 
3. 社区用户希望把某一个图表嵌入自己web网页，**结论：每一次跑完报告，要把报告的图表生成静态URL，进行图片嵌入，可以只提供6个月内的**。 

### Compass二级分类名称冲突
已提交的分类与已存在分类冲突时，通过PR修改已有分类名称，不断吸收合并，减少技术债务。

## 看板跟踪
https://github.com/orgs/oss-compass/projects/1
