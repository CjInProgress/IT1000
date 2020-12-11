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

![alt text](https://github.com/CjInProgress/IT1000/blob/main/IMG_1107.jpg)

Here's a picture I've taken:

![alt text](https://images.squarespace-cdn.com/content/v1/5ea8f9fcd5913d4f94bbd59e/1601965590212-T23E9TNLP418ARQ3XSB3/ke17ZwdGBToddI8pDm48kMXRibDYMhUiookWqwUxEZ97gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0luUmcNM2NMBIHLdYyXL-Jww_XBra4mrrAHD6FMA3bNKOBm5vyMDUBjVQdcIrt03OQ/085A0838.jpg?format=500w)

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
2. [Work Experience](https://github.com/CjInProgress/IT1000/blob/main/2WorkExperience.md)
3. [My Business](https://github.com/CjInProgress/IT1000/blob/main/3mybusiness.md)
4. [How I Spend My Timw](https://github.com/CjInProgress/IT1000/blob/main/4Leisure.md)
5. [Miscellaneous](https://github.com/CjInProgress/IT1000/blob/main/5Miscellaneous.md)
6. [My Photography Page](cjharrisphotgraphy.com)
