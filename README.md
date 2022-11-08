### Definition and Usage of slice () method
* The slice() method returns selected elements in an array, as a new array.
* The slice() method selects from a given start, up to a (not inclusive) given end.
* The slice() method does not change the original array.

### Syntax
array.slice(start, end)

### Parameters
* start
  * Optional. 
  * Start position Default is 0. 
  * Negative numbers select from the end of the array.
* end 
  * Optional.
  * End position. Default is last element.
  * Negative numbers select from the end of the array.

### Return Value
A new array containing the selected elements.

~~~
<!DOCTYPE html>
<html>
<body>

<p id="demo"></p>

<script>
  const fruits = ["Banana", "Orange", "Lemon", "Apple", "Mango"];
  const citrus = fruits.slice(1, 3);

  document.getElementById("demo").innerHTML = citrus;
</script>

</body>
</html>
~~~

### Output: Orange, Lemon

Example: https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_slice_array2

