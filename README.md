# CircleCiNestedWorkflows

Experimenting w CircleCi workflows - specifically nesting them and seeing whether they run sequentially or concurrently - this will make a big difference in whether nesting them is useful at all 

- They run concurrently. Meaning it's not possible to setup workflows within a workflow that depend on each other's output. 
