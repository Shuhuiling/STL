# C++  STL
1、字符串的拼接 
```
string A;
string C = A+A;
```
2、字符串的匹配 find() 
```
if(str1.find(str2) != string::npos){
            return true;
        }
        else{
            return false;
        }
```
3、字符串、数组的形参表示 都要加&
```
void TreetoString(string &str)
```
4、整型转化成字符串类型 to_string
```
str = to_string(treenode->val)
```
5、数组中添加数据 push_back()，弹出数据 pop_back()
```
vector<int> res;
int value;
res.push_back(value);
```
6、数组的长度 res.size()    
7、获取数组的最后一个数据 .back()
```
int res=A.back();
       
A.pop_back();
```
8、构建链表的2种方式
```
ListNode* oneNode = new ListNode(0);
```
```
ListNode smallValue(0);
ListNode* left = &smallValue;
```
9、返回链表的头结点
按照8的第二种方式构建：
```
return smallValue.next;(left指向表头结点)
```
10、定义堆栈
```
stack<TreeNode*> stk;
存放二叉树节点类型的堆栈
```
11、报错的关键词
```
assigning 赋值
incompatible 不兼容
take address 取地址
```
12、map
```
map<char,int> mp; char类型到int型的映射
```
13、输入输出
```
#include<iostream>
输入： cin>>ch>>a>>stu[i];
输出：cout<<stu[i]<<","<<a<<endl;
```
14、头文件
```
#include<iostream>
#include<algorithm>
#include<vector>
#include<string>
```
15、sort
```
a[1,2,3,4,5]
左闭右开
sort(a.begin(),a.end(),cmp); // 【0,5)位置排序
*max_element(a,a+5); // 【0,5)位置求max
*min_element(a,a+5);
```
16、动态数组
```
int *p = new int[n];//相当于一个n个int元素的数组，
```
