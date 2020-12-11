# Hello, and welcome to my Work Experience page.

## Work Experience

### Here are a few **quick** facts about me:
1. I've been working since I was 16.
2. My first job was at Wendy's.
3. I currently employ *myself*, kinda.

### **Fun Fact**
While working at the Alumni Center at The University of Missouri, I spoke with the owner of the Rams.

### **Pictures**
This is a picture I've taken:

![alt text](https://github.com/CjInProgress/IT1000/blob/main/085A0236.jpg)

Here's a picture I've taken:

![alt text](https://images.squarespace-cdn.com/content/v1/5ea8f9fcd5913d4f94bbd59e/1599430357148-VDL50YGL0XI6GWQH8KNT/ke17ZwdGBToddI8pDm48kMXRibDYMhUiookWqwUxEZ97gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0luUmcNM2NMBIHLdYyXL-Jww_XBra4mrrAHD6FMA3bNKOBm5vyMDUBjVQdcIrt03OQ/085A1895.jpg?format=500w)

### **Code**
Random algorithm you should know... selectioneSort
``` C
void swap(int *xp, int *yp)  
{  
    int temp = *xp;  
    *xp = *yp;  
    *yp = temp;  
}  

void selectionSort(int arr[], int n)  
{  
    int i, j, min_idx;  

    // One by one move boundary of unsorted subarray  
    for (i = 0; i < n-1; i++)  
    {  
        // Find the minimum element in unsorted array  
        min_idx = i;  
        for (j = i+1; j < n; j++)  
        if (arr[j] < arr[min_idx])  
            min_idx = j;  

        // Swap the found minimum element with the first element  
        swap(&arr[min_idx], &arr[i]);  
    }  
}  
```

### **Other Pages**
# H3
You can visit the other pages by clicking one of the links:
1. [Homepage]()
2. **Work Experience**
3. [My Business]()
4. [How I Spend My Timw]()
5. [Miscellaneous]()
6. [My Photography Page](cjharrisphotgraphy.com)
