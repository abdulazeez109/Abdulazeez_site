# Abdulazeez_site
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Abdulazeez Data & Airtime</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f9;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #0a3d62;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      padding: 20px;
    }
    h2 {
      color: #0a3d62;
    }
    form {
      background: white;
      padding: 20px;
      margin-top: 10px;
      border-radius: 10px;
      box-shadow: 0 0 10px #ccc;
    }
    input, select, button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #0a3d62;
      color: white;
      border: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Abdulazeez Data & Airtime Services</h1>
    <p>Buy Data, Airtime, Cable TV and More</p>
  </header>

  <div class="container">
    <h2>Buy Data</h2>
    <form>
      <select>
        <option>MTN</option>
        <option>GLO</option>
        <option>Airtel</option>
        <option>9mobile</option>
      </select>
      <input type="text" placeholder="Phone Number" />
      <select>
        <option>500MB - ₦150</option>
        <option>1GB - ₦300</option>
        <option>2GB - ₦500</option>
      </select>
      <button type="submit">Buy Data</button>
    </form>

    <h2>Buy Airtime</h2>
    <form>
      <select>
        <option>MTN</option>
        <option>GLO</option>
        <option>Airtel</option>
        <option>9mobile</option>
      </select>
      <input type="text" placeholder="Phone Number" />
      <input type="number" placeholder="Amount" />
      <button type="submit">Buy Airtime</button>
    </form>

    <h2>Cable Subscription</h2>
    <form>
      <select>
        <option>Dstv</option>
        <option>Gotv</option>
        <option>Startimes</option>
      </select>
      <input type="text" placeholder="Smart Card Number" />
      <select>
        <option>Basic - ₦2000</option>
        <option>Compact - ₦5000</option>
      </select>
      <button type="submit">Subscribe</button>
    </form>
  </div>
</body>
</html>


