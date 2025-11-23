# Shop Management System (Tkinter + MySQL)

A simple GUI-based **Shop Management System** built using **Python (Tkinter)** and **MySQL**.

## Features
- Add new products  
- Delete existing products  
- View available products  
- Generate bills and store sales data

## Technologies Used
- Python 3  
- Tkinter  
- MySQL  
- mysql-connector-python

## Database Structure
### Table: products
- date (VARCHAR 10)  
- prodName (VARCHAR 20)  
- prodPrice (VARCHAR 50)

### Table: sale
- custName (VARCHAR 20)  
- date (VARCHAR 10)  
- prodName (VARCHAR 30)  
- qty (INTEGER)  
- price (INTEGER)

## How to Run
1. Install dependencies:
```
pip install mysql-connector-python
```

2. Ensure MySQL server is running and update credentials in code if needed.

3. Run the Python script:
```
python shop.py
```

## Program Flow
- Add Product  
- Delete Product  
- View Products  
- New Customer (Billing)

## Future Improvements
- Dynamic billing for unlimited products  
- Better UI  
- Input validation  
- Secure queries  
