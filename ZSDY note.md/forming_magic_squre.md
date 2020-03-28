## 模拟做题
    by https://www.hackerrank.com/challenges/magic-square-forming/problem
## 代码
    #include<iostream>
    #include<algorithm>//有很多好用的函数

    using namespace std;

    int aj[8][9]={{8,1,6,3,5,7,4,9,2}, {4,3,8,9,5,1,2,7,6}, {2,9,4,7,5,3,6,1,8},
                    {6,7,2,1,5,9,8,3,4},{6,1,8,7,5,3,2,9,4},{8,3,4,1,5,9,6,7,2},
                    {4,9,2,3,5,7,8,1,6},{2,7,6,9,5,1,4,3,8}};
    //直接模拟，避免计算
    /**************
    5在中央
    2，4，6，8在四角
    利用反转
    ***************/


    int main()
    {
        int a[9];
        for(int i=0;i<9;i++){
            cin>>a[i];
        }
        
        int s=100000;
        
        //直接计算更省
        for(int i=0;i<8;i++){
            int j=0;
            for(int k=0;k<9;k++){
                j+=abs(a[k]-aj[i][k]);
            }
            if(j<s) s=j;
            
        }
        
    } 
    