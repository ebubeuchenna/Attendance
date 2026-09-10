# 1. Separate the products



.git is where Git keeps the information for a local repository.

A hosting service keeps repositories in place so people can share and work together.



2. ### Trace the comparisons
After first commit:
HEAD = Index = Working tree
After editing:
HEAD = Index ~ Working tree13
After staging:
HEAD ~ Index ~ Working tree
After second commit:
HEAD = Index ~ Working tree

The working file stays there because it does not delete your files.

3. Read porcelain status

The first column is for the index.

The second column is for the place you are exactly.

M means the file changed but is not edited

M means the file is edited

it cannot be given without an acual file.

4. ### Trace objects and refs

HEAD/ref - commit - tree - blob

Tag ref - annotated tag object -commit

Lightweight tag ref - commit

A blob stores filenot to delete.

A tree keeps track of files and your location.

A commit records a project state.

A tag gives a name to an object.

A lightweight tag does not have a tag object.


5. ### Bound the evidence

Temporary repository used its observed object format — Supported

YAML was not executed — Supported

A human identity was authenticated — Unsupported

History exists on another device — Unsupported

Remote collaboration works — Unsupported

All objects exist in every clone — Unsupported



6. ### Adversarial extension

Add a wrong statement to the test.

“A lightweight tag is a tag object.”

The checker should reject it because it is false.

The correct answers stay not edited, so the correct answer is not changed.

Retrieval

Two status columns:

First = saved to Git
Second = changed file

Four objects:

Blob
Tree
Commit
Tag

Two tags:

Annotated
Lightweight

Two limits:

Cannot prove another computer has the file.
Cannot show it is  sharing works.