# Project-GrubDash

## Installation

1.  Fork / clone this repository.
2.  Run npm install.
3.  Use npm start to run the application.

## Description

- This is an API project following **RESTful design principles** for a Grub-Dash-Back-End found [here](https://github.com/ramamdeeCode/Project-GrubDash/blob/master/grubdash-main/README.md)

[live Server](https://grub-dash-frontend.onrender.com)
## Home

![image](https://user-images.githubusercontent.com/86864383/183989221-3499e80c-8ada-447d-93a9-c99f148b48dd.png)


## Dashboard
<img width="1506" alt="Screenshot 2022-11-26 at 12 17 46 AM" src="https://user-images.githubusercontent.com/86864383/204074239-96812eea-3fda-4ae6-b3c6-de4e492e0c04.png">




## create order
<img width="1504" alt="Screenshot 2022-11-26 at 12 18 38 AM" src="https://user-images.githubusercontent.com/86864383/204074175-321b3ec4-df95-4d3b-9438-f91839e5f4cd.png">


## Functionalities

This server work with two resources Dishes and Orders

| Dishes              | Routes              |
| ------------------- | ------------------- |
| Create new Dish     | POST /dishes        |
| Update new Dish     | PUT /dishes/:dishId |
| Find Dish by id     | GET /dishes/:dishId |
| List all the Dishes | GET /dishes         |

| Orders              | Routes                  |
| ------------------- | ----------------------- |
| Create new Order    | POST /orders            |
| Update new Order    | PUT /orders/:orderId    |
| Find Order by id    | GET /orders/:orderId    |
| Delete Order        | Delete /orders/:orderId |
| List all the dishes | POST /orders            |
