# *A guide to Python super_cashier_program* :rocket:
- Why super? well... i'm trying my best to make the code as intuitive as i can :grin:


## Objective Notes 

*Mesin Kasir* merupakan program untuk mempermudah customer dalam memasukkan item kedalam sebuah `keranjang` yang nantinya didalam object tersebut, kita bisa melihat item yang sudah kita isi, merubah item tersebut, menentukan jumlah nya, dan membuat total harga sehingga customer dapat membayar dari logic yang dibuat. 

### Project duration and timeline
- January to February 2023

### Methodology and concept applied on this project
- Object Oriented Programming (OOP)
- Error Handling
- Docstring
- Composite Data Structure
- Looping and Branching

### Objective 
- Customer create Transaction with Methods.
- Customer can `Add Item`, `Add Quanitity`, and `Add Price` to each item.
- After adding `item`,`quantity`, and `price`, they can update to each one of the function.
- Customer can `remove` particular item of they own.
- Customer can do `reset` the item of the entire basket.
- Add `discount` logics if the total price were sufficient.

## The Diagram Journey (old version)
 ![python_cashier_project drawio](https://user-images.githubusercontent.com/94776243/216772174-a51f957a-b141-40c8-90cf-cb9fb4f3b751.png)


## Test this code in your IDE.
- 1. Clone this repository.
    
- 2. After the code appears on your IDE, Open your `terminal`.

- 3. type this in your terminal:
    ```
    python menu.py
    ```
- 4. And you will see this when the code running. 
    <img width="578" alt="Initialization" src="https://user-images.githubusercontent.com/94776243/216772219-f1229b5b-d59f-4b1c-aea1-2cb3f198f207.png">

## Test case and result

1. Method `add_barang()` with the customer can freely input their items.
        <img width="549" alt="add" src="https://user-images.githubusercontent.com/94776243/216772351-c99ad17c-c350-4a57-9a25-2841f2b835ac.png">

2. Method `delete_item()` particular items after they added the item by themselves. 
        <img width="549" alt="delete" src="https://user-images.githubusercontent.com/94776243/216772374-8d89afb3-0ac7-4acf-b820-583076902efc.png">


3. Method `update_nama_item()` to update *"Kentang"* to *"Kentung"*.
        <img width="469" alt="edit_name" src="https://user-images.githubusercontent.com/94776243/216772394-233ee41a-fa12-4301-8401-291fcdbc5c5e.png">

4. Method `update_jumlah_item()` to update the quantity of particular item.
        <img width="415" alt="edit_quantity" src="https://user-images.githubusercontent.com/94776243/216772452-d7434241-cd3a-4e2f-8b18-3aa71fc7aab0.png">

5. Method `update_harga_item()` to update the price of particular item.
        <img width="400" alt="edit_price" src="https://user-images.githubusercontent.com/94776243/216772468-ab067126-38f3-426d-8bb4-64b2683bdb0f.png">

6. Method `check_order()` see the entire item that were inputted.
        <img width="542" alt="show_basket" src="https://user-images.githubusercontent.com/94776243/216772490-45f30f18-b77b-41e3-96b6-e9eef61b6801.png">

7. Method `total_pembelian()` + `discount_inputted()` to check the total price, total quantity, total type of item and see if the price were match with discount scheme.
        <img width="538" alt="see_transaction" src="https://user-images.githubusercontent.com/94776243/216772505-733db17c-6c4c-44cf-ab15-a6a5c3842c29.png">

8. Make a simple payment transaction on `pembayaran()` method. 

    - If the nominal below than the total price, you will see this:
            <img width="540" alt="transaction_handling" src="https://user-images.githubusercontent.com/94776243/216772551-dfd163ab-8f99-4bb0-b787-7c096cc3fce2.png">

    - Say YES if you want to try again, check the order and the item is still there: 
            <img width="648" alt="check_order_after_yes" src="https://user-images.githubusercontent.com/94776243/216772588-c2509886-f810-4153-929f-bc7532c19706.png">

    - Input the nominal match with *total sesuai harga* and you will see this message:
            <img width="365" alt="transaction_success" src="https://user-images.githubusercontent.com/94776243/216772600-9d60916d-a7a2-4168-a94b-556e38df4673.png">


    - If you input "YES", then items in the basket will removed.
        <img width="591" alt="basket_empty" src="https://user-images.githubusercontent.com/94776243/216772620-16cfc043-d1c5-4e74-a925-cb3a407f242b.png">

9. After all, you can reset the entire basket by `reset_item()` method.
        <img width="533" alt="reset_basket" src="https://user-images.githubusercontent.com/94776243/216772652-6eead311-cf87-44c7-bedb-9e54f2b0aa58.png">

10. exit the PACSHIER system by pressing no `9` on your terminal.
        <img width="451" alt="exit" src="https://user-images.githubusercontent.com/94776243/216772692-103163aa-fe2a-4e02-9ce4-07f5e73f7a49.png">
      

## Conclusion and Suggestion
- Kita bisa menambah Library seperti table agar lebih rapih.
- Masih perlu banyak improvement dan exploration dalam code.
- Diagram masih belum di update dengan code yang terbaru, tetapi secara garis besar concept nya mendekati dengan diagram nya.

### :blush: Hope this guide will help :blush:

**Copyright** (c) 2023 Abhi Abduh