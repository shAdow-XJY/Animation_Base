# Animation_Base

UE： 刚更新的5.0.3 （虚幻没有向前兼容）

UE第三人称游戏初始模块，开始构建基础的动画状态机。

---

## State

1. 常速行走

2. 加速奔跑、加速冲刺

3. 蹲伏移动

4. 爬行移动

---

## Reference

1. [UE4角色走路速度？ - 知乎 (zhihu.com)](https://www.zhihu.com/question/51916226)
2. [如何使用Github管理UE4工程_大王怕我去巡山的博客-CSDN博客_github ue4](https://blog.csdn.net/weixin_33232568/article/details/97757384)
3. [使用混合空间 | 虚幻引擎5.0文档 (unrealengine.com)](https://docs.unrealengine.com/5.0/zh-CN/blend-spaces-in-animation-blueprints-in-unreal-engine/)
4. [虚幻引擎图文笔记：如何让角色可以蹲着走(Crouch Walk) 方法一 ：用BlendNode实现 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/340184938)
5. [如何使用UE5进行骨骼动画重定向UE5 Retarget Skeleton_FruitP的博客-CSDN博客](https://blog.csdn.net/weixin_42145757/article/details/125349208)
6. [mixamo到UE4_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Nf4y1k7Su/?vd_source=7f470a794558fd74d5bdeba354eb1f32)
7. [在虚幻引擎中创建宏 | 虚幻引擎5.0文档 (unrealengine.com)](https://docs.unrealengine.com/5.0/zh-CN/making-macros-in-unreal-engine/)
8. [虚幻引擎图文笔记：双击事件（Double Press/Tap Event）的蓝图实现_开发游戏的老王的博客-CSDN博客](https://blog.csdn.net/ttm2d/article/details/111951065)
9. [卡耐基梅隆大学提供——UE4——2500+动作：Updated: V2 Free CMU Mocap Animation Library (2500+) Retargeted to UE4 Skeleton - Unreal Engine / Character & Animation - Unreal Engine Forums](https://forums.unrealengine.com/t/updated-v2-free-cmu-mocap-animation-library-2500-retargeted-to-ue4-skeleton/100523)
10. 

---

## Write Down

1. mixamo动画导入有些许浮空或者其它问题，UE eidtor删除，重新导入，导入时选择变换（只有在导入时可选一次），调整即可。【emmmm后面发现没啥用，拉上场景运行就拉跨】
2. footIK Rig在Ani BP中开启和关闭不一定生效，对于template中的foot ik进行添加逻辑判断，避免匍匐爬行或者类似的平躺骨骼动画的脚部异常出错。



---

### Git

1. 设置代理
   
   ```
   git config --global http.proxy http://127.0.0.1:10809
   git config --global https.proxy https://127.0.0.1:10809
   ```
   
   

2. 取消代理
   
   ```
   git config --global --unset http.proxy
   git config --global --unset https.proxy
   ```
   
   
