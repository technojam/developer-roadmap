# RecyclerView
RecyclerView is a viewgroup used to display similar type of data from a database. 
Example: List of contacts.
## Implementation
Requirements to implement RecyclerView :
  * **XML Layout**:- A format in which we display our data.
  * **ViewHolder**:- It is the reference to layout which is dynamically modified during execution.
  * **The Data Class**:- It is the structure for holding every item in the RecyclerView.
### Adapter Class
The adapter is the main class responsible for RecyclerView. It contains important methods dealing with the implementation of RecylcerView. Some methods of adapter class are 
  * onCreateViewHolder
  * onBindViewHolder
  * getItemCount
  * onAttachedToRecyclerView
## Steps to implement recyclerView
  * Add the library to the dependencies section.
  * Add the RecyclerView to your XML file.
  * Add a list adapter (adapter class)
  * Customize the RecyclerView objects according to your needs.
