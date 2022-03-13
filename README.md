
注意！！！此指令本只适用于hyzq版sans模拟器！！！

< >必填（有些可以不填） [ ]可以不填 { }前提，不用把框里的内容输入  如果没有框，必填 【】可以不填，如果填了之后的【】框指令都要跟着填
（）类似{ }

指令本最下面的小提示有部分细节的说明！
                                                                                               
运行基础（最好不要修改！）（要把这些一个一个复制到框里，要不然不能运行！）                     
0 CombatZoneResizeinstant 241 226 406 391
0 HeartTeleport 320 304		

→必须经过作者同意才可修改内容（B站ID：浩杨正气）

特别感谢：Lazybone、Fashion cheese

原版网址:http://jcw87.github.io/c2-sans-fight/（原版网址）
hyzq版网址：鸽

指令列表
FightXY（攻击XY设置）
ActXY（行动XY设置）
ItemXY（物品XY设置）
MercyXY（仁慈XY设置）
GasterBlaster（GB炮）
GetCombatZonePos（定位战斗框四坐标位置）
GetHeartPos（定位决心位置）
GetPlayerHp（获得玩家HP数据）
GetPlayerMaxHp（获得玩家血上限数据）
Ball（球）
BattleAngle（平滑移动屏幕的角度）
BattleScale（平滑移动屏幕的倍数）
SpinBattleAngle（旋转屏幕的角度）
BoneH（横向骨头）
BoneHRepeat（横向骨头连续发射）
BoneV（纵向骨头）
BoneVRepeat（纵向骨头连续发射）
BoneStabRepeat（小骨头墙）
BoneStab（骨头墙）
BoneBulletV（纵向绿心子弹骨头）
BoneBulletH（横向绿心子弹骨头）
BlackScreen（闪烁）
Platform（平台）
PlatformRepeat（平台连续发射）
PurplePlatform（紫平台）
PurplePlatformRepeat（紫平台连续发射）
Stopmusic（停止音乐）
SineBones（纵向波浪骨头）
SineBonesH（横向波浪骨头）
SansHead（sans头）
SansBody（sans身子）
SansAnimation（sans动画）
SansTorso（sans身子2）
SansSweat（sans汗）
SansSlam（引力）
SansRepeat（sans一辈子的运动量）
SansEndRepeat（sans停下来了）{执行条件：前面有出现SansRepeat指令才可有效}
SansText（sans说的内容）
SansX（sans的X坐标）
SansSlamDamage（SansSlam增加伤害附加指令）
SetMaxHp（设置血量上限）
Sound/music（音效/循环播放）
HeartTeleport（决心设置位置）
HeartMaxFallSpeed（设置决心掉落速度）
HeartMode（决心模式）
DamagePlayer（玩家伤害设置）
Destroy（删除）
CombatZoneResizeinstant（就是普通的战斗框，没什么其他的问题）
CombatZoneResize（可以利用 CombatZoneSpeed 来调整它的速度）
CombatZoneSpeed（设置战斗框移动速度）
ColorBoneV（彩色纵向骨）
ColorBoneH（彩色横向骨）
EndAttack（结束/重来）
TLResume（停止时间！！！）
TLPause（时间开始流动！！）
SetMaxHp（血上限设置）
:xxx（标签）（xxx为任意标签名）
*函数* SET（设置某个固定值）
*函数* ADD（增加某个现有的固定值）
*函数* SUB（减少某个现有的固定值）
*函数* MUL（乘法）
*函数* DIV（除法）
*函数* MOD（求余）
*函数* FLOOR（向下取整）
*函数* RND（创建随机值）
*函数* DEG（弧度化角度）
*函数* RAD（角度化弧度）
*函数* SIN（角度化正弦）
*函数* COS（角度化余弦）
*函数* ANGLE（角度计算）
*函数* JMPABS（直接跳转）
*函数* JMPREL（向下跳转）
*函数* JMPZ（为0跳转）
*函数* JMPNZ（非0跳转）
*函数* JMPE（相同跳转）
*函数* JMPNE（不相同跳转）
*函数* JMPL（小于跳转）
*函数* JMPNL（不小于跳转）
*函数* JMPG（大于跳转）
*函数* JMPNG（不大于跳转）

使用方法
#sans动作#

