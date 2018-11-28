# IQOD_Misc_14

## DO EVERYTHING MANUALLY

```
array = [[4, 5, 6], [2, 3, 4, 5], [7, 5, 3, 4, 1]]
```
Using the array above as an example, create a program that will add all of the integer's in the element's array except for the last integer. Multiple the last integer by the sum of the rest. Print out each set. See the example below.

<hr>
Example:

```
array = [[2, 3], [4, 3, 2]]
iqod(array)
```
Output:

```
6
14
```
You only have 2, then multiple it by 3 to get 6.
You have 4 + 3 which equals 7, then multiple 7 by 2 to get 14.


array = [[4, 5, 6], [2, 3, 4, 5], [7, 5, 3, 4, 1]];


if (array[0]){
  var answer = (array[0][0] + array[0][1])*array[0][2];
  console.log(answer);
};

if (array[1]){
  var answer = (array[1][0] + array[1][1] + array[1][2])*array[1][3];
  console.log(answer);
};

if (array[2]){
  var answer = (array[2][0] + array[2][1] + array[2][2]  + array[2][3])*array[2][4];
  console.log(answer);
};
