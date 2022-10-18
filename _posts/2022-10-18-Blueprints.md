---
title: Blueprints
date: 2022-10-18 00:00:00 +0800
author: urusai2333
categories:
- Wiki
tags:
- 蓝图
- 卡池
toc: true
# img_path: /img/path/
---
**蓝图** 可以让玩家使用(赚到的) ![硬币](/icons/coin.png){: .normal w="24" h="24" } 硬币来为餐厅购买新的 [电器](https://wiki.plateupgame.com/appliances)、 [食材](https://wiki.plateupgame.com/ingredients)、 [装饰](https://wiki.plateupgame.com/Decorations)。

通常，每天会有 **5张** 蓝图会以信封的形式，出现在营业开始前的准备环节，玩家可以用 `抓取` 键打开它们 (信封的数量在装修日会有所变化，并受到 [蓝图桌](#蓝图桌) 的影响)。 走到一张蓝图上，会显示其对应的详细信息，然后玩家可以长按 `交互` 键进行购买。

蓝图详情里，视具体情况，可能会出现以下几个图标用来表示它所对应的属性:

- ![复印](/icons/copy.png){: .normal w="24" h="24" } 表示这张蓝图是用 [复印机](https://wiki.plateupgame.com/appliances/CopyingDesk) 拷贝出来的**复印件**。 它不能再次用复印机复印，但是允许参与升级，打折，或者重新随机。
- ![升级](/icons/upgrade.png){: .normal w="24" h="24" }  表示这张蓝图**可以**用 [研究桌](https://wiki.plateupgame.com/appliances/ResearchDesk) 进一步**升级**。
- ![硬币](/icons/coin.png){: .normal w="24" h="24" } 表示这张蓝图必须用硬币**购买**。 如果玩家硬币数量 ![Coins](/icons/coin.png){: .normal w="24" h="24" } 不够，这个图标会显示为 <span style="color: rgb(190, 29, 0);"><strong>红色</strong></span>。


准备环节结束后，掉落在地上的蓝图都会自动消失 (如果是开始练习模式，则只是暂时消失，练习结束后蓝图还会再出现)。 玩家可以用 `抓取` 键拿起蓝图，把它放进 [蓝图储藏柜](https://wiki.plateupgame.com/appliances/BlueprintCabinet)。 储藏柜里的蓝图受到“保护”，不会自动消失。

玩家可以通过蓝图桌、重新随机来获取想要的蓝图。 还可以对蓝图进行**升级**，来获取更高级的蓝图 (升级机制见 [科技研究](https://wiki.plateupgame.com/gameplay/Research)，升级列表见 [科技树](https://wiki.plateupgame.com/appliances/UpgradeTree))。

# 商店(系统)

所谓 **商店** 是指每天准备环节开始时，都会掉落一些蓝图给玩家购买的机制。 这些蓝图是从预设的“卡池”(pools)里随机抽取的。 “卡池”不是一成不变的，它的组成(蓝图)会随着玩家得到特定物品或[卡片](https://wiki.plateupgame.com/Cards) **发生变化** (卡池的具体机制见本文关于 [卡池](#卡池pools) 的部分)。

在 **普通营业日** *(除了 Day 1 和装修日)*...

- 系统会从 **[基础卡池](#基础卡池)** 中随机抽出 **4** 张蓝图，每过 5 天，该数量会减少 **1**，最小值为 **2**。
- **所有其他** 的蓝图都从 **[种子(seed)卡池](#种子seed卡池)** 里随机抽出。 玩家有一定的几率会抽到已经**升级**过的高级蓝图，这个几率一开始是 0， 每5天 增加 **10%**。



在 ![Copy](/icons/franchise.png){: .normal w="24" h="24" }![Copy](/icons/decoration.png){: .normal w="24" h="24" } **装修日** *( Day 6 以及接下来的每个第 5 天)*...

- **8** 张蓝图会从 [**装饰**](https://wiki.plateupgame.com/Decorations) 里随机抽取，可能是通用装饰，也可能是契合所选“餐厅主题”的装饰。
- 另外，系统也会随机给予不同风格的 **3** 张墙纸 和 **3** 种地板。 (这些物品不是用蓝图的形式提供，所以不能被储存在柜子里、或者用来重新随机)。



在 **Day 1** *(新游戏开始时)* 商店不会掉落任何物品，但是会给玩家提供...

- **1 张 [预定桌](https://wiki.plateupgame.com/appliances/BookingDesk)** 蓝图 (必须解锁?，且游戏选项里必须禁用 "预定桌以包裹的形式提供" )。
- 任何由 ![img](https://wiki.plateupgame.com/cards/card_icon_franchise_1.png){: .normal w="24" h="24" } **[联锁店卡片](https://wiki.plateupgame.com/Cards#franchise-cards)**(完成 Day 15 获得的金卡) 的特效免费提供的初始蓝图 (Bootstrapping?，抓取器，洗脸盆)。



如果想人工干预蓝图的随机掉落，可以使用 [蓝图桌](#蓝图桌) 来提前“选择”/“锁定”将要掉落的蓝图。 锁定的蓝图，在装修日也同样会掉落。

# 重新随机

**重新随机** 允许玩家重置掉所有的蓝图 (除了存放在 [蓝图储藏柜](https://wiki.plateupgame.com/appliances/BlueprintCabinet) 中的) ，由系统重新随机抽取相等数量的蓝图。

重新随机只能在准备环节进行，玩家在餐厅外面会看到一个骰子图标，对其长按 `交互` 键即可。 重新随机的初始花费为 10 ![Coins](/icons/coin.png){: .normal w="24" h="24" } 硬币，本局游戏内每次使用后花费递增 10 ![Coins](/icons/coin.png){: .normal w="24" h="24" } 。

跟商店系统类似，重新随机也遵循着一些(潜)规则:

- **所有** 蓝图都由系统从 **[种子(seed) 卡池](#种子seed卡池)** 里抽取。 [基础卡池](#基础卡池)的物品以及[非掉落物品](#非掉落品卡池)永远不会出现。
- 从 **Day 7** 开始，有几率出现已经 **升级** 过的电器蓝图。
- 在 **普通营业日**，只会出现非装修物品 (包括 [电器](https://wiki.plateupgame.com/appliances) 和 [食材](https://wiki.plateupgame.com/ingredients))。
- 在 ![Copy](/icons/franchise.png){: .normal w="24" h="24" }![Copy](/icons/decoration.png){: .normal w="24" h="24" } **装修日**，则只会出现 [装饰](https://wiki.plateupgame.com/Decorations)，装饰可能是通用装饰，也可能是契合所选“餐厅主题”的专用装饰。



玩家可以通过取出存放在蓝图储藏柜里的蓝图 (包括[复印机](https://wiki.plateupgame.com/appliances/CopyingDesk) ![Copy](/icons/copy.png){: .normal w="24" h="24" } 生成的蓝图复印件 )，扩大参与重新随机的蓝图数量，以取得更令人满意的结果。 值得提醒的是，在多人游戏中，如果进行重新随机时，有玩家手中正持有蓝图，则也同样会被重置。

# 蓝图桌

![Copy](/appliances/blueprintdesk.png){: .right w="224" h="224" }

  *更多详情见: [蓝图桌](https://wiki.plateupgame.com/appliances/BlueprintDesk)*

**蓝图桌** 允许玩家提前“选择“/锁定”一张接下来要掉落的蓝图。

每当结束准备环节开始营业时，餐厅里的每个蓝图桌就会**不定期**_\(指时间间隔不固定\)_ 地循环展示蓝图，选择范围包含未升级的 [电器](https://wiki.plateupgame.com/appliances) 和 [食材](https://wiki.plateupgame.com/ingredients)。 玩家对蓝图桌使用 `交互` 键，就可以锁定当前正在展示的那张蓝图。此时，蓝图桌上会显示绿色的对勾，表示该蓝图锁定成功。若打烊时(屏幕上方的进度条满)，玩家仍未手动锁定的蓝图桌，系统就会自动锁定当前正在展示的蓝图。

在 **普通营业日**，如果玩家拥有多个蓝图桌，就可以高效地覆盖掉商店的随机掉落机制。但是无论再多的蓝图桌，商店都**至少会保留1张**蓝图的名额，用来从 [基础卡池](#基础卡池) 中抽卡。另外，商店掉落的蓝图数量会随着蓝图桌的数量**增加**，以“容纳”玩家提前锁定的全部蓝图。

举例:
- **例 1  |  蓝图桌 x2 |  普通营业日** *(商店默认提供 **5** 张蓝图)*  
**3** 张蓝图从基础卡池和种子(seed)卡池里抽取， **2** 张由蓝图桌锁定，总计 **5** 张
- **例 2  |  蓝图桌 x10 |  普通营业日** *(商店默认提供 **5** 张蓝图)*  
**1** 张蓝图从基础卡池抽取， **10** 张由蓝图桌锁定，总计 **11** 张



在 ![Copy](/icons/franchise.png){: .normal w="24" h="24" }![Copy](/icons/decoration.png){: .normal w="24" h="24" } **装修日**，蓝图桌锁定的蓝图数量则单独额外计算，不会占用常规掉落的 **8** 张 [装饰](https://wiki.plateupgame.com/Decorations) 蓝图的名额。

- **例 3  |  蓝图桌 x10  |  装修日** *(商店默认提供 **8** 张蓝图)*  
**8** 张蓝图从装饰品里抽取， **10** 张由蓝图桌锁定，总计 **18** 张



一般来说，蓝图桌永远不会出现 **[非掉落品卡池](#非掉落品卡池)** 里的 [电器](https://wiki.plateupgame.com/appliances) 和 [食材](https://wiki.plateupgame.com/ingredients)，但有一个例外是 [咖啡机](https://wiki.plateupgame.com/recipes/StartersSidesDesserts#desserts)。 当玩家选择了 ![img](https://wiki.plateupgame.com/cards/card_icon_starterssidesdesserts_1.png){: .normal w="24" h="24" } **黑咖啡** 卡片，蓝图桌就成了获取额外的咖啡机的唯一渠道 _(商店默认掉落和重新随机都无法获取)_ 。

# 卡池(Pools)

**卡池** 指特定卡片构成的组合，用来作为随机抽取的卡片来源。基于卡池进行随机的有商店系统、重新随机、[蓝图桌](#蓝图桌) (随机抽取的既定规则已在相关部分阐述)。 某些物品从属的卡池可能会发生变化，取决于玩家当前生效的 [卡片](https://wiki.plateupgame.com/Cards) 以及餐厅中已经拥有的电器。



## 基础卡池

|                **永久**                                            |||||
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [![img](/appliances/counter.png){: .normal w="96" h="96" } <br>柜台](https://wiki.plateupgame.com/appliances/Counter) | [![img](/appliances/diningtable.png){: .normal w="96" h="96" } <br>餐桌](https://wiki.plateupgame.com/appliances/DiningTable) | [![img](/appliances/hob.png){: .normal w="96" h="96" } <br>灶台](https://wiki.plateupgame.com/appliances/Hob) | [![img](/appliances/plates.png){: .normal w="96" h="96" } <br>盘子](https://wiki.plateupgame.com/appliances/Plates) | [![img](/appliances/sink.png){: .normal w="96" h="96" } <br>水池(官译“浸泡”)](https://wiki.plateupgame.com/appliances/Sink) |


| **可变**                                              |                                                              | 
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [![img](/appliances/researchdesk.png){: .normal w="96" h="96" } <br>研究桌](https://wiki.plateupgame.com/appliances/ResearchDesk) | [![img](/appliances/blueprintcabinet.png){: .normal w="96" h="96" } <br>蓝图储藏柜](https://wiki.plateupgame.com/appliances/BlueprintCabinet) |

**基础卡池** 包含了餐厅所必须的基础物品，在游戏前期是最常见的。

基础卡池的组成可能会随着游戏进程发生变化，比如

- 玩家的餐厅一旦拥有了**[研究桌](https://wiki.plateupgame.com/appliances/ResearchDesk)**，它就会从基础卡池中 **移除**，并转移至种子(seed)卡池。
- **[蓝图储藏柜](https://wiki.plateupgame.com/appliances/BlueprintCabinet)** 同上 (如果游戏开始就拥有蓝图储藏柜，同样计算在内)。
- 由 ![img](https://wiki.plateupgame.com/cards/card_icon_franchise_1.png){: .normal w="24" h="24" } **[联锁店卡片](https://wiki.plateupgame.com/Cards#franchise-cards)** 特效引入的，商店会周期性提供的某些特定物品，将从种子(seed)卡池 **添加** 到基础卡池。



重新随机永远不会抽到基础卡池中的物品。



## 种子(seed)卡池

**种子卡池** 取决于玩家当前的种子(seed) (或者说 *地图*)， 它包含了不属于基础卡池和非掉落品卡池的物品。 重新随机的全部蓝图、商店随机的部分蓝图，以及 [蓝图桌](https://wiki.plateupgame.com/appliances/BlueprintDesk)，都是从该卡池里进行随机抽取。

重复游玩同样的地图种子(seed) 或者重新开始某一天，在(影响掉落的)其他变量保持不变的前提下，商店的蓝图掉落也会固定不变。 换句话说，即便是同样的地图种子(seed) ，只要有物品在各卡池之间发生了转移 (比如，选择了新的 [菜谱卡片](https://wiki.plateupgame.com/Cards#food-cards)，拥有/没有 [研究桌](https://wiki.plateupgame.com/appliances/ResearchDesk) 和 [蓝图储藏柜](https://wiki.plateupgame.com/appliances/BlueprintCabinet))，商店的掉落就可能会不同。总之，掉落取决于当前种子(seed)卡池有哪些蓝图。



## 非掉落品卡池

**非掉落品卡池** 主要包含餐厅当前还不需要的 [食材和设备](https://wiki.plateupgame.com/ingredients) 。

一般来说，商店、重新随机、蓝图桌不会出现非掉落品，除非玩家选择的 [菜谱卡片](https://wiki.plateupgame.com/Cards#food-cards) 引入了新的食材和设备。这种情况下，相关物品才会被转移到 **种子(seed)卡池** 里。

上述规则有一些例外:

- **[汉堡肉饼](https://wiki.plateupgame.com/ingredients/BurgerPatty)** 永远限定于非掉落品卡池，不会转移。
- **[咖啡机](https://wiki.plateupgame.com/recipes/StartersSidesDesserts#desserts)** 只能从 [蓝图桌](https://wiki.plateupgame.com/appliances/BlueprintDesk) 获取 (商店和重新随机无法获取)，且要求玩家必须已经拥有 ![img](https://wiki.plateupgame.com/cards/card_icon_starterssidesdesserts_1.png){: .normal w="24" h="24" } **黑咖啡** 卡片。
- **[鱼](https://wiki.plateupgame.com/ingredients)** 这种食材没有对应的蓝图可以获取。 取而代之，玩家可以通过 ![img](https://wiki.plateupgame.com/cards/card_icon_extras_1.png){: .normal w="24" h="24" } **Fish Selection** 卡片获取。



# 一些提示

- 在游戏前期，如果你不购买 [研究桌](https://wiki.plateupgame.com/appliances/ResearchDesk) ，它就会一直留在基础卡池里。 于是乎，玩家可以将商店掉落的第一张研究桌蓝图保存在 [蓝图储藏柜](https://wiki.plateupgame.com/appliances/BlueprintCabinet) 中，然后等待商店掉落另一张研究桌蓝图。 因为游戏前期，基础卡池的物品出现概率远远高于其他卡池的物品，玩家这样做就可以很快获得 2 张研究桌蓝图，也即，可以立刻升级出一个蓝图桌/复印机/折扣桌。 (机制详解见 [基础卡池](#基础卡池))
- 重新随机时，玩家往往希望有足够多的蓝图进行重置。 这可以通过 [复印机](https://wiki.plateupgame.com/appliances/CopyingDesk) 和几个蓝图储藏柜来达成(翻倍的快乐)。 另一个办法，是购买多个蓝图桌(多多益善)，因为当蓝图桌的数量超过商店默认提供的蓝图数，它就能让玩家得到额外的蓝图。 (机制详解见 [蓝图桌](#蓝图桌) )