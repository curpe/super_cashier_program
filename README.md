# *A guide to Python super_cashier_program* :+1:

## Objective Notes 

*Mesin Kasir* merupakan program untuk mempermudah customer dalam memasukkan item kedalam sebuah `keranjang` yang nantinya didalam object tersebut, kita bisa melihat item yang sudah kita isi, merubah item tersebut, menentukan jumlah nya, dan membuat total harga sehingga customer dapat membayar dari logic yang dibuat. 

### Project duration and timeline
- January to February 2023
- it took me "countless days" to code as i'm not really familiar with programming, but it pays me after all. 

### Methodology concept Applied on this project
- Object Oriented Programming (OOP)
- Error Handling
- Docstring
- Composite Data Structure
- Loop and Branching

### Objective 
- Customer create Transaction with Methods.
- Customer can `Add Item`, `Add Quanitity`, and `Add Price` to each item.
- After adding `item`,` quantity`, and `price`, they can update to each one of the function.
- Customer can `remove` particular item of they own
- Customer can do `reset` the item of the entire basket.
- Add `discount` logics if the total price were sufficient.

## The Diagram Journey (old version)
 ![python_cashier_project drawio](https://user-images.githubusercontent.com/94776243/216772174-a51f957a-b141-40c8-90cf-cb9fb4f3b751.png)


## Test this code in your IDE.
- 1. Clone this repositery.
    
- 2. After the code appears on your IDE, Open your `terminal`

- 3. type this in your terminal
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


3. Method `update_nama_item()` to update the name of particular item.
        <img width="469" alt="edit_name" src="https://user-images.githubusercontent.com/94776243/216772394-233ee41a-fa12-4301-8401-291fcdbc5c5e.png">

4. Method `update_jumlah_item()` to update the quantity of particular item.
        <img>

5. Method `update_harga_item()` to update the price of particular item.
        <img>

6. Method `check_order()` see the entire item that were inputted.
        <img>

7. Method `total_pembelian()` + `discount_inputted()` to check the total price, total quantity, total type of item and see if the price were match with discount scheme.

    <img>

8. Make a simple payment transaction on `pembayaran()` method. 

    - If the nominal below than the total price, you will see this 
        <img>

    - Say YES if you want to try again, check the order and the item is still there. 
        <img>

    - Input the nominal match with *total sesuai harga* and you will see this message

        <img>

    - And if you select to input YES, then the basket were removed if you select to check the order.

        <img>

9. After all, you can reset the entire basket by `reset_item()` method.

        <img>

10. exit the PACSHIER system by press no `9`

        <img>
      

## Conclusion and Suggestion
- Kita bisa menambah Library seperti table agar lebih rapih.
- Masih perlu banyak improvement dan exploration dalam code.
- Diagram masih belum di update dengan code yang terbaru, tetapi secara garis besar concept nya mendekati dengan diagram nya.

### :blush: Hope this guide will help :blush:

**Copyright** (c) 2023 Abhi Abduh