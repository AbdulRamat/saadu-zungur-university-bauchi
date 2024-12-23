# saadu-zungur-university-bauchi
schoolfees
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Student Dashboard</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="dashboard">
  <h1>SA'ADU ZUNGUR UNIVERSITY BAUCHI</h1>
  <h2>Student Dashboard</h2>
<div class="student-info">
<h2>Student Information</h2>
<p>Matric Number: <span id="matric-number">MTHU/23/0913</span></p>
<p>Name: <span id="student-name">RAMAT ISAH UMAR</span></p>
<p>Level: <span id="student-level">200</span></p>
<p>Department: <span id="student-department">Department of Mathematical science</span></p>
<p>Faculty: <span id="student-faculty">Faculty of Science</span></p>
</div>
<div class="fee-payment">
<h2>Fee Payment</h2>
<p>Fee Amount: <span id="fee-amount">₦62,500.00</span></p>
<p>Payment Status: <span id="payment-status">Not Paid</span></p>
<button id="make-payment-btn">Make Payment</button>
</div>
<div class="payment-instructions">
<h2>Payment Instructions</h2>
<ol>
<li>Click on the "Make Payment" button to proceed with payment.</li>
<li>Select your preferred payment method and follow the prompts.</li>
<li>Enter your payment details and confirm the transaction.</li>
<li>Once payment is successful, your payment status will be updated.</li>
</ol>
</div>
<div class="transaction-history">
<h2>Transaction History</h2>
<table>
<tr>
<th>Date</th>
<th>Amount</th>
<th>Payment Method</th>
<th>Status</th>
</tr>
<!-- Transaction history will be displayed here -->
</table>
</div>
</div>

```<script src="script.js"></script>
```
</body>
</html>
