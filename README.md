# Ex.05 Design a Website for Server Side Processing
# Date:
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
    <title>Lamp Power Calculator</title>
 <style>
        body {
            background-image: url('image.avif');
            background-repeat: no-repeat;
            width: 100%;
        }
        label {
            display: inline-block;
            width: 150px;
            color: rgb(3, 3, 3);
            }
        input {
            margin-bottom: 10px;
            color: rgb(13, 13, 13);
        }
        button {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h2 style="font-size: xx-large;">Power of Lamp Filament</h2>
    <label style="font-size: larger;">Intensity (I): </label>
    <input type="number" id="intensity"><br><br>
    <label style="font-size: larger;">Resistance (R): </label>
    <input type="number" id="resistance"><br><br>
    <button onclick="calculatePower()">Calculate Power</button>
    <h3 id="result"></h3>
    <script>
        function calculatePower() {
            let I = Number(document.getElementById("intensity").value);
            let R = Number(document.getElementById("resistance").value);
            let P = I * I * R; 
            document.getElementById("result").innerHTML = "Power = " + P + " watts";
        }
    </script>

</body>
</html>
```

#OUTPUT
![alt text](<Screenshot 2025-12-18 231644.png>)
![alt text](<Screenshot 2025-12-18 231704.png>)



# SERVER SIDE PROCESSING:
# HOMEPAGE:
# RESULT:
The program for performing server side processing is completed successfully.
