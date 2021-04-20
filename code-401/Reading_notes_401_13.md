# Related Resources and Integration Testing.

## A) One-to-One Relationship :

### 1. The Data Model : If we defind to  two class with entity that mean we have one-to-one relationship and using  @OneToOne annotation, if we wnt to customize the endpoint. we have to use  @RestResource annotation.

### 2.  The Repositories: to create Repository we need to add interface fo this repository and extending the CrudRepository interface.

### 3. Creating the Resources :  "We can see in the response body that an association resource has been exposed at the libraries/{libraryId}/address endpoint."

## B) One-to-Many Relationship : 

### 1. The Data Model : just we need to use @ManyToOnein the class and add  the relationship to the other class who have relation with as well.

### 2. The Repositories: to create Repository we need to add interface fo this repository and extending the CrudRepository interface.

## C) Many-to-Many Relationship : 

### 1. The Data Model : just we need to use @ManyToMany the class and add  the relationship to the other class who have relation with as well.

### 2. The Repositories: to create Repository we need to add interface fo this repository and extending the CrudRepository interface.
