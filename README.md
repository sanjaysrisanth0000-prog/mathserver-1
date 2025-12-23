# Ex.05 Design a Website for Server Side Processing
# Date:28/11/2025
# AIM:
To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side.

# FORMULA:
P = I2R
P --> Power (in watts)
 I --> Intensity
 R --> Resistance

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Create python programs for views and urls to perform server side processing.

## Step 5:
Create a HTML file to implement form based input and output.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
    <title>LAMP P0WER CALCULATOR</title>
 <style>
        body {
            background-color:rgba(4, 158, 219, 0.225);
            color: rgb(0, 0, 0);
        }

        label {
            display: inline-block;
            color: rgb(0, 0, 0);
            width: 200px;
        }
        input {
            margin-bottom: 10px;
            margin-left: 20px;
            color: rgb(0, 0, 0);
        }
        .container {
            position: relative;
            align-content: center;
        }
      
    </style>
</head>



<body>
    <div class="container">


    <h2>Power of Lamp Filament</h2>

    <label>Intensity (I): </label>
    <input type="number" id="intensity">
    <br>
    <br>
    <label>Resistance (R): </label>
    <input type="number" id="resistance">
    <br>
    <br>

    <button onclick="calculatePower()">Calculate Power</button>
    <h3 id="result"></h3>

    <script>
        function calculatePower() {
            let I = Number(document.getElementById("intensity").value);
            let R = Number(document.getElementById("resistance").value);

            let P= I*I*R; 

            document.getElementById("result").innerHTML = "Power = " + P + " watts";
        }
    </script>
    </div>
</body>
</html>
```
# SERVER SIDE PROCESSING:
<img width="1920" height="1080" alt="Screenshot 2025-12-23 151622" src="https://github.com/user-attachments/assets/3cecea43-87e7-495a-959e-c57e234b0a9c" />


# HOMEPAGE:
<img width="1920" height="1080" alt="Screenshot 2025-12-23 151609" src="https://github.com/user-attachments/assets/cac1a1f0-0102-418f-9116-64cb2dd12ce2" />

# RESULT:
The program for performing server side processing is completed successfully.