SansHead：
BlueEye（审判眼）
Closedeyes（闭眼）
Default（正常）
LookLeft（往左看）
noeyes（黑眼）
noeyes2（黑眼2）
NoTooth（鬼畜模式）
Tired1（疲劳）
Tired2（疲劳）
Wink（眨眼）

SansBody（sans身子）：
HandUp/Down/Left/Right（手向上/下/左/右）

SansAnimation（sans动作）：
HeadBob（只晃头（鬼畜模式））
Idle（正常摆动速度）
Tired（摆动幅度小）
Fast（速度快）

SansTorso（sans身子2）：
Default（普通）
shrug（肩飞天）

sanssweat（sans汗滴）：
0-3

SansSlam（引力）：
0=右 1=下 2=左 3=上

#音效#（Sound/music）
battletext（菜单字幕声音）
BoneStab（骨头墙发射）  
Ding（叮）
Dark（Gaster）
Flash（咔）
GasterBlast（骨炮发射声音）
GasterBlast2（骨炮发射声音2）
GasterBlaster（骨炮蓄力声音）
heartshatter（心碎声音）
heartsplit（心碎声音2）
menucursor（移动按钮）
menuselect（按钮选择）
mus_zz_megalovania（狂妄之人）
playerdamaged（玩家受伤）
playerheal（决心回血） 
playerfight（玩家攻击）
sansspeak（sans说话声）
Slam（bong）
warning（骨头墙准备）

#其他#

:xxx（标签）:<时间> :xxx（xxx为任意标签名）

Ball:<时间> Ball <坐标X> <坐标Y> <角度> <速度> <大小（0为普通，1为中，2为大，3为小，4为超大）> [模式](1为蓝骨，0为白骨，2=橙骨，3=红骨，4=绿骨 5=浅绿骨 6=黄骨) [透明度] [ID]

BattleAngle：<时间> BattleAngle <角度> [移动时间]

BattleScale：<时间> BattleScale <倍数> [移动时间]

SpinBattleAngle：<时间> SpinBattleAngle <旋转速度>

BlackScreen:<时间> BlackScreen <1=黑屏，0=恢复>

BoneV/H:<时间> BoneV/H <坐标X> <坐标Y> <长度> <朝向> <速度> [模式](1为蓝骨，0为白骨，2=橙骨，3=红骨，4=绿骨 5=浅绿骨 6=黄骨) [透明度] [ID] [二次加速速度]

BoneBulletV/H:<时间> BoneBulletV/H <朝向> <速度> [模式](1为蓝骨，0为白骨，2=橙骨，3=红骨，4=绿骨 5=浅绿骨 6=黄骨) [透明度] [ID]

BoneHRepeat:<时间> BoneHRepeat <坐标X> <坐标Y> <长度> <朝向> <速度> <发射次数> <发射间隔时间（间隔时间数值是像素）> [模式](1为蓝骨，0为白骨，2=橙骨，3=红骨，4=绿骨 5=浅绿骨 6=黄骨) [透明度]

BoneStab:<时间> BoneStab <朝向> <高度> <冷却时间> [出现保持时间]

BoneStabRepeat:<时间> BoneStabRepeat <朝向> <高度> <冷却时间> [出现保持时间] <坐标（统一左上角定位）> <数量>

BoneVRepeat:<时间> BoneVRepeat <坐标X> <坐标Y> <长度> <朝向> <速度> <发射次数> <发射间隔时间（间隔时间数值是像素）> [模式](1为蓝骨，0为白骨，2=橙骨，3=红骨，4=绿骨 5=浅绿骨 6=黄骨) [透明度]

CombatZoneResize:<时间> CombatZoneResize <坐标X①> <坐标Y①> <坐标X②> <坐标Y②> 【TLResume】
                 【时间】 【TLPause】

CombatZoneResizeInstant:<时间> CombatZoneResizeInstant <坐标X①> <坐标Y①> <坐标X②> <坐标Y②> 

CombatZoneSpeed:<时间> CombatZoneSpeed <速度>

ColorBoneV/H:<时间> ColorBoneV/H <坐标X> <坐标Y> <长度> <朝向> <速度> <R> <G> <B> [透明度]

DamagePlayer:<时间> DamagePlayer <伤害> <KR>

Destroy:<时间> Destroy <ID>

SetMaxHp:<时间> SetMaxHp <血上限>

