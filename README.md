<!DOCTYPE html>
<html>
<head>
  <title>Smart Life Assistant</title>
</head>
<body>
  <h1>Smart Life Assistant</h1>
  <p>Follow the prompts to complete all 4 tasks.</p>

<script>
let age = parseInt(prompt("Enter your age:"));
let weight = parseFloat(prompt("Enter your weight (in kg):"));

let idealWeightMin, idealWeightMax;
if (age >= 18 && age <= 25) {
  idealWeightMin = 50; idealWeightMax = 70;
} else if (age > 25 && age <= 40) {
  idealWeightMin = 55; idealWeightMax = 75;
} else if (age > 40 && age <= 60) {
  idealWeightMin = 60; idealWeightMax = 80;
} else {
  idealWeightMin = 50; idealWeightMax = 75;
}

if (weight >= idealWeightMin && weight <= idealWeightMax) {
  alert("You are fit for your age.");
} else if (weight < idealWeightMin) {
  alert("You are underweight for your age. Consider a healthy diet.");
} else {
  alert("You are overweight for your age. Consider regular exercise.");
}

let income = parseFloat(prompt("Enter your monthly income (₹):"));

if (income < 10000) {
  alert("Spend cautiously and save more!");
} else if (income >= 10000 && income <= 30000) {
  alert("Balanced budget!");
} else {
  alert("Your income is great! Consider investing in SIPs.");
}

let dataUsage = parseFloat(prompt("Enter total mobile data used this month (in GB):"));

if (dataUsage < 5) {
  alert("Low usage");
} else if (dataUsage >= 5 && dataUsage <= 15) {
  alert("Normal usage");
} else {
  alert("You are a heavy data user. Upgrade your plan.");
}

const oldPasswordStored = "admin123";

let oldPassInput = prompt("Enter old password:");
if (oldPassInput === oldPasswordStored) {
  let newPass = prompt("Enter new password:");
  let confirmPass = prompt("Confirm new password:");
  
  if (newPass === confirmPass) {
    alert("Password changed successfully.");
  } else {
    alert("Passwords do not match.");
  }
} else {
  alert("Old password is incorrect.");
}
</script>
</body>
</html>
