# Product Table
## Date: 07-07-2025
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:

```
<!DOCTYPE html>
<html>
<head>
    <title>Product Table</title>
</head>
<body>
    <table border="1">
        <caption>Product Information</caption>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>₹45,000</td>
                <td>High-speed performance</td>
            </tr>
            <tr>
                <td>Phone</td>
                <td>$499</td>
                <td>Budget-friendly</td>
            </tr>
            <tr>
                <td>Tablet</td>
                <td>₹25,000</td>
                <td>Portable and lightweight</td>
            </tr>
            <tr>
                <td>Headphones</td>
                <td>₹3,500</td>
                <td>Noise cancelling</td>
            </tr>
            <tr>
                <td>Watch</td>
                <td>₹12,000</td>
                <td>Smart features included</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

## Output:

![image](https://github.com/user-attachments/assets/85d306ad-e57d-4918-9cc3-9b0ba527b1e1)

## CSS Code:

```
body {
    background-color: #f9f9f9;
    font-family: Arial, sans-serif;
}

table {
    border-collapse: collapse;
    margin: auto;
    width: 80%;
}

caption {
    font-weight: bold;
    margin-top: 20px;
    margin-bottom: 10px;
    font-size: 18px;
}

th {
    background-color: #4CAF50;
    color: white;
    padding: 12px;
    text-align: left;
}

td {
    border: 1px solid #ddd;
    padding: 12px;
}

tbody tr:nth-child(even) {
    background-color: #f2f2f2;
}

tbody tr:hover {
    background-color: #e8f5e8;
}
```

## Output:

![image](https://github.com/user-attachments/assets/29a57827-9b40-42ac-bc6f-c779ca814a9f)



## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
