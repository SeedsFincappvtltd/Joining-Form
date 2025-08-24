<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Employee Joining Form</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f4f4f4; padding: 20px; }
    form { background: white; padding: 20px; border-radius: 8px; max-width: 400px; margin: auto; box-shadow: 0 2px 6px rgba(0,0,0,0.2);}
    input, select, textarea { width: 100%; padding: 8px; margin: 8px 0; border: 1px solid #ccc; border-radius: 4px; }
    button { background: #4CAF50; color: white; padding: 10px; border: none; width: 100%; cursor: pointer; border-radius: 4px; }
    button:hover { background: #45a049; }
  </style>
</head>
<body>
  <h2 style="text-align:center;">Employee Joining Form</h2>
  <form>
    <label>Full Name:</label>
    <input type="text" name="name" required>

    <label>Email:</label>
    <input type="email" name="email" required>

    <label>Date of Joining:</label>
    <input type="date" name="doj" required>

    <label>Department:</label>
    <select name="department">
      <option>HR</option>
      <option>Finance</option>
      <option>Operations</option>
      <option>IT</option>
    </select>

    <label>Address:</label>
    <textarea name="address"></textarea>

    <button type="submit">Submit</button>
  </form>
</body>
</html>
