# 开源代码汇总 — NLOS-OCC 论文

本文件记录 refs.bib 中 36 篇论文的开源代码搜索结果。
搜索渠道：GitHub API、豆包学术搜索、arXiv 论文页面。

---

## 一、找到开源代码的论文（1 篇直接对应 + 6 篇相关项目）

### 1. 直接对应论文代码

| 仓库 | 对应论文 | cite key | 说明 |
|------|----------|----------|------|
| `codes/EventOCC/` | Motion-Aware Optical Camera Communication with Event Cameras (arXiv:2412.00816, IEEE RAL 2024) | `event2024motion` | 论文正文直接引用 https://github.com/suhang99/EventOCC ；含代码、数据集和视频。17 stars。 |

### 2. 相关 OCC/VLC 开源项目（非直接对应但技术相关）

| 仓库 | 相关研究方向 | 说明 |
|------|-------------|------|
| `codes/Event-Beacon-Communication/` | 事件相机 OCC（RP6） | "Smart Visual Beacons with Asynchronous Optical Communications using Event Cameras", IROS 2022。事件相机+LED 调制解调。14 stars。 |
| `codes/Prometheus/` | 屏幕相机通信（RP4/RP7） | iOS 屏幕到相机 OCC 开源研究应用。20 stars。 |
| `codes/optical-camera-communication/` | OCC 通用工具（RP1-RP4） | OCC 相关类、函数和脚本集合。12 stars。 |
| `codes/python-vlc-rolling/` | CSK 滚动快门 VLC（RP2） | Python 包，模拟基于滚动快门的 CSK 调制 OCC。5 stars。 |
| `codes/rs-vlc-model/` | NLOS 滚动快门 VLC 模型（RP1） | Python 代码，模拟非视距滚动快门 VLC 基础模型。0 stars。 |
| `codes/VLCDetector/` | Android 滚动快门 VLC（RP7/RP11） | Java OpenCV 实现的滚动快门 VLC Android 应用。6 stars。 |

---

## 二、未找到开源代码的论文（35 篇）

以下论文经 GitHub API 搜索、豆包学术搜索、arXiv 页面检查后，未找到公开代码仓库。
这些论文多为 IEEE/ACM 付费出版，作者未公开代码或代码仅限私有。

### Part A: 顶会/顶刊论文 (MobiCom/MobiSys/TMC)
- `winklink2024` — WinkLink (MobiSys 2024): 未找到代码
- `ganocc2026` — GANOCCAS (TMC 2026): 未找到代码
- `passivevlc2017` — PassiveVLC (MobiCom 2017): 未找到代码
- `lightsync2013` — LightSync (MobiCom 2013): 未找到代码
- `pixnet2010` — PixNet: 未找到代码
- `cobra2012` — COBRA: 未找到代码
- `screencamera2015` — ScreenCamera: 未找到代码

### Part B: 期刊/会议论文
- `dong2023barker` — Barker code pilot OCC: 未找到代码
- `chen2021pilot` — Pilot-aided NLOS-OCC: 未找到代码
- `liu2023vehicular` — Vehicular OCC diversity: 未找到代码
- `mimoufsook2013` — MIMO UFSOOK: 未找到代码
- `lu2016raptor` — Raptor fountain code FSO: 未找到代码
- `pernice2016raptorq` — RaptorQ turbulence FSO: 未找到代码
- `unet2025nlos` — U-Net bit segmentation: 未找到代码
- `shirvani2021adaptive` — Adaptive V2V OCC: 未找到代码
- `neuromorphic2025nlos` — Neuromorphic NLOS OWC (arXiv:2503.11226): 未找到代码
- `risisac2025v2x` — RIS-ISAC V2X thesis: 未找到代码
- `mimonoma2025v2v` — MIMO-NOMA V2V-VLC: 未找到代码
- `yahia2022mimo` — MIMO V2V-VLC: 未找到代码
- `okasha2022hybrid` — Hybrid VLC+RF V2V: 未找到代码
- `sejan2023survey` — MIMO VLC survey: 未找到代码
- `yamazato2014vehicular` — Image-sensor VLC automotive: 未找到代码
- `aly2022vehicular` — Vehicular OCC diversity: 未找到代码
- `vlcNoma2023beamforming` — VLC-NOMA beamforming: 未找到代码

### Part C: IEEE 标准
- `ieee802157a2024` — IEEE 802.15.7a-2024: 标准，无代码
- `ieee8021572018` — IEEE 802.15.7-2018: 标准，无代码

### Part D: 扩展研究方向 (RP13-RP16)
- `chang2026uavocc` — UAV bidirectional OCC: 未找到代码
- `kondo2024farmocc` — Farm drone OCC: 未找到代码
- `tsai2024uavwatertoair` — Water-to-air UAV OCC: 未找到代码
- `hamidnejad2023uwmimoocc` — Underwater MIMO OCC: 未找到代码
- `nennouche2025semanticuwoc` — Semantic underwater OWC: 未找到代码
- `bostan2026crosslayer` — Cross-layer AI-native 6G: 未找到代码
- `du2025roisac` — Retroreflective optical ISAC: 未找到代码
- `li2026manchester` — Manchester coding turbulence OCC: 未找到代码
- `furukawa2025cskdl` — DL CSK equalization: 未找到代码

---

## 三、搜索方法说明

1. **GitHub API 搜索**: 使用 `https://api.github.com/search/repositories` 按论文关键词、作者名、系统名搜索。
2. **豆包学术搜索**: 搜索论文标题 + "github code" 关键词。
3. **arXiv 页面检查**: 查看 arXiv 论文 HTML 全文中的 "code" / "github" 链接。
4. **作者主页**: 通过 dblp/Semantic Scholar 查找作者 GitHub 主页。

共检查 36 篇论文，找到 1 篇直接对应代码 + 6 个相关开源项目，已全部 clone 至 `codes/` 目录。
