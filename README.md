# Fibonacci-in-C-using-function

The Code:

```
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
int printfibonacci(int a,int b){
        int ret;
        ret=a+b;
        return ret;
}

void main(){
        int i,x,y,z;
        x=1;
        y=1;
        printf("%d %d ",x,y);
        for(i=1;i<=10;i++){
                z = printfibonacci(x,y);
                printf("%d ",z);
                x=y;
                y=z;

        }
}
```

The output:

![image](https://user-images.githubusercontent.com/124895858/229041332-124b3957-5e0e-4f19-b272-9ecf2e314ef7.png)
