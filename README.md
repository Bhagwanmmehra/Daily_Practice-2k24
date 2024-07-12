<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>car form</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <main>
<nav>
    <h2>CarsInSure</h2>
    <div class="navbar">
    <a href="index.html">Home</a>
    <a href="#">About Us</a>
    <a href="#">Services</a>
    <a href="#">Our Partners</a>
    <a href="#">Contact Us</a>
        </div>
</nav>
<aside>
    <div class="roadsafety">
        <p><q> WE DON'T ONLY INSURE CARS WE ASSURE PEOPLE'S SAFETY ALSO </q></p>
        <p>Here You Can Check Daily Incidents of The Day By
    Clicking On The Button Below:</p>
   <p><a href="https://traffic.nayan.co/"> NAYAN AI </a></p>
</div>
</aside>

        <form>
            <h2>Car Insurance Form</h2>
            <div class="name-box">
                <label for="name">Name</label>
                <input type="text" name="name" id="name" placeholder="Enter Name">
            </div>
            <div class="email-box">
                <label for="email">Email</label>
                <input type="email" name="email" id="email" placeholder= "Enter Email" required>
            </div>
            <div class="gender-box">
                <label for="gender">Gender</label>
                <input type="radio" name="gender" id="gender" value="male" required>Male
                <input type="radio" name="gender" id="gender" value="female" required>Female
            </div>
            <div class="brands-box">
                <label for="car-brands">Car-Brands</label>
                <select name="car-brands" id="car-brands" class="car-brandsbox">
                    <option value="">Select</option>
                    <option value="volvo">Volvo</option>
                    <option value="bmw">BMW</option>
                </select>
            </div>
            <div class="age-box">
                <label for="age">Car Age</label>
                <input type="number" name="age" id="age" max="120" min="0" required>
            </div>
            <div class="purchasedate-box">
                <label for="dateofpurchase">Date of Purchase</label>
                <input type="date" name="date" id="dateofpurchase">
            </div>
            <div class="password-box">
                <label for="password">Password</label>
                <input type="password" name="password" id="password" placeholder="Type Password Here!" required>
            </div>
            <div class="submit-box">
                <button>Submit</button>
            </div>
        </form>

    </main>
</body>

</html>

stylesheet//

*{
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

body{
  
    background-color: black;
    background-image: url('preview_32215.jpg');
    background-size: cover;
    background-repeat: repeat;
}

main{
    width: 100%;
    height:100% ;
    background-color: aliceblue;
    display: flex;
    flex-direction: column;
   

}


.roadsafety{
    width: 400px;
    height: 300px;
    background-color: antiquewhite;
    position: absolute;
    top: 21rem;
    left:3rem;
    padding: 5px;
    display: flex;
    justify-content: baseline;
    flex-direction: column;
    border-radius: 10px;
    font-style: italic;
    gap:10px;
    font-weight: 700;
    color:maroon;

}

q{
    font-size: 30px;
    font-weight: 800;
    border-bottom: 3px solid maroon;
    padding: 2px;
}

form{
    display:flex;
    flex-direction:column;
    width:300px;
    height: 455px;
    gap: 10px;
    padding: 10px;
    border-radius: 10px;
    position: absolute;
    bottom: 10px;
    right: 40px;
    border: 1px solid black;
    font-size: 18px;
    font-weight: 540;
    background-color: rgb(8, 50, 88);;
    color: wheat
    
}

form>h2{
    text-align: center;
    border-bottom: 2px solid black;
}
select{
    text-align: center;
    margin-left: 10px;
    width: 125px;
    border-radius: 8px;
    font-size: 18px;
}

.name-box,.email-box,.purchasedate-box,.password-box{
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 2px;
    font-size: 18px;
}

.name-box>input,.email-box>input,.purchasedate-box>input,.password-box>input{
    width: 100%;
    height: 32px;
    outline: none;
    border-radius: 8px;
    font-size: 18px;
}
.age-box>input{
    width:50px;
    height: 22px;
    margin-left: 30px;
    border-radius: 4px;
    font-size: 18px;
    outline: none;
    
}

.submit-box,button{
    text-align: center;
    background-color: seagreen;
    border: none;
    font-size: 18px;
    padding: 2px;
    border-radius: 8px;
}
button:hover{
    background-color: seagreen;
    
}
.gender-box{
    display: flex;
gap:15px;
font-size:18px;
height: 35px;
}

nav{
    display: flex;
    flex-direction: row;
    background-color: black;
} 

.navbar{
    display: flex;
    align-items: center;
}
.navbar>a{
    color: white;
    text-decoration: none;
    font-size: 30px;
    padding: 2px;
    margin-left: 7rem;
}

.navbar>a:hover{
background-color: gray;
border-radius:8px;
transition: 1s;

    }

nav>h2{
    font-size: 50px;
    color: chartreuse;
    border: 1px solid white;
    padding: 10px;
}
