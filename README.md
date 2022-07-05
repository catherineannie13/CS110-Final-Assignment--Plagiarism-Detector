# CS110-Final-Assignment--Plagiarism-Detector

The plagiarism detector takes 2 strings (X and Y) and compares substrings of length k (parameter) to find matches.\
It first stores substrings of X in a hash table using rolling hashing to compute hash values.\
Collisions are managed using double hashing.\
Substrings of Y are then searched for in the hash table, again using rolling hashing to compute hash values, and double hashing to manage collisions.\
The overall program returns the indexes in the strings X and Y at which we would find matching substrings of length k.
