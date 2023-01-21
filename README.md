# konvektion

## Commit messages

Prefix commit messages with emoji code according to type of the change that commit brings.

This makes it easier to visually identify commits when checking history, and helps to be mindful when commiting.

### :feet: changes to behavior 

Code: `:feet:`  
Alternatives: :black_cat: :cat2:

Apply when
- introducing new capabilities
- fixing behavior of existing functionality
- removing a part of existing functionality

E.g. _deleted an endpoint, with related route handler, tests, etc._

### :axe: changes to structure

Code: `:axe:`  
Alternatives: :hammer: :carpentry_saw:

E.g. _deleted some structural things. everything works the same, the program doesnt seem to complain and slava bogu_

### :golf: testing and specification

Code: `:golf:`  

When setting test cases for production code

### ❔ other changes

Besides :feet: :axe: and :golf: defined above, where we deal with the part of code that goes to production, there are other types of changes where we deal with documentation, or CI processes, etc. 

Then use emoji's based on situation and your preference.
