<?php
session_start();
if (!isset($_SESSION['user_id'])) {
    header('Location: ../auth/user_login.php');
    exit;
}

include('../config/db.php');

$sql = "SELECT * FROM books";
$result = $conn->query($sql);
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Dashboard</title>
    <link rel="stylesheet" href="../css/styles.css">
</head>
<body>
    <header>
        <h1>User Dashboard</h1>
        <nav>
            <ul>
                <li><a href="browse_books.php">Browse Books</a></li>
                <li><a href="../auth/user_logout.php">Logout</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Available Books</h2>
        <?php
        if ($result->num_rows > 0) {
            echo '<table>';
            echo '<tr><th>Title</th><th>Author</th><th>Price</th><th>Description</th><th>Image</th><th>Action</th></tr>';
            while ($book = $result->fetch_assoc()) {
                echo '<tr>';
                echo '<td>' . $book['title'] . '</td>';
                echo '<td>' . $book['author'] . '</td>';
                echo '<td>' . $book['price'] . '</td>';
                echo '<td>' . $book['description'] . '</td>';
                echo '<td><img src="' . $book['image'] . '" alt="' . $book['title'] . '" width="50"></td>';
                echo '<td><a href="buy_book.php?id=' . $book['id'] . '">Buy</a></td>';
                echo '</tr>';
            }
            echo '</table>';
        } else {
            echo '<p>No books available.</p>';
        }
        ?>
    </main>
    <footer>
        <p>&copy; 2024 Online Bookstore</p>
    </footer>
    <script src="../js/scripts.js"></script>
</body>
</html>

<?php
$conn->close();
?>
