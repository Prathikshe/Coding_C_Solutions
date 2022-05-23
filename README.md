# Coding_C_Solutions
## [1]Check Anagram or Not
Given a string S and a non-empty string P, find string S is Anagram of P.
Check if the string S can be equal to P when charectors in P are rearranged

Strings consists of lowercase English letters only and the length of both strings S and P will not be larger than 20,100.


# Example 1:

## Input:
Enter first string S: creative
Enter first string P: reactive
## Output:
Strings are Anagram

Explanation:
Length of String S is equal to Length of String P  
 "creative" is rearranged and found "reactive" 

# Example 2:

## Input:
Enter first string S: angel
Enter first string P: glean
## Output:
Strings are Anagram

Explanation:
Length of String S is equal to Length of String P  
 "angel" is rearranged and found "glean"
 
 # Example 3:

## Input:
Enter first string S: car
Enter first string P: cat
## Output:
Strings are not Anagram

Explanation:
Length of String S is equal to Length of String P  
 "car" is rearranged and "cat" is not found 

## Find the solution in file "A1"

## [2] Palindromes in Anagram
Given a string S list the palindromes generated when string S is rearranged.
Re-arrange the string with all permutation and print strings which are palendrome.
palendrome : Reverse of a string equal to its original string.

Strings consists of lowercase English letters only and the length of both strings S and P will not be larger than 20,100.

# Example 1:

## Input:
Enter a string S: abb
## Output:
All palindrome strings from permutations of the string are:
bab

Explanation:
List of permutation from given string found is ["abb","bba","bab"]
palindrome strings from permutations "bab"

# Example 2:

## Input:
Enter a string S: seels 
## Output:
All palindrome strings from permutations of the string are:
seles
eslse

Explanation:
List of permutation from given string found is ["seels","seesl","seles","selse","sesle", ... ,"eessl","eslse"]
palindrome strings from permutations "seles" and "eslse"

## Find the solution in file "A2"
