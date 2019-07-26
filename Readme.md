## README file for the repository!  </br>

![alt text](Pictures/Pic.png "Image added") </br>

---------------------------------------------------------------------------------------------

<h1>Header 1</h1>
<h2>Header 2</h2>
<h3>Header 3</h3>

</br>

```java
public class A {
    public static void main(String args[]){
        for(int i=0; i<10; i++){
            System.out.println("Hello, this is a test program!!");
        }
    }
}
```


</br>


---------------------------------------------------------------------------------------------

</br>

```java
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

## Runtime efficiency of the sorting methods!!

| Sorting Method of Algorithm | Best Case     | Avg case        | Worst Case    |
| :---: | :--- | :---: | :---:  |
| Bubble Sort Algorithm | [Program]() | [Program]() | [Program]() |
| Merge Sort Algorithm | [Program]() | [Program]() | [Program]() |


---------------------------------------------------------------------------------------------

## Time Complexity:

Sorting Algorithm | Best Case | Worst Case | Average Case
--- | --- | --- | ---
Linear Search| | |


---------------------------------------------------------------------------------------------
