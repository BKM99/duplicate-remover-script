# duplicate-remover-script
A simple command line tool to remove or count duplicate files based on MD5 hash.

Note: This script will DELETE the duplicate files based on the MD5 hash from the given directory if the "del" argument is passed. 

# How to use:

This script takes two arguments, an action and the path to the dataset. 

action = ["del", "count"]

datapath = your/path/to/dataset

# Example:

python3 count your/path/to/dataset

or 

python3 del your/path/to/dataset

