# Hello, and welcome to my Markdown home page.

## Home

### Here are a few **quick** facts about me:
1. I was born in Memphis, TN
2. I moved to St. Louis in 8th grade.
3. *Cereal* used to be my favorite food.

### **Fun Fact**
I have a business! I'm a professional photographer/videographer in the Midwest!
On every page, there will be a picture that I've taken.

### **Pictures**
This is what I look like:
![alt text][picture]

Here's a picture I've taken:
!![alt text][picture2]

[picture]: (https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

[picture]: (https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

### **Code**
Random algorithm you should know... bubbleSort
``` C
// C++ program for implementation of Bubble sort  
#include <bits/stdc++.h>
using namespace std;

void swap(int *xp, int *yp)  
{  
    int temp = *xp;  
    *xp = *yp;  
    *yp = temp;  
}  

// A function to implement bubble sort  
void bubbleSort(int arr[], int n)  
{  
    int i, j;  
    for (i = 0; i < n-1; i++)      

    // Last i elements are already in place  
    for (j = 0; j < n-i-1; j++)  
        if (arr[j] > arr[j+1])  
            swap(&arr[j], &arr[j+1]);  
}  

/* Function to print an array */
void printArray(int arr[], int size)  
{  
    int i;  
    for (i = 0; i < size; i++)  
        cout << arr[i] << " ";  
    cout << endl;  
}
```

### **Other Pages**
You can visit the other pages by clicking one of the links:
1. **Homepage**
2. [Work Experience]()
3. [My Business]()
4. [How I Spend My Timw]()
5. [Miscellaneous]()
6. [My Photography Page](cjharrisphotgraphy.com)
