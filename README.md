# submoo
Just a dummmy repo. To try submodules

It often happens that while working on one project, you need to use another project from within it. Perhaps it’s a library that a third party developed or that you’re developing separately and using in multiple parent projects. A common issue arises in these scenarios: you want to be able to treat the two projects as separate yet still be able to use one from within the other.


Git allows you to include other Git repositories called submodules into a repository. This allows you to track changes in several repositories via a central one. Submodules are Git repositories nested inside a parent Git repository at a specific path in the parent repository’s working directory. 


Once you have set up the submodules you can update the repository with fetch/pull like you would normally do. To pull everything including the submodules, use the --recurse-submodules and the --remote parameter in the git pull command.
