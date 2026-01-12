## `郑惠珊`
#### 24级微电子科学与工程

*MBTI: ENFJ*
![logo](https://youke3.picui.cn/s1/2026/01/12/69647bde77076.jpg)

*图片是先去tinypng网站上压缩，压缩好保存之后，上传到图床，获得图片链接，然后贴在这里*


[仓库链接](https://github.com/zhs-bj/github_1_try)

[尝试部署的wiki链接](http://localhost/Sample%20Markdown%20document.md)但是localhost应该换设备打不开

c++代码块（拿来玩一下代码的显示部分）
```c++
void computeGravity(Body &planet, const Body &sun) {
    Vector2 r_vec = planet.pos - sun.pos;
    Fixed32 r2 = r_vec.lengthSquared();
    Fixed32 r = r2.sqrt();
    
    if (r.raw == 0) return;
    Fixed32 GM = Fixed32::fromRaw((1 << 28));
    Fixed32 forceMagnitudeTemp = GM / r2;
    Fixed32 forceMagnitude = forceMagnitudeTemp / r;
    Vector2 forceDir = {Fixed32::fromRaw(0) - r_vec.x, Fixed32::fromRaw(0) - r_vec.y};
    
    planet.acc = forceDir * forceMagnitude;
}
```


品质技能（抄了报名问卷））
- 实验开展：(非湿实验ww)做过基础物理实验和模电数电实验，前者有具体的器材进行实操，后者主要是利用电脑软件进行电原理图的设计绘制，并仿真得到波形结果
- 数学建模：参加过美赛和国赛，具备建模基础，掌握常见模型和算法，并会使用overleaf进行论文排版
- 软件编程：会c/c++,python,matlab的语言
- 网页制作：无相关经验，但略有了解过基本的操作
- 美术设计：会使用可画来设计海报，具备审美能力
- 工程制造：熟练使用vivado来进行电路的设计和下板验证，并掌握vga
- 英文交流：选修过跨文化交际的课程，正在上新航道的托福口语和思辨演讲课，参加过学校举办的language night等活动，并做过对外国留学生的采访，和新加坡NTU活动负责人写过英文的邮件对接
- 宣传展示：获得过多项演讲口才相关的奖项，参演过很多话剧，拍摄过复旦大学官方宣传片，接受过央视的采访，参与过推送文案和排版以及责编的工作
- 其他：我喜欢音乐剧，喜欢合唱，对任何事物都充满着好奇和热情！生活积极向上，或许我可以给队伍带来正能量

<table style="width: 100%; border-collapse: collapse; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); overflow: hidden; cursor: pointer; transition: all 0.2s ease;" onmouseover="this.style.boxShadow='0 6px 8px rgba(0,0,0,0.15)'" onmouseout="this.style.boxShadow='0 4px 6px rgba(0,0,0,0.1)'">
    <tr style="background-color: #80b0e0ff;">
        <th style="padding: 10px 16px; text-align: left; font-weight: bold; color: #27374D; border: true;">兴趣爱好</th>
        <th style="padding: 10px 16px; text-align: center; font-weight: bold; color: #27374D; border: true;">example</th>
    </tr>
    <tr style="background-color: #d3e2e8ff;">
        <td style="padding: 8px 16px; border: true;">音乐剧</td>
        <td style="padding: 8px 16px; text-align: center; border: none;">frozen，汉密尔顿，人间失格</td>
    </tr>
    <tr style="background-color: #d3e2e8ff;">
        <td style="padding: 8px 16px; border: true;">干饭！</td>
        <td style="padding: 8px 16px; text-align: center; border: none;">蔡澜，西塔，令谷</td>
    </tr>
    <tr style="background-color: #d3e2e8ff;">
        <td style="padding: 8px 16px; border: true;">和人交流</td>
        <td style="padding: 8px 16px; text-align: center; border: none;">参加活动，合作打比赛</td>
    </tr>
    <tr style="background-color: #d3e2e8ff;">
        <td style="padding: 8px 16px; border: true;">新事物</td>
        <td style="padding: 8px 16px; text-align: center; border: none;">新比赛新课题</td>
    </tr>
    <tr style="background-color: #d3e2e8ff;">
        <td style="padding: 8px 16px; border: true;">外出play</td>
        <td style="padding: 8px 16px; text-align: center; border: none;">citywalk，公园</td>
    </tr>
</table>