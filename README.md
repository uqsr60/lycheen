# Lycheen 荔枝云 VPS 评测：香港/日本/美国多节点，最低 ¥8/月起

一直有人问我，有没有既便宜、线路又不烂的小众 VPS 主机商？今天聊聊荔枝云（Lycheen）——一家面向中文用户的云服务器商，产品覆盖香港、日本东京、美国犹他州、马来西亚等多个节点，BGP 多线路接入，价格挺实在的，入门款最低月付 ¥8 起。

<img width="3007" height="1298" alt="image" src="https://github.com/user-attachments/assets/2d0e7639-5bfd-4054-bffa-ce079f596a34" />

---

## 荔枝云是什么？

Lycheen，中文叫荔枝云，算是国人圈子里知名度不算特别高但口碑还不错的一家小众 VPS 商家。主打亚太区节点，走的是 BGP 多线路路由，官网全程中文，支付方式对国内用户友好。

产品线目前在售的有：

- **日本东京 BGP**（JP BGP v1 Standard）
- **香港 BGP v1 Lite**（普通流量计费款）
- **香港 BGP v3 Lite Unmetered**（无限流量款）
- **香港 BGP VDS/站群**
- **美国犹他州 BGP**（US SLC BGP v1）
- **英国 Storage VPS**
- **马来西亚家宽 NAT**（MY TIME NAT）
- **马来西亚 TIME VDS**

值得注意的是，2026 年初他们已经下架了 HKv2、UKv1、DEv1 及 SGv1 系列产品，算是做了一次产品线精简。

---

## 主要套餐价格对比

### 香港 BGP v1 Lite（计流量款）

搭载 AMD EPYC 7C13 处理器，NVMe 阵列存储，接入 PCCW/NTT/Cogent/RETN 等国际 Tier 1 运营商。无中国优化，适合中转使用或跑国际业务。

| 套餐 | CPU | 内存 | 硬盘 | 带宽 | 流量 | 月价 | 购买 |
|------|-----|------|------|------|------|------|------|
| Nano (Xmas) | 1 vCPU | 0.5 GB | 5 GB | 1 Gbps | 768 GB In+Out | ¥8.00 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v1-lite-nano-1) |
| Micro | 1 AMD EPYC vCPU | 1 GB | 5 GB | 1 Gbps | 1 TB In+Out | ¥14.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v1-lite-micro) |
| Small | 1 AMD EPYC vCPU | 2 GB | 10 GB | 1 Gbps | 2 TB In+Out | ¥28.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v1-lite-small) |
| Medium | 2 AMD EPYC vCPU | 4 GB | 20 GB | 2 Gbps | 5 TB In+Out | ¥68.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v1-lite-medium) |
| Large | 4 AMD EPYC vCPU | 8 GB | 40 GB | 5 Gbps | 10 TB In+Out | ¥118.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v1-lite-large) |

> ⚠️ Nano (Xmas) 为限量款，库存仅余 10 台，先到先得。

👉 [查看香港 BGP v1 所有套餐](https://www.lycheen.com/aff.php?aff=263&gid=hkbgp-v1-lite)

---

### 香港 BGP v3 Lite Unmetered（无限流量款）

接入 10 Gbps 骨干网络，NTT + TATA + EIE 混合 BGP 路由，移动方向尽力优化，适合大流量国际业务，支持 BGP Session、BYOIP、BYOASN（代播 IP/ASN）。

| 套餐 | CPU | 内存 | 硬盘 | 带宽 | 流量 | IPv4 | 月价 | 购买 |
|------|-----|------|------|------|------|------|------|------|
| Burstable 500M | 1 vCPU | 2 GB | 40 GB | 峰值 500M / 保底 125M | 无限 | ×1 | ¥135.00 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v3-lite-burstable-500m) |
| Burstable 1000M | 2 vCPU | 4 GB | 70 GB | 峰值 1000M / 保底 250M | 无限 | ×3 | ¥260.00 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v3-lite-burstable-1000m) |
| Dedicated 500M | 2 vCPU | 8 GB | 200 GB | 500M 可跑满 | 无限 | ×5 | ¥350.00 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v3-lite-dedicated-500m) |
| Dedicated 1000M | 4 vCPU | 16 GB | 380 GB | 1000M 可跑满 | 无限 | ×5 | ¥680.00 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=hk-v3-lite-dedicated-1000m) |

> 注：Burstable 两款目前显示 0 库存，Dedicated 款有少量余货，有需要的朋友建议尽快下手。

---

### 日本东京 BGP v1 Standard（国内优化款）

这是荔枝云里对国内访问最友好的一条线。接入了软银（SoftBank）+ Cogent + PCCWG + Lumen + NTT + TATA + BBIX + EIE Tokyo 等多家运营商，尽力优化中国大陆方向路由，IP 风险值低，流媒体解锁良好，还支持额外订购附加 IP 和流量包。

测试 IP：`23.151.104.1`

