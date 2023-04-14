In computing, a hash table (hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. During lookup, the key is hashed and the resulting hash indicates where the corresponding value is stored.


HashTable class implements some of the Python Dictionary methods, such as:
 
    • hash(key: str) - a function that should figure out where to store the key-value pair
    • add(key: str, value: any) - adds a new key-value pair usign the hash function
    • get(key: str) - returns the value corresponding to the given key
    • additional "magic" methods, that will make the code in the example work correctrly
