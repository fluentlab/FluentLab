<h1>Welcome to FluentLab 🌍</h1>
<p>Type your English sentence below and see the correction + explanation!</p>
<textarea id="userInput" placeholder="Write in English..."></textarea>
<button onclick="sendMessage()">Check</button>
<p id="response"></p>
<!DOCTYPE html>
<html>
<head>
  <title>FluentLab AI - Demo</title>
  <style>
    body { font-family: Arial; text-align: center; margin-top: 50px; }
    textarea { width: 300px; height: 100px; }
    button { padding: 10px 20px; margin-top: 10px; }
    #response { margin-top: 20px; font-weight: bold; }
  </style>
</head>
<body>

<!-- 1️⃣ Header -->
<h1>Welcome to FluentLab 🌍</h1>

<!-- 2️⃣ Description -->
<p>Type your English sentence below and see the correction + explanation!</p>

<!-- 3️⃣ Textarea -->
<textarea id="userInput" placeholder="Write in English..."></textarea>
<br>

<!-- 4️⃣ Button -->
<button onclick="sendMessage()">Check</button>

<!-- 5️⃣ Response area -->
<p id="response"></p>

<!-- 6️⃣ JavaScript تجريبي -->
<script>
function sendMessage() {
  const message = document.getElementById("userInput").value;
  let response = "Great sentence! Here's a correction suggestion: " + message;
  document.getElementById("response").innerText = response;
}
</script>

</body>
</html>