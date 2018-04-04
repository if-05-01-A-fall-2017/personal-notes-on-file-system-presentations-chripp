# Personal notes Pfleger Christoph #

## Group Jusic ##
Well presented
Because of the linked-list-system it would be a bit slow
## Group Kepplinger ##
Decent ideas, though they didn't think about what happens if the content list gets too long for a single block
## Group Fallmann ##
Poorly explained
Use a linked-list
## Group Danninger ##
pretty much the same as Kepplinger's
## Group Friesenecker ##
good presentation
pretty much the same as Kepplinger's, however they only save a single free block-adress which creates problems
In the presentation, FriesenechKer acknowleged the problem of only saving one address without being asked about it which 
indicates that they became aware of the problem pretty late and didn't have time to change the presentation
## generally ##
Every group saved the free block-addresses in a list
When creating a file or making a file bigger they delete the address from the list
When deleting a file or making a file smaller they add the address to the list
Except those who used linked-lists everybody used metadata-blocks, which contain metadata and a list of addresses to data-blocks
