# Sublime Notes Syntax
A syntax for notetaking in sublime text

See general overview http://www.sublimetext.com/docs/3/syntax.html
For a more list of scopes, see: https://www.sublimetext.com/docs/3/scope_naming.html

Files should have a .note or .notes extension. Place this file \Packages\User\ directory,
on windows it is located in C\users\<you>\AppData\Roaming\Sublime Text 3\

#### Section highlighting (case sensitive) in green by default
  - ;;

#### Important words (case sensitive) in pink by default
  - Note
  - NOTE
  - Notes
  - NOTES
  - Recall
  - RECALL

#### Grey "Comment-esque" line that blends in by default
  - == <stuff>

#### Emphasized Line that is in blue italics by default
  - >
 
#### Inline Equation yellow/tan line with equalities/etc as purple. Note it uses the grave key, `
 - ` <stuff> `


#### Highlighted line
 - !!! <stuff>

#### Special case highlighted words (case sensitive)
 - FILL                  pink by default
 - POPULATE              pink by default 
 - Section               green by default
