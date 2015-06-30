# check_metalink
A script to check metalink contents.

Please run ./check_metalink --help for an overview of all arguments.

More documentation will follow.


## Modes of operation

The script has two modes of operation:

- It can check the master mirrors if the metalink content is up-to-date with master mirror contents.
For this, use the --check-master flag.

- It can check the mirrors provided in the metalink whether they have a valid repomd.
For this, use the --check-mirrors flag.