GetCombatZonePos:<时间> GetCombatZonePos <变量> <变量> <变量> <变量>

GetHeartPos:<时间> GetHeartPos <变量> <变量>

GetPlayerHp:<时间> GetPlayerHp <变量>

GetPlayerMaxHp:<时间> GetPlayerMaxHp <变量>

GasterBlaster:<时间> GasterBlaster <模式> <初始坐标X> <初始坐标Y> <最终坐标X> <最终坐标Y> <朝向>  <冷却时间> <发射保持时间> [颜色]（1为蓝，2为橙）

HeartMaxFallSpeed:<时间> HeartMaxFallSpeed <速度> 

HeartMode:<时间> HeartMode <模式> (0:红 1:蓝 2:蓝橙 3:红橙 4:白 5:绿 6:青 7:黄)

HeartTeleport:<时间> HeartTeleport <坐标X> <坐标Y>

music:<时间> music <声音>

Platform:<时间> Platform <坐标X> <坐标Y> <长度> <朝向> <速度> [模式]（0为普通，1为反弹） [透明度] [ID]

PlatformRepeat:<时间> PlatformRepeat <坐标X> <坐标Y> <长度> <朝向> <速度> <发射次数> <发射间隔时间（间隔时间数值是像素）> [透明度]

PurplePlatform:<时间> Platform <坐标X> <坐标Y> <长度> <朝向> <速度> [模式]（0为普通，1为反弹） [透明度] [ID]

PurplePlatformRepeat:<时间> PlatformRepeat <坐标X> <坐标Y> <长度> <朝向> <速度> <发射次数> <发射间隔时间（间隔时间数值是像素）> [透明度]

SansSlamDamage:<时间> SansSlamDamage 1/0（后面加上SansSlam指令可以增加伤害）

sanssweat:<时间> sanssweat <数量，最多3滴>

SansX:<时间> SansX <坐标X>

SineBones:<时间> SineBones <长度（骨头数量）> <骨头间隔(负数为反向)> <速度> <高度> [透明度]

SineBonesH:<时间> SineBones <长度（骨头数量）> <骨头间隔(负数为反向)> <速度> <高度> [透明度]

Sound:<时间> Sound <声音> <速度(0可以停止音乐)>

FightXY/ActXY/ItemXY/MercyXY:<时间> FightXY/ActXY/ItemXY/MercyXY <X> <Y>

#函数#

ADD/SUB/MUL/DIV/MOD:<时间> <前面的ADD...> <变量> <数值/$变量> <数值/$变量>

RND:<时间> RND <变量> <最大限制（从0开始）>

SET/FLOOR/DEG/RAD/SIN/COS:<时间> <前面的SET...> <数值/$变量>

ANGLE:<时间> ANGLE <变量> <X1> <Y1> <X2> <Y2>

#JMP系列#

JMPZ/JMPNZ:<时间> JMPZ/JMPNZ <行数> <$变量>

JMPL/JMPNL/JMPG/JMPNG/JMPE/JMPNE:<时间> <前面的那些> <行数> <$变量> <数值>

JMPABS:<时间> JMPABS <行数>（不能填变量）

JMPREL:<时间> JMPREL <数值>

#关于TLResume#
战斗框移动的时候不会影响指令运行，假如0 CombatZoneResize 1 1 1 1 TLResume和0 SansText e放在一起，会等战斗框完全定型才能让sans说e，并且写完这条指令要接上TLPause（大概吧）

**小提示**

行数=标签，标签=行数，JMP系列所有的行数都可以用标签代替


GB炮距离移动后面等待时间+0.4=无差错时间（大部分，太近的话会有所变化）

边界距离：（不是战斗框！）X:0---640（亲测）
                          Y:0---480（亲测）
BlackScreen可以用来做动画

X:320 Y:304 战斗框中心

150是红心正常速度
750是蓝心掉落速度
480是战斗框默认还原速度

骨头生成时X坐标是在骨头左上角。

决心判定点在中下方。

决心掉落速度和战斗框移动速度设置后是固定的。

任何以‘$’开头值的列都将被解释为变量(例如：“$MyVariableName”)。这包括第一列中的延迟时间。可以使用自定义标识符来代替函数名来创建标签(例如：“:MyLabel”)。（转Fashion cheese）

指令不用区分大小写，变量和标签需要区分大小写，这点需要注意
