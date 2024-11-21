# APCS - Lab07 - NoNullArrayList
You are implementing two classes:

# NoNullArrayList

```
public class NoNullArrayList<T> extends ArrayList<T>{

}
```

### 2 Constructors: 

`public NoNullArrayList()`

`public NoNullArrayList(int initialCapacity)`

### 3 Overrides:

  `public T set(int index, T value)`
  
  `public boolean add(T value)`
  
  `public void add(int index, T value)`

# OrderedArrayList

```
public class OrderedArrayList<T extends Comparable<T>> extends NoNullArrayList<T>{
}`
```

### 2 Constructors: 

`public OrderedArrayList()`

`public OrderedArrayList(int initialCapacity)`

### New Method:
  
```
/*return the index that the value should be placed
 *when inserting into the OrderedArrayList.
 */
private int whereToPlace(T value){ 
}
```

### 3 Overrides:

  `public T set(int index, T value)`
  
  `public boolean add( T value)`
  
  `public void add(int index,T value)`
