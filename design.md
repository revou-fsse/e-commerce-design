# E-Commerce Design Assigment

## High Level Design

![high level diagram](https://user-images.githubusercontent.com/9874779/218235900-aa0dadd1-a9d1-46ba-a4c4-6e49e8382424.png)

Some explanation about the diagram here. Explain what pattern you use, and why.

## Create Order Details

### Explanation

Some initial explanation and assumption.

<!-- 
This sequence diagram is created using https://sequencediagram.org/ with this code:

title Create Order Flow

actor User

User -> component1: create order request
activate component1
component1 ->component2: do something
activate component2
component2 ->component1: return something
deactivate component2
component1 ->component3: do something
activate component3
component3 ->component1: return something
deactivate component3
component1 ->User: 200 OK
deactivate component1
-->

![create order flow](https://user-images.githubusercontent.com/9874779/218236081-1c79cdf4-4193-409f-b3a7-37465fef11cd.png)

```pseudocode
function something_useful():
    do something

function createOrder(product_ids):
    do something
    call something_useful()
```

### Complexity Analysis

The complexity of creating a order is $O(n*m)$ with $n =$ **something** and $m =$ **something else**. I got this complexity because ...
