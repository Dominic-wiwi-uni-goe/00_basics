## Vectors, functions, and data frames

### Vectors
- Vector is the most fundamental data structure that is used to store data in R. 
- Vector is a one-dimensional, ordered collection of data of the same data type.
- To manually create a vector in R, we use c( ). 
- Alternatively, there are also built-in functions in R specifically for the purpose of creating numeric vectors such rep( ) and seq( ).
- We can also access, add, remove, and alter the elements in any given vector.


### Functions
- Programming, much like any problem-solving scenario in general, is about breaking down a big problem into smaller constituent components. 
- This helps to not only better structure and organise our work but more importantly, it allows for easier code review and debugging when needed.
- Functions are a piece of code that performs a certain task that can be readily reused again. A function involves a simple 3-step process: input, process and output.
- Inputs are sometimes called parameters or arguments which is what we pass into the function itself. 
- Process is what the function will perform on the inputs that it is being given, which can be any form of data transformation or numerical computation. 
- Last but not least, the function will then return the desired output.

### Data frames
- Similar to a vector, data frame is data structure that is used for storing data in R. 
- It is a list of vectors which are of equal lengths but can be of different data types.
- The vectors are presented as columns, each with a name and represent variables. 
- The rows represent observations and can be named or unnamed.
- While they can be constructed from scratch, data frames are typically produced from importing data sets e.g. csv or Excel format files.


**Source**: https://towardsdatascience.com/r-basics-everything-you-need-to-know-to-get-started-with-r-10c8e566d7b3
