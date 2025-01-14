---
permalink: /
layout: page
title: Home
---

## Security Researcher & Developer

## Research Interest  

- System security
  - Trusted Execution Environments (TrustZone, ARM CCA, SGX, Secure Processor) and confidential computing
  - OS Security
  - Side-channel attacks and defenses
  - Bug finding and Exploitations
- Machine learning security (e.g., federated learning, LLM security)
- Applied cryptography (e.g., Zero Knowledge Proof)

## About me

I'm one of (passionate) security researchers and developers.
I got B.S degree in Department of Software at [Gachon University](https://www.gachon.ac.kr/english/) in 2013.
Also, I was in [Samsung Software Membership](https://www.secmem.org/) (at Gangnam) from 2011 to 2013.
Since 2013, I've been working for [Samsung Research](https://research.samsung.com/).
Here is my [CV](jinbum-cv.pdf) which details each of what I've done so far.

## Links

[blog](https://jinb-park.hashnode.dev), [GitHub](https://github.com/jinb-park), [LinkedIn](https://www.linkedin.com/in/jinbum-park-6040ba188/), [Google Scholar](https://scholar.google.com/citations?user=e-o2O2IAAAAJ), [Instagram](https://www.instagram.com/tlos6733/)

## Projects

#### 2023-present

- Islet: An on-device confidential computing platform (based on ARM CCA) [[code](https://github.com/islet-project/islet)]

#### 2021-2022

- A federated learning framework for mobile devices

#### 2020-2021

- Rust-based full-stack OS for secure element (from kernel to application framework)

#### 2018

- Real-time Kernel Protection (RKP)
  - Tiny hypervisor + hypervisor-based kernel monitoring solution on ARM64 arch.

#### 2014-2016

- System Integrity Monitor (SIM) Version 1.0 ~ 3.0
  [[CC certification report](https://commoncriteriaportal.org/files/epfiles/[KECS-CR-16-08]%20Samsung%20Smart%20TV%20Security%20Solution%20GAIA%20V1.0%20Certification%20Report.pdf)]
  - SIM is a kernel integrity monitoring solution based on ARM TrustZone and Custom hardware IP for security.
  - SIM takes a part of Samsung Smart TV Security Solution GAIA.

#### 2013-2014

- Samsung DRM (SDRM)
  - Developed Samsung DRM to protect sensitive contents
  - Used in Samsung Smart TV

## Publications

- EdgeShield: A Security Monitor Framework For On-Device Confidential Computing
  - Jinbum Park, Bokdeuk Jeong, Sunwook Eom, Taesoo Kim
  - Under submission

- TikTag: Breaking ARM's Memory Tagging Extension with Speculative Execution [[paper](https://arxiv.org/abs/2406.08719)]
  - Juhee Kim, Jinbum Park, Sihyeon Roh, Jaeyoung Chung, Youngjoo Lee, Taesoo Kim, Byoungyoung Lee
  - 46th IEEE Symposium on Security and Privacy (IEEE S&P 2025) (to appear)

- PeTAL: Ensuring Access Control Integrity against Data-only Attacks on Linux
  - Juhee Kim, Jinbum Park, Yoochan Lee, Chengyu Song, Taesoo Kim, Byoungyoung Lee
  - ACM CCS 2024

- ViK: Practical Mitigation of Temporal Memory Safety Violations through Object ID Inspection [[paper](https://dl.acm.org/doi/10.1145/3503222.3507780)]
  - Haehyun Cho, Jinbum Park, Adam Oest, Tiffany Bao, Ruoyu Wang, Yan Shoshitaishvili, Adam Doupé, Gail-Joon Ahn
  - The 27th ACM International Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS '22)

- In-Kernel Control-Flow Integrity on Commodity OSes using ARM Pointer Authentication
  [[paper](https://arxiv.org/pdf/2112.07213.pdf), [code](https://github.com/SamsungLabs/PALinux)]
  - Sungbae Yoo(\*), Jinbum Park(\*), Seolheui Kim, Yeji Kim, Taesoo Kim (\*: co-leading authors)
  - The 31st USENIX Security Symposium (USENIX Security 2022)

- Exploiting Uses of Uninitialized Stack Variables in Linux Kernels to Leak Kernel Pointers
  [[paper](https://www.usenix.org/system/files/woot20-paper-cho.pdf), [code](https://github.com/jinb-park/leak-kptr)]
  - Haehyun Cho, Jinbum Park, Joonwon Kang, Tiffany Bao, Ruoyu Wang, Yan Shoshitaishvili, Adam Doupe, Gail-Joon Ahn
  - The 14th USENIX Workshop on Offensive Technologies (WOOT '20)

- SmokeBomb: Effective Mitigation Method against Cache Side-channel Attacks on the ARM Architecture
  [[paper](https://dl.acm.org/doi/pdf/10.1145/3386901.3388888), [code](https://github.com/samsung/smoke-bomb)]
  - Haehyun Cho, Jinbum Park, Donguk Kim, Ziming Zhao, Yan Shoshitaishvili, Adam Doupe, Gail-Joon Ahn
  - The 18th ACM International Conference on Mobile Systems, Applications, and Services (MobiSys 2020)

- Prime+Count: Novel Cross-world Covert Channels on ARM TrustZone
  [[paper](http://www.public.asu.edu/~hcho67/papers/prime+count-acsac18.pdf), [code](https://github.com/samsung/prime-count)]
  - Haehyun Cho, Penghui Zhang, Donguk Kim, Jinbum Park, Choong-Hoon Lee, Ziming Zhao, Adam Doupé, and Gail-Joon Ahn
  - Annual Computer Security Applications Conference (ACSAC) 2018

- A Snoop-Based Kernel Introspection System against Address Translation Redirection Attack
  [[paper](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07047473)]
  - Donguk Kim, Jihoon Kim, Jinbum Park, Jinmok Kim
  - Journal of The Korea Institute of Information Security & Cryptology VOL.26, NO.5, Oct. 2016

- An Efficient Kernel Introspection System using a Secure Timer on TrustZone
  [[paper](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06505646)]
  - Jinmok Kim, Donguk Kim, Jinbum Park, Jihoon Kim, Hyoungshick Kim
  - Journal of The Korea Institute of Information Security & Cryptology VOL.25, NO.4, Aug. 2015

## Talks (Industry conferences)

- On-Device Confidential Computing: Updates on Our Activities and Future Potential [[video](https://youtu.be/YP2jFD9uPjk?si=Kn-K_ysCAf9K_SDA)]]
  - Jinbum Park, Heeill Wang
  - Samsung Security Tech Forum 2024 (SSTF 2024)

- Breaking ARM MTE with Speculative Execution
  - Jinbum Park
  - Zer0Con 2024

- Taking Kernel Hardening to the Next Level
  [[slide](https://i.blackhat.com/Asia-22/Friday-Materials/AS-22-Park-Taking-Kernel-Hardening-to-the-Next-Level.pdf), [video](https://youtu.be/1titzBiuxSc)]
  - Jinbum Park, Haehyun Cho, Sungbae Yoo, Seolheui Kim, Yeji Kim, Bumhan Kim, Taesoo Kim
  - Blackhat ASIA 2022

- Cache Attacks on Various CPU Architectures
  [[slide](cache-attack-poc2020-r2.pdf), [video](https://drive.google.com/file/d/1sqasfokB0LkGUvpo_G-z0XNODu4EJkJM/view)]
  - Jinbum Park
  - POC 2020

- Micro-architectural attack and defense on Linux kernel
  [[slide](https://www.soscon.net/content/data/session/Day%201_1630_2.pdf)]
  - Jinbum Park, Joonwon Kang
  - Samsung Open Source Conference (SOSCON) 2019

- Leak kernel pointer by exploiting uninitialized uses in Linux kernel
   [[slide](leak-kptr.pdf), [code](https://github.com/jinb-park/leak-kptr)]
  - Jinbum Park
  - Zer0Con 2019

- Attack and Defense on Linux kernel
  [[slide](https://www.sosconhistory.net/soscon2018/pdf/day1_1330_3.pdf), [code](https://github.com/jinb-park/linux-exploit/tree/master/samples)]
  - Jinbum Park
  - Samsung Open Source Conference (SOSCON) 2018
  
- Exploit Linux kernel eBPF with side-channel
  [[slide](Exploit-Linux-kernel-eBPF-with-side-channel.html), [code](https://github.com/jinb-park/linux-exploit)]
  - Jinbum Park
  - KIMCHICON 2018

- Host-based DRDoS Defense Model proposed and implemented
  - Jinbum Park
  - Conference on Information Security and Cryptology. Winter 2012 (CISC-W'12)

## Opensource Projects

- KSPP Study: Analysis on Kernel Self-Protection: Understanding Security and Performance Implication
  [[white paper](https://samsung.github.io/kspp-study/)]

- CSCA: Crypto Side Channel Attack
  [[code](https://github.com/jinb-park/crypto-side-channel-attack)]

## Opensource Contributions

#### Linux kernel (selected)

- Fix vulnerable gadgets to variant1 attack
  [patch-[0](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=55690c07b44a), [1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=3a2af7cccbba)]

- arm: Makes ptdump reusable and add WX page checking
  [[patch](https://lkml.org/lkml/2017/12/7/321)]
  
- arm: Add ARCH_HAS_FORTIFY_SOURCE
  [patch-[0](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=73b9160d0dfe), [1](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=ee333554fed5)]
  
#### Ubuntu kernel

- Revert barrier-patch which turns out be vulnerable to variant4 attack
  [patch-[0](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/xenial/commit/?id=cb0321f01227), [1](https://git.launchpad.net/~ubuntu-kernel/ubuntu/+source/linux/+git/xenial/commit/?id=48a028480eb0)]

## Contact

- E-mail : jinb.park7@gmail.com
