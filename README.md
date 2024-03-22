<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Application Form</title>
</head>
<body>
    <h1>Student Application Form</h1>
    <form action="submit-form-url" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br>
        
        <label for="roll">Roll Number:</label><br>
        <input type="text" id="roll" name="roll_number" required><br>
        
        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="date_of_birth" required><br>
        
        <label for="mobile">Mobile Number:</label><br>
        <input type="tel" id="mobile" name="mobile_number" required><br>
        
        <label for="email">E-mail ID:</label><br>
        <input type="email" id="email" name="email" required><br>
        
        <label for="address">Address:</label><br>
        <input type="text" id="address" name="address" required><br>
        
        <label for="landmark">Landmark:</label><br>
        <input type="text" id="landmark" name="landmark"><br>
        
        <label for="father">Father's Name:</label><br>
        <input type="text" id="father" name="father_name" required><br>
        
        <label for="mother">Mother's Name:</label><br>
        <input type="text" id="mother" name="mother_name" required><br>
        
        <input type="submit" value="Submit">
    </form>
</body>
</html>
