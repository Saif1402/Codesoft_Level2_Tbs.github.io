<?php
// Replace with your actual database credentials
$host = 'localhost';
$username = 'root';
$password = '';
$dbname = 'form';

// Connect to the database
$conn = new mysqli($host, $username, $password, $dbname);

// Check the database connection
if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}

if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Collect form data
    $name = $_POST['name'];
    $email = $_POST['email'];
        $age = $_POST['age'];
            $country = $_POST['country'];
                $gender = $_POST['gender'];
                    $mobile = $_POST['mobile'];
                        $date = $_POST['date'];
                            $payment_method = $_POST['payment_method'];
                                $amount = $_POST['amount'];
                                    $transaction_id = $_POST['transaction_id'];
                                    

    

    // Insert the user data into the database using prepared statements
    $stmt = $conn->prepare("INSERT INTO reg_data (name, email, age, country, gender, mobile, date, payment_method, amount, transaction_id) VALUES (?, ?, ?, ?, ?, ?, ?, ?, ?, ?)");
    $stmt->bind_param("ssssssssss", $name, $email, $age, $country, $gender, $mobile, $date, $payment_method, $amount, $transaction_id);

    if ($stmt->execute()) {
        echo "Registration successful!";
    } else {
        echo "Error: " . $stmt->error;
    }

    $stmt->close();
}
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    if (isset($_POST["user_id"]) && !empty($_POST["user_id"])) {
        $user_id = $_POST["user_id"];
$sql = "DELETE FROM users WHERE user_id = $user_id";

        if ($conn->query($sql) === TRUE) {
            echo "User with ID $user_id has been deleted successfully!";
        } else {
            echo "Error deleting user: " . $conn->error;
        }
    } else {
        echo "Please provide a valid user id.";
}
}

$conn->close();
?>
