## Information

--> Project Name:- Rto Office

## basic info:-

1. we make this project for both user & rto office  
2. Registration (For rto office) & Login for user 
3. Search vehicle
4. Update vehicle detail
5. Fine check using number plate
6. Detail of all user include ,registration, user detail, car name company name ,insurance Update
7. we connect  JDBC 
8. insurance check
9. user only update P.U.C. & insurance
10. save all detail in file using buffered writer 
## Database info :-

- number_plate(varchar(50))
- owner_name(varchar(50))
- vehicle_name(varchar(50))
- vehicle_color(varchar(50))
- vehical_type (varchar(50))--> bike, car, truck, bus etc. 
- fines (int ) 
- insurance expire date 
- puc expire date 
- owner unique password for login
- pay fine (here we use fix card details for payment )

## Method 

- Registration (only for access by office )
- Login (user)
    - update insurance & puc 
- write method for save all detail in file      
- add fine & fetch fine & pay fine
- all changes (if we need to change already exist vehicle)
- search vehicle 
- check insurance & puc  is valid or not 
