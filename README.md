```powershell
PS C:\Users\RedJoker> Get-Command RedJoker | Format-List *

Name        : RedJoker
CommandType : 小工具作者
平台        : Windows 重度用户
信条        : 小工具也可以有温度
偏好        : 离线 · 绿色 · 单文件 · 不碰用户数据
主力        : Python / C# (.NET 8)
工具箱      : OpenCV · WPF · Win32 API · Emgu.CV · PyInstaller · manim
出没地      : 摄像头、任务栏托盘、系统钩子的第一线
```

```powershell
PS C:\Users\RedJoker> Get-ChildItem .\repos -Verbose

d----  face-guard                [Python]  鲸鱼娘护眼神器
                                       · 离线人脸检测，一贴脸就弹窗报警
                                       · 悬浮球蓝→红，实时显示你离屏幕多近
                                       · 单文件免安装，零联网零上传 ⭐

d----  redjoker2025.github.io    [HTML]   博客本体
                                       · 技术干货，更新随缘但篇篇实在

d----  say-chinese-ai-progamming [Python] 中文场景 AI 编程工具
                                       · 已停止维护，寻找接手人

d----  melon-field-os            [Shell]  吃瓜第一线
```

```powershell
PS C:\Users\RedJoker> Get-EventLog System -Newest 6

时间        事件
----        ----
2023.03     注册 GitHub，第一行代码入库
2025.12     博客上线，开始输出干货
2026.04     say-chinese-ai-progamming 发布
2026.05     用 C# 写了个 Verve
2026.08     melon-field-os 上线
2026.10     face-guard v2.2 发布 —— 鲸鱼娘正式上岗
```

```powershell
PS C:\Users\RedJoker> Get-Help RedJoker -Examples

---------- 示例 1：看博客 ----------
PS> start redjoker2025.github.io
    技术干货都在这，欢迎串门。

---------- 示例 2：养一只鲸鱼娘 ----------
PS> Start-Process FaceGuard.exe
    全程离线、免安装；凑近屏幕会被当场骂回座位。

---------- 示例 3：免费的鼓励 ----------
PS> Invoke-Star face-guard
    给仓库点个 ⭐，鲸鱼娘会很开心。
```

```powershell
PS C:\Users\RedJoker> exit

会话已保存。鲸鱼娘：慢走，路上坐直点 ( ˘•ω•˘ )
```

---

<div align="center">

**[博客](https://redjoker2025.github.io)** · **[face-guard](https://github.com/redjoker2025/face-guard)** · ⭐ 是对开源作者最便宜的鼓励

</div>
