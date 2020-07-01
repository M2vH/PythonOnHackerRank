# A Flow chart

```flow
st=>start: Start:>
e=>end:>
op1=>operation: My Op
sub1=>subroutine: My Sub
cond=>condiiton: Yes
or No?:> link
io=>inputoutput: my catch

st->op1->cond
cond(yes)->io->e
cond(no)->sub1(right)->op1
```