# FORKED
This has been forked from nathan-v's original repo. You can find the older readme details including license information under README_prefork.md

# Breaking Changes
Main changes enable the ability to login to all AWS accounts that OKTA has listed at once, instructions have been added to prompts as needed. 
This flow can easily be reached by running the baseline 'aws_okta_keyman' command.

Currently, this breaks reup functionality, this will hopefully be fixed in the future.

# TODOs
-Add caching to re-use previously selected roles for an account
-Fix reup functionality