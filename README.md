# ***🌟Give Star If you find this helpful :)🌟***

# 1. ***Find Unique***
### Code:Find Unique
public class Solution{  

    public static int findUnique(int[] arr){
		int temp=0;
        for (int i = 0; i < arr.length; i++) {
            int cnt = 0;
            for (int j = 0; j < arr.length; j++) {
                if (arr[j] == arr[i])
                    cnt++;
            }
            if (cnt == 1) {
                temp = arr[i];
                break;
            }
        }
        return temp;
    }
    
}

# 2. ***Find Duplicate***
### Code:Find Duplicate
public class Solution{  

    public static int findUnique(int[] arr){
		int temp=0;
        for (int i = 0; i < arr.length; i++) {
            int cnt = 0;
            for (int j = 0; j < arr.length; j++) {
                if (arr[j] == arr[i])
                    cnt++;
            }
            if (cnt == 1) {
                temp = arr[i];
                break;
            }
        }
        return temp;
    }
    
}

# 3. ***Intersection of Two Arrays II***
### Code:Intersection of Two Arrays II
public class Solution{  
    
    public static void intersections(int arr1[], int arr2[]) {
    	 for (int i = 0; i < arr1.length; i++) {
            for (int j = 0; j < arr2.length; j++) {
                if (arr1[i] == arr2[j]) {
                    System.out.print(arr1[i]+" ");
                    arr2[j] = -10000;
                    break;
                }
            }
        }
    }
    
}

# 4. ***Pair Sum***
### Code:Pair Sum
public class Solution {  

    public static int pairSum(int arr[], int x) {
        int value=0;
    	for (int i = 0; i < arr.length; i++) {
            for (int j = i + 1; j < arr.length; j++) {
                if (arr[i] + arr[j] == x)
                    value = value + 1;
            }
        }
        return value;
    }
    
}

# 5. ***Triplet sum***
### Code:Triplet sum
public class Solution {
    
    public static int findTriplet(int[] arr, int x) {
        int value=0;
    	for (int i = 0; i < arr.length; i++) {
            for (int j = i + 1; j < arr.length; j++) {
                for (int k = j + 1; k < arr.length; k++)
                    if (arr[i] + arr[j] + arr[k] == x)
                        value = value + 1;
            }
        }
        return value;
    }

}

# 6. ***Sort 0 1***
### Code:Sort 0 1
public class Solution {  

    public static void sortZeroesAndOne(int[] arr) {
    	  int sum=0;
                for(int i=0;i<arr.length;i++)
                {sum=sum+arr[i];}
                for(int i=0;i<(arr.length-sum);i++)
                {arr[i]=0;}
                for(int i=(arr.length-sum);i<arr.length;i++)
                {arr[i]=1;}
    }
    
}

# ***🌟Give Star If you find this helpful :)🌟***
