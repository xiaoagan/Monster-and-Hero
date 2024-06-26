### 基本实现（使用Class将怪物、英雄进行封装）
有一个英雄，和一个怪物：
1. 我们可以在终端初始化英雄的血量、蓝量，和攻击力，以及怪物的血量和攻击力。
2. 英雄有4个技能，每个技能都有一定的伤害（或者能够加血），但是需要消耗一定的蓝量（可
以在代码中写死）。（可以考虑冷却时间，比如说，第一个技能3个回合才能放一次）。
3. 游戏是回合制游戏，英雄可以放技能以及普通攻击，怪物只能普通攻击。 首先是英雄攻击，然
后是怪物攻击。然后再是英雄攻击，接着是怪物攻击。依次循 环。 英雄可以通过键盘的输入
来选择技能还是普通攻击，但是如果英雄蓝量不够的话，就 没法放技能，因此攻击失败，此回
合不会造成任何伤害。 每个回合结束后英雄会回复一定的蓝量。（随着回合的增加，英雄的蓝
量回复能力增 强）
4. 输出最终获胜的结果。
5. 可以通过输入q，结束游戏。 在回合中，可以输入某个命令来查看双方的信息（英雄的血量、
蓝量，攻击力、回复能力以及怪物 的血量，攻击力）
### 提高
C++是一门面向对象（OOP）的语言，在上面的任务中，只是使用Class将功能和属性进行了分装，
并不能称之为OOP（应该是称之为ADT）。OOP有三个特性：
1. 封装：在上面的过程中已经尝试封装
2. 继承：？？
3. 多态：？？
### 想一想如何将继承和多态加入到上面的代码中。
Tips：
1. 英雄和怪物都有血量和攻击力，是不是可以理解为他们可以拥有同一个父类。
2. 如果他们属于同一个父类，那么多态怎么应用呢？？
 
