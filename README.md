
# Migration PROJECT



# Projects Steps -

> step 1: install fresh laravel project

    composer create-project laravel/laravel MigrationAssignment
  
>  step 2: setup database connection from .env file
   
> step 3: create products table

```bash
  php artisan make:migration create_products_table
  ``` 
  
  > step 4: add category column to products table
  
```bash
  php artisan make:migration add_category_to_products_table
  ``` 
  
  >  step 5:  create orders table
```bash
  php artisan make:migration create_orders_table
  ``` 
    
  >  step 6: run migration 

```bash
  cd php artisan migrate 
  ``` 
  
  >  step 7: run project
  
```bash
  cd php artisan serve
  ``` 


  