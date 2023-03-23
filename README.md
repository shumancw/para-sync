# para-sync
Wrapper for rsync to allow for parallel processing

EXAMPLE:
>./para-sync 10 -avh /path/to/source/ /path/to/destination/ --delete

This will run rsync in parallel with 10 threads, using the specified flags and modifiers.
