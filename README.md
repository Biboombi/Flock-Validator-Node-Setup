# 明牌激励-隐私AI项目Flock 验证者节点搭建教程

## 项目简介
FLock 旨在为人工智能构建一个去中心化的隐私保护解决方案。FLock提出了一项名为联合学习区块（简称 FLocks）的研究计划，该计划使用区块链作为数据持有者之间的协调平台来进行机器学习，同时数据保持本地和隐私。通过用区块链取代收集数据和组织机器学习的中央实体，FLocks 旨在让用户能够从自己的数据中挖掘洞察力，并自行决定货币化。

## 关键事件
- **2024-03-28**: FLock.io 完成 600 万美元种子轮融资

## 项目概况
项目目前明牌激励测试网活动，CPU和GPU均可参与运行（GPU效率相对高很多）。

## 推荐运行配置
- 4核CPU
- 32G 运行内存
- 80G 硬盘
- 至少4070 TI GPU

## 安装指南
### 前置条件
- Ubuntu系统原生设备或虚拟机设备
- 白名单地址（[申请表格](https://blog.flock.io/news/trainflock)，没有白名单的话，得自己领水）

### 官方资源
- [FLock 官方推特](https://x.com/flock_io)
- [FLock 官方网站](https://www.flock.io/)
- [FLock 官方Discord](https://discord.com/invite/ay8MnJCg2W)

### 安装步骤
1. 前往网站质押FML代币获取验证者资格 [train.flock.io](https://train.flock.io) ，最低需要质押30个，账户通过GitHub验证即可。
2. 获取对应账户API。
3. 获取Hugging Face API [Hugging Face Token](https://huggingface.co/settings/tokens)。
4. 执行验证者节点安装：
    - **适用于中国内地**:
        ```bash
        wget -O flock.sh https://git.dadunode.com/smeb_y/Flock/raw/branch/main/Flock.sh && chmod +x flock.sh && ./flock.sh
        ```
    - **适用于全球**:
        ```bash
        wget -O flock.sh https://raw.githubusercontent.com/a3165458/Flock/main/Flock.sh && chmod +x flock.sh && ./flock.sh
        ```

### 节点运行日志
Flock 验证者节点搭建到此结束。

## 社群
- [Discord 社群](https://discord.gg/gk6Y7YqunR)

