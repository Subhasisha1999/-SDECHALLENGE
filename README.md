# -SDECHALLENGE
NEW repo. this repo is for solving the dsa sheet question which is design by striver
#include<algorithm>
int findDuplicate(vector<int> &arr,int n){
    sort(arr.begin(),arr.end());
    for(int i=0;i<n-1;i++){
        if(arr[i]==arr[i+1]){
            return arr[i];
        }
    }
    return -1;
}
