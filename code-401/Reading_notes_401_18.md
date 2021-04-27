# Web App Security

## A) Many to many relationships

### In this part we will cover how the @ManyToMany annotation can be used for specifying this type of relationships in Hibernate.

1. ### If we want to  create many to many relation what we will do is link to table in one table this new table will have a id form first table linked with secund id for the other table.

2. ### In the model class we need to use the @ManyToMany, @JoinTable and @JoinColumn annotations. to indecate that the both classes Employee class and Project classes refer to one another, which means that the association between them is bidirectional.

![manyToMany](https://bezkoder.com/wp-content/uploads/2020/02/mongodb-many-to-many-relationship-mongoose-example.png)