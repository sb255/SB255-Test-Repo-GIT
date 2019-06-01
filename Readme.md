# README file for the repository!!  </br>
## This file is added by a branch!!! </br>

![alt text](Pictures/Pic.png "Image added") </br>

---------------------------------------------------------------------------------------------


# we will discuss about adding contents to the file
</br>

```
`public class A {
    public static void main(String args[]){
        for(int i=0; i<10; i++){
        `**`System.out.println("Hello, this is a test program!!");`**` 
        }
    }
}`
```


</br>


---------------------------------------------------------------------------------------------

</br>

```
public class BubbleSortAlgo {

	public static void main(String[] args) {
	    
	        
    int[] arr = {2,3,4,1,8,9,5,6,7};
    int bucket = 0; 
    
	    
	    for(int i=0; i<arr.length; i++){
	        for(int j = i+1; j<arr.length; j++){
	            
	            if(arr[i]>arr[j]){
	                bucket = arr[i];
	                arr[i] = arr[j];
	                arr[j] = bucket; 
	            }
	            
	        }
	    }
	    
	    for(int i=0; i<arr.length; i++){
	        System.out.print(arr[i]+" ");
	    }
		
	}

}
```

</br>


---------------------------------------------------------------------------------------------
