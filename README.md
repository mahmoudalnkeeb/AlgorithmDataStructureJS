![javascript algorithm and data structures!](/assets/js.png "javascript algorithm and data structures")

# Data Structures & Algorithms

1. ## Data Structures

    - ### Arrays
        
        Arrays are the most basic data structure
        in JavaScript arrays are dynamic which means 
        that we don't predefine type & size
        [Array in mdn for further reading](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array#)

    - ### Stack

        Stack is a linear data structure in which addition or removal of element follows a particular order i.e. LIFO -Last in First Out- AND FILO -First in Last Out-

        in JavaScript we implement stack with array 


            class Stack {
                constructor()
                    {
                        this.items = [];
                    }

                // Most common operations on Stack in JS

                // this method adds one item to stack
                push(item){
                    this.items.push(item)
                }
                // this method removes the most recent item and return it
                pop(){
                    if(this.items.length == 0) return "empty"
                    return this.item.pop()
                }
                // this method only returns the most recent item 
                peek(){
                    return this.items[this.items.length - 1]
                }
                // this method returns true if stack is empty
                isEmpty(){
                    return this.items.length == 0
                }
            }

    When to use stack? (applications)



    - ### Queue
    - ### Linked List
    - ### Set
    - ### Hash table
    - ### Tree
    - ### Trie
    - ### Graph
  

2. ## Algorithm




