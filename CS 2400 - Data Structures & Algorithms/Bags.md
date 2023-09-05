The ADT Bag
- Definition
	- a finite collection of objects in no particular order
	- can contain duplicate items
- Possible behaviors
	- get number of items
	- check for empty
	- add and remove objects

```start-multi-column
```
```java
public interface BagInterface<T>
{ // an interface that describes the operations of a bag of objects

  public int getCurrentSize();
  // get the current number of entries in this bag
  // @return the integer number of entries currently in the bag
  
  public boolean isEmtpy();
  // sees whether this bag is empty or not
  // @return True if the bag is empty, or False if not
  
  public boolean add(T newEntry);
  // adds a new entry to this bag
  // @param newEntry; The object to be added as a new entry
  // @return True if the addition is successful, or False if not
  
  public T remove();
  // removes one unspecified entry from this bag, if possible
  // @return Either the removed entry, if the removal was successful, or null
  
  public boolean remove(T anEntry);
  // removes one occurence of a given entry from this bag, if possible
  // @param anEntry; the entry to be removed
  // @return True if the removal was successful, or False if not
  
  public void clear();
  // removes all entries from this bag
  
  public int getFrequencyOf(T anEntry);
  // counts the number of times a given entry appears in this bag
  // @param an Entry; the entry to be counted
  // @return the number of times anEntry appears in the bag
  
  public boolean contains(T anEntry);
  // tests whether this bag contains a given entry
  // @param anEntry; the entry to find
  // @return True if the bag contains anEntry, or False if not
  
  public T[] toArray();
    // retrieves all entries that are in this bag
  // @return A newly allocated array of all the entries in the bag. Note: if the bag is empty, the returned array is empty
}
//end BagInterface
```
=== end-column ===
| Bag                         |
| --------------------------- |
| hi                            |
=== end-multi-column
