

 Grocery Store App

Grocery Store is an e-commerce style web application that creates a direct link between customers and the shop, similar to Amazon, eBay, or Walmart. The app has two main phases: Admin and User.

- *Admin Phase:* Allows creation, updating, and deletion of products and categories to adapt to customer needs or external changes like government policies.  
- *User Phase:* Enables searching, adding/removing products from the cart, and placing orders.

 Features

- Separate Admin and User functionalities  
- CRUD operations on Categories and Products via RESTful APIs  
- User-friendly interface with search, cart management, and ordering  
- Data visualization with Seaborn for insights (if applicable)  

API Endpoints

 Category API  
- GET /category_api/{id} - Get category by ID  
- GET /category_api/ - Get all categories  
- POST /category_api/ - Create a new category  
- PUT /category_api/{id} - Update category by ID  
- DELETE /category_api/{id} - Delete category by ID  

 Product API  
- GET /product_api/{id} - Get product by ID  
- GET /product_api/ - Get all products  
- POST /product_api/ - Create a new product  
- PUT /product_api/{id} - Update product by ID  
- DELETE /product_api/{id} - Delete product by ID  

 Technologies Used

- Python (Programming Language)  
- Flask (Web Framework)  
- HTML & Bootstrap (Frontend)  
- Flask-SQLAlchemy (SQLite database connection)  
- Jinja2 (Template engine for HTML injection)  
- Werkzeug (Security utilities)  
- Seaborn (Data visualization)  

 Project Structure

GROCERY-ECOMMERCE/ ├── static/ ├── templates/ ├── admin.py ├── API.py ├── API.yaml ├── app.py ├── controller.py ├── database.sqlite3 ├── model.py

 Getting Started

1. Clone the repository:  
   ```bash
   git clone https://github.com/Saravanaguru281/grocery-store-app.git

2. Navigate to the project directory:

cd grocery-store-app


3. Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate    # Linux/macOS  
venv\Scripts\activate       # Windows


4. Install dependencies:

pip install -r requirements.txt


5. Run the app:

flask run --port=8080


6. Open your browser and visit:

http://localhost:8080/



License

This project is licensed under the MIT License - see the LICENSE file for details.  
