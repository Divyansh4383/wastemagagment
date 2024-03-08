PROBLEM STATMENT NUMBER -144
TITLE-Domestic Waste Management

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoComplaint</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="icon" href="favicon.ico" type="image/x-icon">

    <style>
        h1{
            text-align: center;
            font-size: 70px;
            font-weight: 400;
        }
        body{
            background-color: #bc9de8;
        }
        img{
            max-height: 550px;
            max-width: 700px;
            margin: 10px;
            transition: transform 0.3s ease-in-out;
        }
        img:hover {
            transform: scale(1.1);
        }
        p{
            font-size: 30px;
        }
        button{
            background-color:rgb(195, 195, 173);
            color:black;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor:pointer;
            
        }
        .button{
            font-weight:bold;
        }
        button:hover{
            
    background-color: burlywood;
    transform: scale(1.1);
    transition: transform 0.3s ease-in-out;
}


    
    body {
    font-family: 'Roboto', sans-serif;
}

    </style>
</head>
<body>
    <h1> Waste Managment System</h1>
    <P>Welcome to EcoComplaint, your platform for addressing waste management issues. We connect citizens with government, fostering a cleaner, greener society. Spot a problem? Log in, report it, and we'll
         forward it to the relevant authorities. 
         You can track the progress of your complaint until resolution. 
         By giving voice to your concerns, we can influence waste management practices,
          contributing to a healthier planet. Join us at EcoComplaints and let's make a
           difference, one complaint at a time.</P> <img src="https://as2.ftcdn.net/v2/jpg/07/09/89/49/1000_F_709894934_AurCstddCJsB7hZvXZ1cPzN9fX6yimaR.jpg" >
           <h2>
            Ways to manage waste
           </h2>
           <div>
            <p>1. Use a reusable bottle/cup for beverages on-the-go<br>
                You can put that reusable bottle to use, save money and reduce waste. By taking your own water with you, you’ll also reduce your chances of purchasing more expensive beverages on-the-go.</p>
                <p>
                    2. Compost it!<br>
                    Your fruit and vegetable scraps, egg shells, coffee grounds, grass clippings and leaves can all be composted. While composting requires more effort than the previously mentioned lifestyle changes, it will provide you with a beneficial return on your investment of time and effort.
                </p>
                <p>
                    3. Avoid single-use food and drink containers and utensils<br>
    Whenever possible, try to avoid single-use coffee cups, disposable utensils, straws and napkins. 
                </p>
    
        </div>
       
     <h2>Community Participation</h2>
        <p> Involve community members in decision-making processes related to waste management. This can include forming committees or councils where community members can contribute ideas
            , provide feedback, and take part in planning initiatives</p><img src = "https://as1.ftcdn.net/v2/jpg/06/31/85/08/1000_F_631850822_JFN9gULJmnkROFQCzvTs5qNRYOGCs0qc.jpg"> 
    <h2>Fill the form below</h2>
    <form>
        <section class="align">
            <label for ="fname">First Name:</label><br>
            <input type="text" id="fname" name="fname" required><br>
            <label for="lname">Last Name:</label><br>
            <input type="text" id="lname" name="lname" required><br>
            <label for="address">Address:</label><br>
            <input type="text" id="address" name="address" placeholder="Type Your Full Address" required><br>
            <label for ="phone">Phone Number:</label><br>
            <input type="tel" id="phone" name="phone" required pattern="[0-9]{5}[0-9]{5}" placeholder="12345-67890" required><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" required><br>
            <label for="summary">Complain:</label><br>
            <textarea id="summary" name="summary" rows="3" cols="50" placeholder="Write your complain in brief"></textarea><br>
            <button class="button" type="submit">Submit</button>
            <h2 style="text-align: center;">
                We will help you in manageing waste!
                <br>
                We will report your complain to your nearest municipal corporation.
            </h2>
        </section>
    </form>
</body>
</html>
