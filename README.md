# Pytorch implement of "Dynamic Task Software Caching-Assisted Computation Offloading for Multiaccess Edge Computing".

This repository contains the code for our paper titled [Dynamic Task Software Caching-Assisted Computation Offloading for Multi-Access Edge Computing](https://ieeexplore.ieee.org/abstract/document/9862981).


# Citation:

Please use the following BibTeX citation if you use this respository in your work:
```
@ARTICLE{9862981,
  author={Chen, Zhixiong and Yi, Wenqiang and Alam, Atm S. and Nallanathan, Arumugam},
  journal={IEEE Transactions on Communications}, 
  title={Dynamic Task Software Caching-Assisted Computation Offloading for Multi-Access Edge Computing}, 
  year={2022},
  volume={70},
  number={10},
  pages={6950-6965},
  doi={10.1109/TCOMM.2022.3200109}}
  
  
  
  [7] Dynamic Task Software Caching-Assisted Computation Offloading for Multi-Access Edge Computing
作者：Chen Z, Yi W, Alam A S, et al.
出处：IEEE Transactions on Communications, 2022.
摘要：在多访问边缘计算（MEC）中，现有的任务软件缓存工作大多集中在网络边缘静态缓存数据，在实践中由于用户请求的时变，很难保持高可重用性。为此，本工作考虑在MEC服务器上进行动态任务软件缓存，以协助用户执行任务。具体来说，我们制定了一个联合任务软件缓存更新（TSCU）和计算卸载（COMO）问题，以在保证延迟约束的同时最小化用户的能源消耗，其中有限的缓存大小和MEC服务器的计算能力，以及时间-调查用户不同的任务需求。该问题被证明是非确定性多项式时间难题，因此我们根据它们的时间相关性将其转化为两个子问题，即实时COMO问题和基于马尔可夫决策过程的TSCU问题。我们首先将COMO问题建模为多用户博弈，并提出一种去中心化算法来解决其纳什均衡解。然后，我们提出了一种基于双深度Q网络(DDQN)的方法来解决TSCU策略。为了降低计算复杂度和收敛时间，我们为DDQN中的深度神经网络(DNN)提供了一种新设计，称为状态编码和动作聚合(SCAA)。在SCAA-DNN中，我们在输入层引入了dropout机制来编码用户的活动状态。此外，在输出层，我们设计了一个两层架构来动态聚合缓存动作，这能够解决巨大的状态动作空间问题。仿真结果表明，所提出的解决方案优于现有方案，节省超过12%的能量，并以更少的训练集收敛。
链接：
https://ieeexplore.ieee.org/abstract/document/9862981/
代码：
https://github.com/chfocus/DRL-MEC
