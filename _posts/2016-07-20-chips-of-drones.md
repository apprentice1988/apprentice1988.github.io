---
layout: post
title: 谈谈无人机芯片
date: 2016-07-20 06:40
---
这两天，华为进军无人机行业的新闻在无人机行业引起不小的关注。华为和无人机方案公司宙心科技，基于华为海思Hisilicon安防摄像头里的芯片开发出了一套无人机方案，并预计今年将会有基于该方案的无人机推上市场。他们宣称平台有三大优势：

* 电子稳像算法，可支持4K视频
* 极速图传，延迟只有100ms
* 快速启动，从冷启动到航拍业务启动完成，不超过3s

![海思芯片](http://o90dc46kr.bkt.clouddn.com/chip.jpg)

借这个话题，我们一起盘点一下各芯片制造商是如何觊觎无人机行业这杯羹的。

**Intel**为了推广其RealSense深度传感功能，去年以合作的名义投资了德国无人制造商Ascending科技，今天1月份又宣布收购该公司。Ascending公司产品目前已经开始使用Intel的RealSense技术。除此之外，Intel公司去年8月份投资了中国无人机厂商Yuneec 6000万美金，并和今年CES上推出了整合了RealSense功能的Typhoon H系列产品，虽然被外界证明该功能的演示存在作弊嫌疑。在这之前，Intel还对无人机公司Airware和PrecisionHawk进行过投资。



另一芯片巨头**高通(Qualcomm)**曾经收购了一家美国无人机公司KMelRobotics，将其飞控系统和手机芯片结合，开发了骁龙飞行平台。与国内的零度进行了合作，目前已经应用在了零度的即将上市的Dobby产品中。高通还曾对3DR进行投资。



**英伟达(Nvidia)** 也推出了两款面向消费级无人机的芯片模块—Tegra X1和Jetson TX1。这两种芯片组模块具有强大的图形运算能力，可提高无人机视觉识别应用。DJI在今年早些时候宣布基于Nvidia的Tegra芯片研发自己的开发平台Manifold。



再说说国内市场。DJI和零度的产品也都有采用过联芯科技的芯片方案。联芯科技是大唐电信旗下核心企业之一，凭借TD-SCDMA、TD-LTE技术积累在3G时代成为主要国内主要手机芯片供应商之一。联芯科技在无人机领域大放异彩，其采用了软件无线电方案的SDR平台备受青睐。与传统方案使用的2.4G WiFi频段不同，联芯的SDR平台可以让无人机自定义修改无线电频段，从而获得更远的传输距离，解决了核心的图传问题。



随着DJI Phantom4的推出，另一家成立于2005的芯片制造商也正式进入无人机芯片领域－Movidius。 Phantom4 使用了Movidius最新的Myriad 2. Movidius 第一代芯片Myriad 1曾被Google用于Tango项目。该公司最初解决老电影转成3D电影的方案，后来发现并锁定了机器视觉的发展方向。该公司目前专注于开发继CPU， GPU之后的VPU(Vision Processing Unit)和努力在现代计算，人工智能等领域开发相应的芯片方案。