<html>
 <head>
  <title>
   A Web Page
  </title>
  <style>
   body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ccc;
        }
        .header {
            background-color: #ccc;
            padding: 10px;
            text-align: center;
        }
        .header input[type="text"] {
            width: 80%;
            padding: 5px;
        }
        .header img {
            vertical-align: middle;
        }
        .nav {
            text-align: center;
            margin: 20px 0;
        }
        .nav a {
            margin: 0 10px;
            text-decoration: none;
            color: black;
        }
        .content {
            display: flex;
        }
        .content .left {
            flex: 1;
            text-align: center;
        }
        .content .left img {
            width: 200px;
            height: 200px;
            border: 1px solid #000;
        }
        .content .left button {
            margin-top: 10px;
            padding: 5px 10px;
        }
        .content .right {
            flex: 2;
            padding-left: 20px;
        }
        .content .right input[type="text"], .content .right select {
            width: 100%;
            padding: 5px;
            margin: 5px 0;
            border: 1px solid #000;
        }
        .content .right textarea {
            width: 100%;
            height: 100px;
            padding: 5px;
            margin: 5px 0;
            border: 1px solid #000;
        }
        .content .right .checkbox-group {
            margin: 10px 0;
        }
        .content .right .checkbox-group input[type="checkbox"] {
            margin-right: 5px;
        }
        .content .right .checkbox-group label {
            color: green;
        }
        .content .right .note {
            font-size: 12px;
            color: #666;
        }
        .content .right .generate-button {
            background-color: green;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
        a{
            text-decoration: none;
            color: #fff;
        }
  </style>
 </head>
 <body>
  <div class="nav">
   <a href="#">
    Home
   </a>
   |
   <a href="#">
    Generate Link
   </a>
   |
   <a href="#">
    Transaction History
   </a>
   |
   <a href="#">
    Policy
   </a>
   |
   <a href="#">
    Logout
   </a>
  </div>
  <div class="container">
   <div class="content">
    <div class="left">
     <img alt="Placeholder Image" src="macbook.jpg"/>
     <br/>
     <button>
      Upload Picture
     </button>
    </div>
    <div class="right">
     <label>
      Title Here:
     </label>
     <input type="text" value="MacBook Air £800"/>
     <label>
      Description:
     </label>
     <textarea>Year : 2009
Model :
Condition : Mint</textarea>
     <label>
      Account Number:
     </label>
     <input type="text" value="123-456-789-0"/>
     <label>
      Bank:
     </label>
     <select>
      <option>
       HSBC
      </option>
     </select>
     <label>
      Account Holder:
     </label>
     <input type="text" value="Name Here"/>
     <label>
      Transaction:
     </label>
     <input type="text" value="1"/>
     <div class="note">
      * if the transaction is for 3 person, choose 3 from the drop-down list
     </div>
     <div class="checkbox-group">
      <input checked="" type="checkbox"/>
      <label>
       Send to Mobile Phone
      </label>
      <br/>
      <input checked="" type="checkbox"/>
      <label>
       Send to Email
      </label>
     </div>
     <label>
      Send to Mobile Phone:
     </label>
     <input type="text" value="1234567890, 1234567891"/>
     <label>
      Send to Email:
     </label>
     <input type="text" value="mfrmm2g13@soton.ac.uk, fys_06@yahoo.com"/>
     <br/>
     <button class="generate-button">
      <a href="formpemesanan2indexs.html" >Generate</a>
     </button>
    </div>
   </div>
  </div>
 </body>
</html>
