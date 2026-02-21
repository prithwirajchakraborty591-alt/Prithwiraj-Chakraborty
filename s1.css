<?php
$isSubmitted = false;

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $isSubmitted = true;
    $name = $_POST['name'];
    $college = $_POST['college'];
    $phone = $_POST['phone'];
    $email = $_POST['email'];
}
?>

<!DOCTYPE html>
<html>
<head>
    <title>Student Information Form</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
        }

        .container {
            width: 400px;
            margin: 80px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0px 0px 10px gray;
        }

        h2, h3 {
            text-align: center;
        }

        label {
            display: block;
            margin-top: 15px;
        }

        input {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }

        button {
            margin-top: 20px;
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #0056b3;
        }

        .result {
            margin-top: 30px;
            padding: 15px;
            background: #e9f5ff;
            border-radius: 6px;
        }
    </style>

    <script>
        function validateForm() {
            let phone = document.getElementById("phone").value;

            if (phone.length != 10 || isNaN(phone)) {
                alert("Please enter a valid 10-digit phone number");
                return false;
            }
            return true;
        }
    </script>
</head>

<body>

<div class="container">
    <h2>Student Information Form</h2>

    <form method="POST" onsubmit="return validateForm()">
        <label>Name:</label>
        <input type="text" name="name" required>

        <label>College:</label>
        <input type="text" name="college" required>

        <label>Phone Number:</label>
        <input type="text" name="phone" id="phone" required>

        <label>Email ID:</label>
        <input type="email" name="email" required>

        <button type="submit">Submit</button>
    </form>

    <?php if($isSubmitted): ?>
    <div class="result">
        <h3>Submitted Information</h3>
        Name: <?php echo $name; ?><br>
        College: <?php echo $college; ?><br>
        Phone: <?php echo $phone; ?><br>
        Email: <?php echo $email; ?><br><br>

        <h3>Mess / Hostel Information</h3>
        1) Chakraborty Mess - ₹3000/3500 per month - Nearby Camellia Polytechnic, Nandanagar - Rooms: 12 <br>
        2) Lokenath Mess - ₹4000 per month - Nandanagar - Rooms: 17 <br>
        3) Taramaa Mess - ₹3500 per month - Nearby Railway Station - Rooms: 6 <br>
        4) Mondal Complex (Boys & Girls) - ₹5000 per month - Nearby Railway Station - Rooms: 10 <br><br>

        <h3>Contact Numbers</h3>
        Chakraborty Mess: 7633224141 <br>
        Lokenath: 7602841117 <br>
        Taramaa: 9135683985 <br>
        Mondal Complex: 9307423859
    </div>
    <?php endif; ?>

</div>

</body>
</html>
 
  
