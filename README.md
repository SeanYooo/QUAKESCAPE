<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Path to Safety</title>
<style>
  body {
    font-family: 'Open Sans', sans-serif;
    background-color: #f0f0f0; /* Light gray background */
    margin: 0;
    padding: 0;
    color: #333; /* Adjust the text color as needed */
    margin-top: 80px; /* Adjust top margin to match header */
    margin-left: 10px; /* Adjust left margin */
    margin-right: 10px; /* Adjust right margin */
    text-align: center; /* Center body text */
  }

  header {
    background-color: #0b1c35; /* Dark blue header */
    padding: 10px;
    text-align: left;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    position: fixed; /* Fixed position */
    width: 100%; /* Full width */
    z-index: 1000; /* Ensure it's above other content */
    top: 0; /* Position at the top */
  }

  header img {
    max-width: 80px;
    vertical-align: middle;
  }

  h1 {
    margin: 0;
    font-size: 18px; /* Adjust the font size */
    color: #fff; /* White text */
    display: inline-block;
    margin-left: 10px;
    vertical-align: middle;
  }

  main {
    padding: 20px 8%; /* Adjust horizontal padding */
    background-color: #f0f0f0; /* Light gray background */
    max-width: 1300px; /* Adjust maximum width */
    margin: auto; /* Center content */
    text-align: justify; /* Justify text */
  }

  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 20px;
  }

  th, td {
    padding: 10px;
    text-align: left;
    border-bottom: 1px solid #ddd;
  }

  th {
    background-color: #0b1c35; /* Dark blue header color */
    color: #fff; /* White text */
  }

  #calculateButton, #clearButton {
    margin-top: 20px;
    display: inline-block;
    vertical-align: middle; /* Align buttons vertically */
  }

  button {
    padding: 10px 20px;
    background-color: #d13913; /* Darker orange background color */
    color: #fff; /* White text */
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px; /* Adjust font size */
  }

  button:hover {
    background-color: #b33410; /* Darker orange on hover */
  }

  #clearButton button {
    margin-left: 20px; /* Add margin between buttons */
  }

  hr {
    border: 0;
    height: 1px;
    background-color: #ddd;
    margin-top: 40px;
    margin-bottom: 40px;
  }

  p {
    margin: 0; /* Adjust paragraph margin */
  }
</style>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <img src="head.png" alt="QuakeScape Logo">
    <h1>Your Path to Safety</h1>
  </header>

  <main>
    <h2>Data Inputs</h2>
    <form id="networkFlowForm">
      <table>
        <tr>
          <th>Parameter</th>
          <th>Value</th>
        </tr>
        <!-- Input fields here -->
      </table>
    </form>

    <div id="calculateButton">
      <button type="button" onclick="calculateEvacuationTime()">Calculate Evacuation Time</button>
    </div>

    <div id="clearButton">
      <button type="button" onclick="clearFields()">Clear</button>
    </div>

    <div id="result"></div>

    <hr>

    <h2>About Us</h2>
    <p><strong style="color: orange;">About Us</strong>: Introducing QuakeScape, the app revolutionizing escape routes by leveraging precise data to mitigate empirical obstacles, ultimately saving lives. Our innovative solution prioritizes accuracy and efficiency, ensuring individuals can navigate emergencies with confidence and security. Join us in transforming disaster preparedness with QuakeScape.</p>

    <!-- Divider between sections -->
    <hr>

    <!-- How does this webpage work? section -->

    <!-- What can this create? section -->
  </main>

  <script>
    // Clear fields functionality
    function clearFields() {
      document.getElementById("smokeCoefficient").value = "";
      document.getElementById("numberOfExits").value = "";
      document.getElementById("distance").value = "";
      document.getElementById("exitCapacity").value = "";
      document.getElementById("averageSpeed").value = "";
      document.getElementById("population").value = "";
      document.getElementById("result").innerHTML = "";
    }

    // Calculation functionality
    function calculateEvacuationTime() {
      // Calculation logic here
    }
  </script>
</body>
</html>
