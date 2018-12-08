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
5、数组中添加数据 push_back()
```
vector<int> res;
int value;
res.push_back(value);
```
6、数组中弹出数据 pop_back()
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
