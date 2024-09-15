<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Dashboard</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #008080;
        }
        .profile, .courses, .grades {
            margin-bottom: 30px;
        }
    </style>
</head>
<body>
<div class="container">
    <h1>Welcome, [Student Name]</h1>
    <div class="profile">
        <h2>Profile Information</h2>
        <p><strong>Name:</strong> John Doe</p>
        <p><strong>Email:</strong> john.doe@example.com</p>
        <p><strong>Program:</strong> Computer Science</p>
    </div>
    <div class="courses">
        <h2>Enrolled Courses</h2>
        <ul>
            <li>Web Development</li>
            <li>Data Science</li>
        </ul>
    </div>
    <div class="grades">
        <h2>Your Grades</h2>
        <p>Web Development: A</p>
        <p>Data Science: B+</p>
    </div>
</div>
</body>
</html>
