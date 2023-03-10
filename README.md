# -## HJ24（因为是先递增再递减，所以递减子序列右右）

//非连续递增

for(int i=1;i<vec.size();i++){

​      for(int j=0;j<i;j++){

​        if(vec[i]>vec[j]){

​          dp[i]=max(dp[i],dp[j]+1);

​        }

​      }

​    }



//非连续递减

​    for(int i=vec.size()-1;i>0;i--){

​      for(int j=i;j<vec.size();j++){

​        if(vec[j]<vec[i]){

​          dp1[i]=max(dp1[i],dp1[j]+1);

​        }

​      }

​    }



## 字符串压缩（双指针）

https://www.nowcoder.com/practice/44da6966beb449d383f62b12e8df6317?tpId=131&tqId=33837&ru=/exam/oj



## 接雨水（单调栈）

https://www.nowcoder.com/practice/769e5e6c3ebf42a49cfb555ebf4a90e2?tpId=125&tqId=33749&ru=/exam/oj



## 俄罗斯套娃信封（二维降一维，递增子序列）

https://www.nowcoder.com/practice/25fe1fc89c4c4e82bbc63df04bc6ca30



## 743.网络延迟时间（迪杰斯特拉算法）

https://leetcode.cn/problems/network-delay-time/



## 151. 反转字符串中的单词（快慢指针，先去空格再反转）

https://leetcode.cn/problems/reverse-words-in-a-string/



## 79.单词搜索（回溯）

https://leetcode.cn/problems/word-search/
