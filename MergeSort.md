# Merge Sort Project

**[16,21,11,8,12,22]** -> Merge Sort

- Write the stages of the above array according to the sort type.
- Write the Big-O notation.
---
- Merge sort method splits a list into parts at each step until only one element remains. After dividing, it presents it to us sequentially.

* **[16,21,11,8,12,22]**
* **[16,21,11]** , **[8,12,22]**
* **[16]** , **[21,11]** , **[8,12]** , **[22]**
* **[16]** , **[21]** , **[11]** , **[8]** , **[12]** , **[22]**
* **[16,21]** , **[8,11]** , **[12,22]**
* **[8,11,16,21]** , **[12,22]**
* **[8,11,12,16,21,22]** 
---
* If a list have n member it cost 2**x=n and big o notation is logn.
* Our list has 6 elements and our big o notation is log6.