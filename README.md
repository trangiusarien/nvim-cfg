---- Navigation ----
Ctrl-o:     Hop to

---- Code -----
gd          Go to definition
gr          Go to references
gi:         Go to implementation
go:         Show hover documentation
gs:         Show signature documentation

Aeral
Alt-a:      Toggle navigation view
Alt-j:      Go to next navigation symbol
Alt-k:      Go to previous navigation symbol

---- Buffer Management ----
Ctrl-x:     Close buffer
Alt-h:      Go to previous buffer
Alt-l:      Go to next buffer
g+h/j/k/l:  Move to split buffer

---- Search ----
Ctrl-f:     Fuzzy search in current buffer
Ctrl-b:     Find existing buffers
Ctrl-p:     Search/replace with Spectre

:%s/foo/bar/g: all in whole file
-> using ctrl-r+" will paste current register

---- Macros ----
qx:         Start recording macro on x, then:
q:          Stop recording, then
@x or @@:   To run macro x or last run
