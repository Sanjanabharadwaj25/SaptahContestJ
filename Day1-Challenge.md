## Problem Statement:
Khaleel the youngest coder in the world, he is just 15 months old (when this problem was added), and he has just decided to write his first program.

This program is very simple, the program should be able to read 2 numbers and print the sum of them.

Can you help Khaleel by writing a correct program so that he can use it to check if his program is correct or not?


## Input Format:
Your program will be tested on one or more test cases. The first line of the input will be a single integer T, the number of test cases  
(1 ≤ T ≤ 100). Followed by the test cases, each test case is described in one line which contains 2 integers separated by a  
single space X Y (1 ≤ X,Y ≤ 100). X and Y are the 2 numbers which you should print the sum of them.


## Output Format:
For each test case, print a single line contains a single integer which is the sum of X and Y.


## Sample Input:
5  private:
22 12  
23 12  
1 1  
2 3  
100 100  


## Sample Output:
34  
35  
2  
5  
200
#include<iostream.h>
#include<iomanip.h>
class sum
{
   private:int n;
   public: void getdata();
   void compute();
   void display();
  };
    void sum::getdata()
    {
    cout<<"ENTER NUMBER";
    cin>>n;
    cout<<"ENTER TWO NUMBERS TO ADD";
    cin>>n1>>n2;
    }
     void sum::compute()
     {
     sum=n1+n2;
     }
     void sum::display()
     {
     cout<<n<<endl;
     cout<<n1<<" "<<n2<<endl;
     cout<<sum;
     }
     void main()
     {
     sum s;
     clrscr();
     s.getdata();
     s.compute();
     s.display();
     getch();
     }
     //sanjana j bharadwaj
     //sanjana2002251@gmail.com
     
     
    
     
    
    
