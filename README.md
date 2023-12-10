# website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>Survey Form</title>
</head>
<body>
  <div class="container">
    <h1 id="title">Survey Form</h1>
    <p id="description">Please fill out this survey form.</p>

    <form id="survey-form">
      <label for="name" id="name-label">Name:</label>
      <input type="text" id="name" placeholder="Enter your name" required>

      <label for="email" id="email-label">Email:</label>
      <input type="email" id="email" placeholder="Enter your email" required>

      <label for="number" id="number-label">Number:</label>
      <input type="number" id="number" placeholder="Enter a number" min="1" max="10" required>

      <label for="dropdown">Select an option:</label>
      <select id="dropdown" required>
        <option value="" disabled selected>Select an option</option>
        <option value="option1">Option 1</option>
        <option value="option2">Option 2</option>
      </select>

      <label>Radio buttons:</label>
      <div class="radio-group">
        <label><input type="radio" name="radio" value="radio1">Radio 1</label>
        <label><input type="radio" name="radio" value="radio2">Radio 2</label>
      </div>

      <label>Checkboxes:</label>
      <div class="checkbox-group">
        <label><input type="checkbox" value="checkbox1">Checkbox 1</label>
        <label><input type="checkbox" value="checkbox2">Checkbox 2</label>
      </div>

      <label for="comments">Additional comments:</label>
      <textarea id="comments" rows="5" placeholder="Enter additional comments"></textarea>

      <button type="submit" id="submit">Submit</button>
    </form>
  </div>

  <script src="script.js"></script>
</body>
</html>
