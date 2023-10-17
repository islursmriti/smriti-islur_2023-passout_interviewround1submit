# smriti-islur_2023-passout_interviewround1submit
## qs-1
Find minimum swaps(S) required to get all 1s and 0s in the input array together.
Input:
● N = number of elements in the array.
● Array of elements with value equal to either 0 or 1.
Output:
● S = Minimum swaps to sort the array (ascending/descending)
Example 1:
Input:
10
1 0 0 1 1 0 1 1 1 0
Output:
3
Example 2:
Input:
10
0 0 0 1 0 0 0 0 0 0
Output:
1

## qs-2
A snail wishes to reach a water shore. To do this it must cross a wall which is 30
feet high. It has a time limit of 30 hours to reach atop the wall. The time starts as soon
as it starts climbing the wall. However, he faces a problem while climbing. Every hour it
climbs the wall 3 feet up, it slides down 2 feet. This occurs every hour. Writr a code on
how many hours will it take for the snail to reach atop the wall?

Inputs:
● H - Height of the wall in feet.
● U - per hour climbing speed. (Feet/hour)
● S - feets slided per hour. (Feat)
Outputs:
● O - Hours to be taken by the snail to reach and stay at the top. (Not just to touch
it)
Assume: S < U.

Example:
Input:
30
3
2
Output:
28

## qs-3
Develop a program to process a large text file containing millions of lines, each
containing semicolon-separated key-value pairs. The goal is to extract and
concatenate specific values based on input keys, find unique concatenated strings,
and count their occurrences throughout the file.

You have been given a text file (data.txt) containing millions of lines, with each line
having the following format:
key1=value1;key2=value2;key3=value3;...;keyN=valueN
The keys are of integer data type, and the values are alphanumeric characters. The key
value pairs are semicolon separated.
The code should accomplish the following:
1. Read the data.txt file.
2. Extract specific values from each line’s key value pairs based on the list of input
keys provided.
3. Concatenate the extracted values for each line in the order specified by the input
keys, using '|' as the concatenator.
4. Track and count the found keys per line.
5. Print the concatenated string and the count.

Input:
● The path to the input data file (data.txt).
● A list of input keys in sequential order, e.g., [5, 10, 17, 23]. These keys represent
the desired order of values to concatenate.
Output:
(for each input text file’s line:)
● Concatenated String: Values concatenated into a string.
● Count: Number of occurrences of input keys in the line.

Example:
Input:
5, 7, 10, 23
Output:
Concatenated String: John|30|2023-10-12 08:30:45, Count: 3
Concatenated String:, Count: 0
Concatenated String:Chicago, Count: 1
