// search_item
//to search an item in an array 
#include<stdio.h>
int main(){
	int i,n;
	int index;
	printf("enter a number to search");
	scanf("%d",&n);
	int a[10]={2,4,5,7,6,3,1,9,8,0};
	for(i=0;i<n;i++){
		if(a[i]==n){
			index=i;
		}
	}
	if(index==10){
		printf("element not found");
	}
	else{
		printf("searched element is in index=%d",index);
	}
	return 0;
}
