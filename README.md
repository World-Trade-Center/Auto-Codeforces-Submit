# Auto-Codeforces-Submit
A autohotkey script to submit codeforces codes automatically

by World_Trade_Center

1. 下载

   先去[AutoHotkey](https://www.autohotkey.com/)官网中傻瓜式下载AutoHotkey软件。

   下载本脚本的.ahk文件

   打开本文件，使用AutoHotkey打开。

   上述步骤即完成了下载。

2. 测量

   由于开发者使用的电脑是2240*1400的，属于不标准的分辨率。所以这里给大家提供测量选项，大家可以测量自己的数值后，配上分辨率私信@World_Trade_Center（uid=241867）。

   测量方法：

   1. 直接输入网址打开[codeforces提交界面](https://www.codeforces.com/contest/1/submit)

   2. 点击键盘中的 向下箭头按键。

   3. 打开截图软件（推荐：微信或qq）自带的，截图范围为屏幕最左上角 至 Submit按钮范围内的任意位置，不需要真的将图接下来，我们所需要的是像素（分辨率）Pos数值（应当为”$(x,y)$“或$x\times y$的格式）。
   4. 记录Pos数值的$x,y$

   即完成了测量

3. 微调

   使用记事本/vscode/notepad++等软件以文字形式打开本脚本，将脚本中的数个sleep后的时间延长或缩短（如果数值为2000，即等待2s。请合理估计自己的机器速度和codeforces的反应时间）

4. 使用

   1. 请使用热键为alt+b不会与其他功能冲突的ide

      如果要调整热键的，调整脚本第一行的内容。

      请调整为如下格式

      `（你所希望的格式）::`

      其中如果你的热键包含以下特殊按键的，请键入右列的代替字符	

   | 键盘  | 输入字符 |
   | ----- | -------- |
   | Alt   | !        |
   | Shift | +        |
   | Ctrl  | ^        |
   | Win   | #        |

   ​	例如你所希望的热键是win+l，请输入`#l`

   2. 在ide中编辑好代码，然后按alt+b（或你所修改的热键）

   3. 在第一个问题中输入这场codeforces的id（例如[Dashboard - Codeforces Beta Round #1 - Codeforces](https://codeforces.com/contest/1)的id是1）

   4. 在第二个问题中输入题目编号

      例：一场比赛有A,B,C,D,E1,E2,F

      A题编号为1，B题编号为2，C题编号为3，D题编号为4，E1编号为5，E2编号为6，F编号为7

   5. 在第三个问题中输入测量好的x

   6. 在第四个问题中输入测量好的y

   7. 然后等待运行，查看提交结果即可。
