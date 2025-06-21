# py-5.1
class Product:
    def __init__ (self,product_id,product_name,price,expiry_date):
        self.product_id = product_id
        self.product_name = product_name
        self.price = price
        self.expiry_date = expiry_date
    def print_display(self):
        print(f"Product ID:{self.product_id}")
        print(f"Product Name:{self.product_name}")
        print(f"Price:{self.price}")
        print(f"Expiry Date:{self.expiry_date}")
product1=Product(458,"ball pens",6.25,"2 jan 2026")
product1.print_display()

