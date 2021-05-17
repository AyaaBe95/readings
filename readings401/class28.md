# RecyclerView

- It is a container for displaying large datasets which can be scrolled efficiently by maintaining limited number of views.
- It is more flexible and advanced version of GridView and ListView.
- RecyclerView reuses the view for new items that have scrolled onscreen.

## Key classes:
- RecyclerView is the ViewGroup that contains the views corresponding to your data. 
- Each individual element in the list is defined by a view holder object (RecyclerView.ViewHolder)
- RecyclerView.Adapter: it binds the views to their data.
- LayoutManager: arranges the individual elements in your list.

## Steps for implementing  RecyclerView:
- decide what the list or grid is going to look like
- Design how each element in the list is going to look and behave (ViewHolder provides all the functionality for your list items)
- Define the Adapter that associates  data with the ViewHolder views.

## Plan layout:
- The items in RecyclerView are arranged by a LayoutManager class.
- The RecyclerView library provides three layout managers.
1. LinearLayoutManager arranges the items in a one-dimensional list.
2. GridLayoutManager arranges all items in a two-dimensional grid (Vertically and Horizantaly)
3. StaggeredGridLayoutManager: it does not require that items in a row have the same height  or items in the same column have the same width.

## Implementing  adapter and view holder
- Once layout has been determined, you need to implement  Adapter and ViewHolder. 
- These two classes work together to define how  data is displayed. 
- The ViewHolder is a wrapper around a View that contains the layout for an individual item in the list.
- The Adapter creates ViewHolder objects as needed, and also sets the data for those views. 

### methods:
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()





