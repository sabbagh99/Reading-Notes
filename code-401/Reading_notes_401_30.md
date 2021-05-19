# Hash Tables

##  Terminology :

### We need to know this terminology in order to understand hash tabel.

* #### Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

* #### Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

* #### Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

### The main idea of using hash table is to store data using keys and values and it's work by converting the key for an index and save it in array and when we want to find this it we will look for his index.
 

### And we have this methods in hash table :

#### 1. `Add()` : first we will convert it to a number then we will check if this number exist in the array if not we will add it

#### 2. `Find()` : we will start looking for the index location 

#### 3. `Contains()` : this method will take a key as a parameter  and it will returen boolen if it exsit or not

#### 4. `GetHash()` :  will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.

