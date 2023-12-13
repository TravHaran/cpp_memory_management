#C++ Memory Managemnt Rules

- if data doesn't come from the heap, don't take it from the heap.
- when data or classes have to come from the heap, use the STL pointer wrapper classes to ensure that everything is cleaned up (i.e. unique_ptr).
- Manage data access through abstact interfaces
- Writing boring code. Simple code, that is easy to ready and easy to modify. It comes in small chunks of functionality and doesn't require detective work to figure out how those chuncks work together. It doesn't make assumptions abut the data it receives or returns.
- if you're uncofortable with a technique, or feel that you don't understand it fully - don't use it!
- Comment your code. Proper code comments dont tell that something was done, but instead tell why something was done.
