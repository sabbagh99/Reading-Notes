# Create dynamic lists with RecyclerView

## RecyclerView defination

### It's easyer for us to use RecyclerView to display large sets of data, when you supply the data and define how each item looks the RecyclerView library dynamically creates element when they're needed

## Key classes

### When you build a dynamic list several different classes may work together as the following :

* #### RecyclerView : we can use it to view it in a view group corresponding for out data.

* #### By defult when we have element in a list is using view holder object  if we are  extending RecyclerView.ViewHolder.

* ####  extending RecyclerView.Adapter help us to  binds the views to  their data and to do this we need to call adapter methods.

* ####   LayoutManager help you to arrange the individual elements in your list.

## Steps for implementing your RecyclerView:

#### 1. You need to know what the list or grid is going to use in recycler view

#### 2. Disign our list of element using ViewHolder , and will provide us with functionality

#### 3. Define the Adapter that associates your data with the ViewHolder views.

## Plan your layout 

### the items in the recycler view are arranged by a LayoutManager , and we have three  layout managers,

#### 1. LinearLayoutManager arranges the items in a one-dimensional list.

#### 2. GridLayoutManager arranges all items in a two-dimensional grid.

#### 3. StaggeredGridLayoutManager.