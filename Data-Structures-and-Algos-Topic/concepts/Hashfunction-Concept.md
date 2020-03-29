# concept_name
Hashing


# Hashing Step 1

## name
Hash Functions

## md_content
```
A hash function is a necesity when working with Hash tables. 
The purpose of the hash function is to take in an input of any sized-length and convert it to a fixed index value. 
This implies that no matter how big the input, the hashfunction should be able to take that input and convert it to a **Hash Value**. 

When creating a hash function, there are several aspects we want to keep in mind. 
```

# Hashing Step 2

## name
Producing Appropriate Hash Values

## md_content
```
 Every Hash Value produced should be unique. 
  What this means is that two different inputs should always produce two different Hash Values.
  This limits **collisions** which is very important if we want our HashTable to be useful.
```
  
# Hashing Step 3

## name
Input = Same Hash Value

## md_content
```
The same input should always produce the same Hash Value. 
If we input a string, we want to be getting a consistent Hash Value. If we get inconsistent Hash Values, this essentially deems our Hashtable ineffective .
```
  
# Hashing Step 4

## name
Time Complexity for Hashing

# md_content
```

The time it takes for our Hash function to produce Hash Values
We need to be mindful of what time our Hash function works under. The smaller our O(n) time is, the better.
```
