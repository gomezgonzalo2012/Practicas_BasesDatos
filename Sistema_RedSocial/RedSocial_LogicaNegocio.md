# Red Social para postear fotos

## listado de entidades

### posts **(ED)**
- post_id **(PF)**
- post_date
- plot (descripción)
- photo (URL)
- user **(FK)**

### user **(ED)**
- user **(PK)**
- user_date (fecha de creación)
- user_name 
- email **(UQ)**
- password
- phone **(UQ)**
- bio
- web (URL)
- birth_date
- genre
- country **(fK)**

### comments **(ED|EP)**
- comment_id **(PK)**
- comment_date
- comment
- post_id **(FK)**
- user **(FK)**

### hearts **(ED|EP)**
- heart_id **(PK)**
- heart_date
- post_id **(FK)**
- user  **(FK)**

### follows
- follow_id **(PK)**
- follow_date 
- follow_user (a quien sigo)
- user **(FK)** ()


### country **(EC)**
- country_id **(PK)**
- country_name 


