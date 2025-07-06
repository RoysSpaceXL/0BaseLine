# Basics


```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Bob->>Alice: Hi Alice
    Alice->>Bob: Hi Bob
```    

## diagram 1

```mermaid
sequenceDiagram
    participant A
    participant B
    participant C
    participant D
    A->>B: Query
    B->>C: Forward query
    Note right of C: Thinking
    C->> B: Response
    B->> A: Forward response
    C->> D: Forward Part 2 query```
```

## diagram 2

```mermaid
graph TD;
    A2--> B2;
    A2-->C2;
    B2-->D2;
    C2-->D2;
```


## diagram 3

```mermaid
graph TD;
    A3-->B3;
    A3-->C3;
    B3-->D3;
    C3-->D3;
```
## diagram 4

You can also use ::: blocks:

::: mermaid
graph TD;
    A4-->B4;
    A4-->C4;
    B4-->D4;
    C4-->D4;
:::
## diagram 5

Supports MDI and logos icons from Iconify:

```mermaid
architecture-beta
    service user(mdi:account)
    service lambda(logos:aws-lambda)

    user:R --> L:lambda
```
## diagram 6
"markdown.styles": [
    "https://use.fontawesome.com/releases/v5.7.1/css/all.css"
]
## diagram 7

```mermaid
graph LR
    fa:fa-check-->fa:fa-coffee
```
