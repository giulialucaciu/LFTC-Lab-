

THE PROBLEM:

#include<iostream> 
using namespace std; 
int main() {
int i, sum;
int v[3] = {1,2,3}; 
i = 0;
sum = 0;
if ( i >= 0 ) {
i = i + 1; 
while ( i <= v[3] ) {
sum = sum + v[i]; 
i = i + 1; }
} 
cout<< " sum of the array without the first element is: " <<sum; 
return 0;
}

-------------------------

GIT LINK:
https://github.com/giulialucaciu/LFTC-Lab-

I uploaded two screenwhots of my result in the Temrinal.
          
-------------------------

TERMINAL:
~~~~~~~ Symbol table ~~~~~~~
 include  0
 iostream  1
 using  2
 namespace  3
 std  4
 main  5
 i  6
 sum  7
 v  8
 3  9
 1  10
 2  11
 0  12
 " sum of the array without the first element is: "  13
~~~~~~~ End ST ~~~~~~~

~~~~~~~ Program internal form ~~~~~~~
 #  -1 
 include  0 
 <  -1 
 iostream  1 
 >  -1 
 using  2 
 namespace  3 
 std  4 
 ;  -1 
 int  -1 
 main  5 
 (  -1 
 )  -1 
 {  -1 
 int  -1 
 i  6 
 ,  -1 
 sum  7 
 ;  -1 
 int  -1 
 v  8 
 [  -1 
 3  9 
 ]  -1 
 =  -1 
 {  -1 
 1  10 
 ,  -1 
 2  11 
 ,  -1 
 3  9 
 }  -1 
 ;  -1 
 i  6 
 =  -1 
 0  12 
 ;  -1 
 sum  7 
 =  -1 
 0  12 
 ;  -1 
 if  -1 
 (  -1 
 i  6 
 >=  -1 
 0  12 
 )  -1 
 {  -1 
 i  6 
 =  -1 
 i  6 
 +  -1 
 1  10 
 ;  -1 
 while  -1 
 (  -1 
 i  6 
 <=  -1 
 v  8 
 [  -1 
 3  9 
 ]  -1 
 )  -1 
 {  -1 
 sum  7 
 =  -1 
 sum  7 
 +  -1 
 v  8 
 [  -1 
 i  6 
 ]  -1 
 ;  -1 
 i  6 
 =  -1 
 i  6 
 +  -1 
 1  10 
 ;  -1 
 }  -1 
 }  -1 
 cout  -1 
 <<  -1 
 " sum of the array without the first element is: "  13 
 <<  -1 
 sum  7 
 ;  -1 
 return  -1 
 0  12 
 ;  -1 
 }  -1 
~~~~~~~ End PIF ~~~~~~~
