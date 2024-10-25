<?php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "customerinfo";

$conn = new mysqli($servername, $username, $password, $dbname);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}

if (isset($_POST['submit'])) {
    $type = $_POST['meats'];
    $name = $_POST['name'];
    $quantity = $_POST['quantity'];
    $price = $_POST['price'];

    $sql = "INSERT INTO product (type, name, quantity, price) VALUES ('$type', '$name', '$quantity', '$price')";

    try {
        if ($conn->query($sql) === TRUE) {
            echo "Record added successfully";
        }
    } catch (mysqli_sql_exception $e) {
        echo "Error: " . $e->getMessage();
    }
}
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Input Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 10px 15px;
            background-color: #28a745;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

<h2>Product Input Form</h2>

<form id="productForm" class="input-group" method="post" action="">
    <div class="form-group">
        <label for="meat-selection">Select a type of meat:</label>
        <select id="meat-selection" name="meats" required>
            <option value="" disabled selected>Select your option</option>
            <option value="beef">Beef</option>
            <option value="pork">Pork</option>
            <option value="chicken">Chicken</option>
            <option value="lamb">Lamb</option>
            <option value="turkey">Turkey</option>
            <option value="duck">Duck</option>
            <option value="venison">Venison</option>
            <option value="bacon">Bacon</option>
            <option value="sausage">Sausage</option>
            <option value="fish">Fish</option>
            <option value="shellfish">Shellfish</option>
            <option value="goat">Goat</option>
            <option value="rabbit">Rabbit</option>
        </select>
    </div>

    <div class="form-group">
        <label for="productName">Product Name:</label>
        <input type="text" name="name" id="productName" required>
    </div>
    <div class="form-group">
        <label for="quantity">Quantity:</label>
        <input type="number" name="quantity" id="quantity" min="1" required>
    </div>
    <div class="form-group">
        <label for="price">Price:</label>
        <input type="number" name="price" id="price" step="0.01" required>
    </div>
    <button type="submit" name="submit">Submit</button>
</form>


<script src="input.js"></script>
</body>
</html>
