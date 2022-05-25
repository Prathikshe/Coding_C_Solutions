# Coding_C_Solutions
# [1]Check Anagram or Not
### Given a string S and a non-empty string P, find string S is Anagram of P.
Check if the string S can be equal to P when charectors in P are rearranged

Strings consists of lowercase English letters only and the length of both strings S and P will not be larger than 20,100.


## Example 1:

### Input:
* Enter first string S: creative

* Enter first string P: reactive
### Output:
* Strings are Anagram

### Explanation:
* Length of String S is equal to Length of String P  

 * "creative" is rearranged and found "reactive" 

## Example 2:

### Input:
* Enter first string S: angel

* Enter first string P: glean
### Output:
* Strings are Anagram

### Explanation:
* Length of String S is equal to Length of String P  
 * "angel" is rearranged and found "glean"
 
## Example 3:

### Input:
* Enter first string S: car

* Enter first string P: cat
### Output:
* Strings are not Anagram

### Explanation:
* Length of String S is equal to Length of String P  
 * "car" is rearranged and "cat" is not found 

## Find the solution in file "A1"

# [2] Palindromes in Anagram
### Given a string S list the palindromes generated when string S is rearranged.
Re-arrange the string with all permutation and print strings which are palendrome.
palendrome : Reverse of a string equal to its original string.

Strings consists of lowercase English letters only and the length of both strings S and P will not be larger than 20,100.

## Example 1:

### Input:
* Enter a string S: abb
### Output:
* All palindrome strings from permutations of the string are:

      bab

### Explanation:
* List of permutation from given string found is ["abb","bba","bab"]
* palindrome strings from permutations "bab"

## Example 2:

### Input:
* Enter a string S: seels 
### Output:
* All palindrome strings from permutations of the string are:

     seles

     eslse

### Explanation:
* List of permutation from given string found is ["seels","seesl","seles","selse","sesle", ... ,"eessl","eslse"]
* palindrome strings from permutations "seles" and "eslse"

## Find the solution in file "A2"


# [3] Rotate array
### Given a array of length "N" Rotate the array with "K"th position and display the elements in odd positions.

Read the input "N" (Number of elements in array) and "K" (Number of positions to be rotated).
Read "N" number of elements in array rotate it by "K"th position and print the element in odd positions after rotation.

Note:
* All the elements in array should be integers.
* 'K' value can be grater than 'N'.

## Example 1:

### Input:
* Enter Number of element N :
  6
* Enter rotate position K :
  2
* Input 6 elements in the array :
  1 2 3 4 5 7
### Output:
* Rotated Array with odd positions is:
  3 5 1 


### Explanation:
* 'N'= 6 , 'K' = 2 , array = [1,2,3,4,5,7]
* Rotate by 2 positions rotated array = [3,4,5,7,1,2]
* Odd positions elements in array = 3 5 1

## Example 2:

### Input:
* Enter Number of element N :
  4
* Enter rotate position K :
  7
* Input 6 elements in the array :
  4 5 7 6
### Output:
* Rotated Array with odd positions is:
  6 5
  
### Explanation:
* 'N'= 4 , 'K' = 7 , array = [4,5,7,6]
* Rotate by 2 positions rotated array = [7,6,4,5]
* Odd positions elements in array = 6 5

## Find the solution in file "A3"
M!LI<EY50U
