# index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shahidullah Hall Registration</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f2f5;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .container {
      background-color: #ffffff;
      padding: 40px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 400px;
    }
    h1 {
      font-size: 24px;
      margin-bottom: 10px;
      text-align: center;
    }
    h2 {
      font-size: 18px;
      margin-bottom: 20px;
      text-align: center;
      color: #555;
    }
    input[type="text"],
    input[type="email"] {
      width: 100%;
      padding: 10px;
      margin: 8px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
      box-sizing: border-box;
    }
    button {
      width: 100%;
      background-color: #007bff;
      color: white;
      padding: 10px;
      margin-top: 12px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Shahidullah Hall</h1>
    <h2>Registration Application</h2>
    <form>
      <label for="name">Name</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required />

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required />

      <label for="studentid">Student ID</label>
      <input type="text" id="studentid" name="studentid" placeholder="Enter your student ID" required />

      <label for="department">Department</label>
      <input type="text" id="department" name="department" placeholder="Enter your department" required />

      <label for="room">Room Number</label>
      <input type="text" id="room" name="room" placeholder="Enter room number" required />

      <button type="submit">Register</button>
    </form>
  </div>
</body>
</html>
