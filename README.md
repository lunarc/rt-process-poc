# rt-process-poc
Proof-of-concept RT process - ticket handling state diagrams and flow charts

```
# use https://graphviz.org to generate diagrams
# (sudo apt install graphviz)

# generate diagrams from specifications:
#
dot -Tsvg rt_state_diagram.dot -o rt_state_diagram.svg
dot -Tsvg rt_triage_flowchart.dot -o rt_triage_flowchart.svg
dot -Tsvg rt_reopened_flowchart.dot -o rt_reopened_flowchart.svg

# view diagrams:
#
open rt_state_diagram.svg 
open rt_triage_flowchart.svg 
open rt_reopened_flowchart.svg
```

