# 基础
```c++
std::pair<int, int> P;
```
## 容器
### 栈 stack
```c++
std::stack<int> S;
S.top();  //返回栈顶元素
S.empty();
S.push(x);
S.pop();  //弹出栈顶元素
S.size();
```
### 队列 queue
```c++
std::queue<int> Q;
Q.empty();
Q.front();  //返回队列头部元素
Q.back();
Q.pop();  //弹出队列头部元素
Q.push(x);
Q.size();t
```
### 二叉堆 priority queue
```c++
std::priority_queue<int> big_heap;  //默认构造是最大堆
std::priority_queue<int， std:vector<int>, std::greater<int>> small_heap2;  //最小堆
std::priority_queue<int， std:vector<int>, std::less<int>> big_heap2;  //最大堆
big_heap.empty();
big_heap.pop();  // 弹出堆顶元素
big_heap.push(x);
big_heap.top();  // 返回堆顶元素
big_heap.size();
```
### 字符串 string
```c++
std::string str;
str.append(1, '0'+2);  // 添加一个字符'2'
```