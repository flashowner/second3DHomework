# second3DHomework

### 1. c#
动态数组（ArrayList）
动态数组（ArrayList）代表了可被单独索引的对象的有序集合。它基本上可以替代一个数组。但是，<br>
与数组不同的是，您可以使用索引在指定的位置添加和移除项目，动态数组会自动重新调整它的大小。<br>
它也允许在列表中进行动态内存分配、增加、搜索、排序各项。<br>
<br>
ArrayList 类的方法和属性<br>
下表列出了 ArrayList 类的一些常用的 属性：<br>
<table border="1">
  <tr>
    <th>属性</th>
    <th>描述</th>
  </tr>
  <tr>
    <td>Capacity</td>
    <td>获取或设置 ArrayList 可以包含的元素个数。</td>
  </tr>
  <tr>
    <td>Count</td>
    <td>获取 ArrayList 中实际包含的元素个数。</td>
  </tr>
  <tr>
    <td>IsFixedSize</td>
    <td>获取一个值，表示 ArrayList 是否具有固定大小。</td>
  </tr>
  <tr>
    <td>IsReadOnly</td>
    <td>获取一个值，表示 ArrayList 是否只读。</td>
  </tr>
  <tr>
    <td>Item</td>
    <td>获取或设置指定索引处的元素。</td>
  </tr>
</table>
<br>

下表列出了 ArrayList 类的一些常用的 方法：<br>
<table border="1">
  <tr>
    <th>序号</th>
    <th>方法名 & 描述</th>
  </tr>
  <tr>
    <td>1</td>
    <td>public virtual int Add( object value ); 
    在 ArrayList 的末尾添加一个对象。</td>
  </tr>
  <tr>
    <td>2</td>
    <td>public virtual void AddRange( ICollection c ); 
在 ArrayList 的末尾添加 ICollection 的元素。</td>
  </tr>
  <tr>
    <td>3</td>
    <td>public virtual void Clear();
从 ArrayList 中移除所有的元素。</td>
  </tr>
  <tr>
    <td>4</td>
    <td>public virtual bool Contains( object item ); 
判断某个元素是否在 ArrayList 中。</td>
  </tr>
  <tr>
    <td>5</td>
    <td>public virtual ArrayList GetRange( int index, int count ); 
返回一个 ArrayList，表示源 ArrayList 中元素的子集。</td>
  </tr>
  <tr>
    <td>6</td>
    <td>public virtual int IndexOf(object);
返回某个值在 ArrayList 中第一次出现的索引，索引从零开始。</td>
  </tr>
  <tr>
    <td>7</td>
    <td>public virtual void Insert( int index, object value ); 
在 ArrayList 的指定索引处，插入一个元素。</td>
  </tr>
  <tr>
    <td>8</td>
    <td>public virtual void InsertRange( int index, ICollection c ); 
在 ArrayList 的指定索引处，插入某个集合的元素。</td>
  </tr>
  <tr>
    <td>9</td>
    <td>public virtual void Remove( object obj ); 
从 ArrayList 中移除第一次出现的指定对象。</td>
  </tr>
  <tr>
    <td>10</td>
    <td>public virtual void RemoveAt( int index ); 
移除 ArrayList 的指定索引处的元素。</td>
  </tr>
  <tr>
    <td>11</td>
    <td>public virtual void RemoveRange( int index, int count ); 
从 ArrayList 中移除某个范围的元素。</td>
  </tr>
  <tr>
    <td>12</td>
    <td>public virtual void Reverse();
逆转 ArrayList 中元素的顺序。</td>
  </tr>
  <tr>
    <td>13</td>
    <td>public virtual void SetRange( int index, ICollection c ); 
复制某个集合的元素到 ArrayList 中某个范围的元素上。</td>
  </tr>
  <tr>
    <td>14</td>
    <td>public virtual void Sort();
对 ArrayList 中的元素进行排序。</td>
  </tr>
  <tr>
    <td>15</td>
    <td>public virtual void TrimToSize();
设置容量为 ArrayList 中元素的实际个数。</td>
  </tr>