| 套餐 | CPU | 内存 | 硬盘 | 带宽 | 流量 | 月价 | 购买 |
|------|-----|------|------|------|------|------|------|
| Micro | 1 vCPU | 1 GB | 10 GB | 500 Mbps | 2 TB In+Out | ¥28.00 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=jp-v1-standard-micro) |
| Small | 1 vCPU | 1.5 GB | 15 GB | 1 Gbps | 3 TB In+Out | ¥52.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=jp-v1-standard-small) |
| Medium | 2 vCPU | 2 GB | 20 GB | 1 Gbps | 6 TB In+Out | ¥102.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=jp-v1-standard-medium) |
| Large | 2 vCPU | 4 GB | 40 GB | 1 Gbps | 10 TB In+Out | ¥199.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=jp-v1-standard-large) |

如果你主要需求是翻墙自用、流媒体解锁，或者跑一些面向国内用户的服务，日本线路是荔枝云里首选。Small 套餐 ¥52.80/月，1 Gbps 带宽跑 3 TB 流量，挺够用的。

👉 [查看日本 BGP 所有套餐及购买](https://www.lycheen.com/aff.php?aff=263&gid=jp-bgp-v1-standard)

---

### 美国犹他州 BGP v1（美国原生 IP）

美国原生 IPv4 / IPv6，TikTok 等流媒体解锁优秀，到洛杉矶仅 14ms 延迟，已优化移动去程路由。支持额外订购普通美国 IPv4（¥10/个/月）或 GTT 原生 ISP IPv4（¥20/个/月），量大可优惠。

测试 IP：`216.238.52.175`

| 套餐 | CPU | 内存 | 硬盘 | 带宽 | 流量 | 月价 | 购买 |
|------|-----|------|------|------|------|------|------|
| Tall | 1 vCPU | 1 GB | 10 GB | 1 Gbps | 2 TB In+Out | ¥14.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=us-slc-lite-v1-tall) |
| Grand | 1 vCPU | 2 GB | 15 GB | 1 Gbps | 4 TB In+Out | ¥28.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=us-slc-lite-v1-grand) |
| Venti | 2 vCPU | 4 GB | 30 GB | 1 Gbps | 6 TB In+Out | ¥49.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=us-slc-lite-v1-venti) |
| Trenta | 4 vCPU | 8 GB | 60 GB | 1 Gbps | 10 TB In+Out | ¥89.80 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=us-slc-lite-v1-trenta) |

注意 Quaranta（6 核 16 GB）目前库存为 0。美国这条线路对需要美国原生 IP 做 TikTok 运营、电商独立站、或者跑 AI API 的用户挺合适，¥14.80 入门价格在美国原生 IP 市场里算低的。

---

### 马来西亚家宽 NAT（真实住宅宽带）

这个比较有意思，用的是马来西亚 TIME 运营商真实家庭宽带线路，双栈动态 IP，IPv6 独立 /128。适合需要马来住宅 IP 的场景，比如本地化业务测试、某些对 IP 类型有要求的应用。

| 套餐 | CPU | 内存 | 硬盘 | 共享带宽 | 出向流量 | 月价 | 购买 |
|------|-----|------|------|----------|----------|------|------|
| Small | 1 vCPU | 2 GB | 15 GB | 200 Mbps | 3 TB 出单向 | ¥54.90 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=my-time-nat-small) |
| Medium | 2 vCPU | 4 GB | 25 GB | 200 Mbps | 5 TB 出单向 | ¥109.90 |  [立即购买](https://www.lycheen.com/aff.php?aff=263&pid=my-time-nat-medium) |

需要注意：该产品 IPv4 是共享的（每台 10 个端口），动态 IP 需自行部署 DDNS，**无退款政策**，购买前确认需求再下单。

---

## 几个场景，帮你挑套餐

**想便宜试试水、随便用用的：** 香港 HK v1 Lite Nano ¥8/月，但库存只剩 10 台，不确定还有没有。没货的话，美国 Tall ¥14.80 也是不错的起步款。

**国内访问优先、想要低延迟的：** 日本东京 BGP，软银等多运营商接入，Micro ¥28/月，体验下来应该比大多数这价位的亚太 VPS 好。

👉 [日本东京 BGP - 直接下单](https://www.lycheen.com/aff.php?aff=263&gid=jp-bgp-v1-standard)

**需要美国原生 IP 解锁流媒体 / TikTok 的：** 美国 SLC BGP，原生 IP 干净，流媒体解锁效果好，到洛杉矶 14ms，Grand 套餐 ¥28.80/月性价比挺高。

**大流量跑业务、不想算流量账的：** 香港 v3 Unmetered 系列，无限流量，500M / 1G 带宽可选，适合需要持续跑大量数据的场景。

**有马来西亚住宅 IP 需求的小众场景：** MY TIME NAT，真实家宽，TM 运营商，¥54.90 起。

---

## 注意事项

- 荔枝云近期下架了多个产品线（HKv2、UKv1、DEv1、SGv1），目前在售产品以官网实时显示为准
- 部分套餐库存极少，比如 HK v1 Lite Large 和 v3 Unmetered 的 Burstable 款，购买页面显示 0 可用
- 马来西亚 NAT 系列无退款，需谨慎
- 如需 BGP Session、BYOIP、自带 ASN 等高级网络功能，香港 v3 Unmetered 系列支持，其他产品线需工单确认

有问题可以在官网提交工单，也可以关注他们的 Telegram 频道获取最新活动通知。

👉 [前往荔枝云查看所有在售套餐](https://www.lycheen.com/aff.php?aff=263)
