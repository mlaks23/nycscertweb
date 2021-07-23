# nycscertweb

## Programming in Java

**Codes for Games**

[Nim](https://github.com/hunter-teacher-cert/work_csci70900-mlaks23/blob/master/1/Nim.java)

[Game of Life](https://github.com/hunter-teacher-cert/work_csci70900-mlaks23/blob/master/3/Cgol.java)

![cgol](https://user-images.githubusercontent.com/84258308/126729807-4ee4f364-4d77-42d0-a5d1-d2bb62e11e78.jpg)




## Data Structures

[SortDemo](https://github.com/hunter-teacher-cert/work_csci70900-mlaks23/blob/master/ds/sort1/SortDemo.java)


`**Binary Search Code**

public int binarySearch(int value) {

	     int lowerIndex = 0;
	     int upperIndex =  data.size() - 1;
	     int middleIndex = data.size()/2;

	   while (lowerIndex <= upperIndex) {
       if (value < data.get(middleIndex)) {
         upperIndex = middleIndex - 1;
         middleIndex = (upperIndex + lowerIndex)/2;
       } else if (value > data.get(middleIndex)) {
         lowerIndex = middleIndex + 1;
         middleIndex = (upperIndex + lowerIndex)/2;
       } else if (value == data.get(middleIndex)) {
         System.out.println("Your value " + value + " is in the data set. ");
         return value;
       }
	    }

    System.out.println ("Your value " + value + " is not in the data set. ");
	  return -1; 
      }`

[Linked Lists](https://github.com/hunter-teacher-cert/work_csci70900-mlaks23/blob/master/ds/lists/Llist.java)


## Methods 1

**Sample Lesson Plans**

[NetLogo Introductory Lesson](https://github.com/hunter-teacher-cert/work_csci70900-mlaks23/blob/master/meth1/05_netlogo.md)

[Unplugged Lesson](https://github.com/hunter-teacher-cert/work_csci70900-mlaks23/blob/master/meth1/06_unplugged.md)
