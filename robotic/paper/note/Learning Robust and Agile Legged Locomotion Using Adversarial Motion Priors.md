### 一手资料

### 二手资料
* [知乎-机器人步态最新论文速递 | Learning Robust and Agile Legged Locomotion Using Adversarial Motion Priors [译]](https://zhuanlan.zhihu.com/p/649964731?utm_psn=1717494318141685760)
### note
* RL网络结构：
	* 输入：本体感知状态$o_{p}^{t}$
	* 输出：12维关节位置矢量(PD位置控制)
* 奖励组成：
	* 任务奖励：线速度、角速度跟踪
	* 风格奖励：参考步态数据集，由神经网络判别（GAN）
	* 正则化奖励：关节水平罚分、步幅持续时间、环境碰撞惩罚


