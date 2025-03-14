Test the [mermaid](https://mermaid-js.github.io/mermaid/#/) syntax for making diagrams in Github markdown.

Here is a flowchart:

```mermaid

flowchart TD;
      A[raw data table 1]-->C[(database)];
      B[raw data table 2]-->C;
      X[raw data table 3]-->C;
      C-->D(first analytical step);
      D-->E(second analytical step);
      E-->F(((saved intermediate output)));
      F-->G(third analytical step);
      G-->H(fourth analytical step);
```

And here is some text after. 

Here is a sequence diagram:

```mermaid
sequenceDiagram
    participant A as Ayesha
    participant J as Jill
    A->>J: Hello Jill, how are you?
    activate J
    J->>A: Great!
    deactivate J
```



