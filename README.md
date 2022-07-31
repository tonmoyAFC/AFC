# AFC
notjing
n = int(input("Enter the maximum number = "))
ave = 0
total = 0
for i in range(1, n+1):
       print("{0}".format(i))
       total = total+i

print("The  sum of numbers from of 1 to {0} is = {1}".format(i,total))
ave = total / n
print("The average of the sum from number 1 to ",n,  "is", ave)



/// becrowd -38 
#include <stdio.h>
 
int main() {
    int x, y;
    scanf("%d %d",&x,&y);
    float price = 0;
    if (x == 1){
        price = (float) (y*4);
    }
    else if (x == 2){
        price = (float) (y*4.50);
    }
    else if (x == 3){
        price = (float) (y*5);
    }
    else if (x == 4){
        price = (float) (y*2);
    }
    else if (x == 5){
        price = (float) (y*1.5);
    }
    
    printf("Total: R$ %.2f\n",price);
    
   
   
    return 0;
}