</table>
<br>
<br>
哈希表（Hashtable）<br>
Hashtable 类代表了一系列基于键的哈希代码组织起来的键/值对。它使用键来访问集合中的元素。<br>
当您使用键访问元素时，则使用哈希表，而且您可以识别一个有用的键值。哈希表中的每一项都有一个键/值对。键用于访问集合中的项目。<br>
下表列出了 Hashtable 类的一些常用的 属性：<br>
<table border="1">
  <tr>
    <th>属性</th>
    <th>描述</th>
  </tr>
  <tr>
    <td>Count</td>
    <td>获取或设置 ArrayList 可以包含的元素个数。</td>
  </tr>
  <tr>
    <td>Count</td>
    <td>获取 Hashtable 中包含的键值对个数。</td>
  </tr>
  <tr>
    <td>IsFixedSize</td>
    <td>获取一个值，表示 Hashtable 是否具有固定大小。</td>
  </tr>
  <tr>
    <td>IsReadOnly</td>
    <td>获取一个值，表示 Hashtable 是否只读。</td>
  </tr>
  <tr>
    <td>Item</td>
    <td>获取或设置与指定的键相关的值。</td>
  </tr>
   <tr>
    <td>Keys</td>
    <td>获取一个 ICollection，包含 Hashtable 中的键。</td>
  </tr>
  <tr>
    <td>Values</td>
    <td>获取一个 ICollection，包含 Hashtable 中的值。</td>
  </tr>
</table>
<br>下表列出了 Hashtable 类的一些常用的 方法：<br>
<table border="1">
  <tr>
    <th>序号</th>
    <th>方法名 & 描述</th>
  </tr>
  <tr>
    <td>1</td>
    <td>public virtual void Add( object key, object value ); 
向 Hashtable 添加一个带有指定的键和值的元素。</td>
  </tr>
  <tr>
    <td>2</td>
    <td>public virtual void Clear(); 
从 Hashtable 中移除所有的元素。</td>
  </tr>
  <tr>
    <td>3</td>
    <td>public virtual bool ContainsKey( object key ); 
判断 Hashtable 是否包含指定的键。</td>
  </tr>
  <tr>
    <td>4</td>
    <td>public virtual bool ContainsValue( object value ); 
判断 Hashtable 是否包含指定的值。</td>
  </tr>
  <tr>
    <td>5</td>
    <td>public virtual void Remove( object key ); 
从 Hashtable 中移除带有指定的键的元素。</td>
  </tr>
</table>
<br>
<br>

### 2. 简答并用程序验证
* 游戏对象运动的本质其实是游戏对象随着游戏运行时每一帧的变化，主要指的是空间上的变化，而<br>
  空间上的变化主要是游戏对象trnasform属性中position的值和rotation的值，position的值说明<br>
  了物体相对于世界或者是它的父对象的位置，也就是相对位置，rotation的值说明了物体在x轴，y<br>
  轴，z轴的旋转角度<br><br>
* 实现物体的抛物线运动<br>
![](https://github.com/flashowner/second3DHomework/blob/master/%E5%9B%BE%E7%89%871.PNG) <br>
第一种方法是通过改变物体的position来实现抛物线的运动的，在这里可以构造一个Vector向量，其中x轴<br>
方向的值是每一帧变化的count，y轴方向的值是count * count, z轴的值为0。这样可以构造一个y = x^2的抛物线。<br>
第二种方法是是通过transform属性的translate方法来实现水平方向的位移，x，y，z轴的值与第一种方法相同，<br>
通过许多细小的直线组成一个平滑的抛物线。<br>
第三种方法是通过给物体添加刚体部件，通过AddForce方法来给物体施加x轴和y轴方向的力实现曲线运动也就是抛物线。<br>
<br>

* 写一个程序，实现一个完整的太阳系， 其他星球围绕太阳的转速必须不一样，且不在一个法平面上。<br>
在这里我是用MVC架构实现的，首先是按照各个行星的大小和样子制成模型，放到Resources文件夹下的Prefabs文件夹。<br>
![](https://github.com/flashowner/second3DHomework/blob/master/%E5%9B%BE%E7%89%872.PNG) <br>
然后在脚本里动态生成各个行星，并且用MoveAround方法使得它们按照不同的法向量围绕太阳转，同时将MoveAround<br>
的target设为自己的transform属性的position, 这样就可以有自转的效果了。<br>

![](https://github.com/flashowner/second3DHomework/blob/master/%E5%9B%BE%E7%89%873.PNG)
<br>
![](https://github.com/flashowner/second3DHomework/blob/master/%E5%9B%BE%E7%89%874.PNG)
<br>
![](https://github.com/flashowner/second3DHomework/blob/master/%E5%9B%BE%E7%89%875.PNG)
<br>
