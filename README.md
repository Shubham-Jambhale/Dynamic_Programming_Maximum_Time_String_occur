# Dynamic_Programming_Maximum_Time_String_occur

# Question

You are given a string ‘s’ and two characters c1 and c2. You can choose any one of the two
characters and add it to any position in the string to create a new string (exactly once). For
example, if s= ‘cdaabcacd’ and c1= ‘a’ and c2=’d’, you could create a new string ‘cdaabdcacd’
or ‘acdaabcacd’ etc.(note that the character can be added to the beginning or the end of the
string ‘s’). Your job is to find the maximum number of times string ‘c1c2’ can occur as a substring of the modified string using Dynamic Programming. The substring can be contiguous
or non-contiguous (i.e for a string ‘abcdef’ ,‘ab’,’ce’, ‘ef’,’be’ all are valid substrings). Assume all
characters and string s consists of lowercase english letters.
Time complexity constraint: O(n) where n is the length of string s.Space complexity <= O(n)


# Example:

s = "bcedecd", c1 = ‘b’, c2= ‘d’

output: 4

Explanation:
We can form a modified string by adding c1 in s such that the
modified string is “bcbedecd”, the substring ‘c1c2’ (‘bd’) occurs 4 times
in the modified string as: [“bcbedecd”,“bcbedecd”,“bcbedecd”,“bcbedecd”]

Any other modified string will have the occurrence of ‘c1c2’ 4 times or less.
