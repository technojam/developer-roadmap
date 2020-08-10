# RecyclerView
The RecyclerView widget is a more advanced and flexible version of ListView.
## Implementation
To implement a basic RecyclerView three sub-parts are needed to be constructed which offer the users the degree of control they require in making varying designs of their choice.
  * **The Card Layout**:- It is an XML layout which will be treated as an item by the RecyclerView.
  * **The ViewHolder**:- It is a java class that stores the reference to the layout views that have to be dynamically modified during the execution of the program by a list of data.
  * **The Data Class**:- It is a custom java class that acts as a structure for holding the information for every item of the RecyclerView.
### Adapter Class
The adapter is the main code responsible for RecyclerView. It holds the important methods dealing with the implementation of RecylcerView. Some methods of adapter class are 
  * onCreateViewHolder
  * onBindViewHolder
  * getItemCount
  * onAttachedToRecyclerView
## Steps to implement recyclerView
  * Add the library to the dependencies section.
  * Add the RecyclerView to your XML file.
  * Add a list adapter (adapter class)
  * Customize the RecyclerView objects according to your needs.
