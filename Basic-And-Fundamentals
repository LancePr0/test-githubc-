#include <iostream>
#include <algorithm>

using namespace std;

int main() {
    const int maxSize = 10; 
    const int mergeSize = maxSize * 2; 

    int arr1[maxSize]; 
    int arr2[maxSize];   
    
    cout << "Enter 10 elements for the first array: ";
    for (int i = 0; i < maxSize; i++) {
        cin >> arr1[i];
    }
    
    cout << "Enter 10 elements for the second array: ";
    for (int i = 0; i < maxSize; i++) {
        cin >> arr2[i];
    }

    int tempArray[mergeSize]; 

    for (int i = 0; i < maxSize; i++) {
        tempArray[i] = arr1[i];
    }
    for (int i = 0; i < maxSize; i++) {
        tempArray[maxSize + i] = arr2[i];
    }

  
    sort(tempArray, tempArray + mergeSize, greater<int>());

   
    cout << "Merged and sorted array: ";
    for (int i = 0; i < mergeSize; i++) {
        cout << tempArray[i] << " ";
    }
    cout << endl;

    return 0;
}