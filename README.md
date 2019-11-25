# Primtive-Roots

#include<iostream>
#include<vector>
#include<cstring>
using namespace std;


int main()
{
   int o,j,res=1;
   int i,n=6,p;
   for(i=1;i<10;i++)
   {
       o=i;
    j=10;
   while(j!=0)
   {
       res*=o;
       p=res;
       if(res>11)
        {
            while(p>11){
                p-=10;
                p--;

            }
          res=p;
        }


       j--;
       cout<<"  "<<res;
   }
   cout<<endl;

   }


}
