HTML Code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Task Management System</title>
   
</head>
<body>

    <div class="container">
        <div class="content">
            <h1>Be Organized</h1>
            <div class="image">
                <img src="https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcScH9uRpwTYZf3QTTDtw0KY189cXefWB6KE6JXBu2RvEl1LRG9G" alt="Organized" />
            </div>

            <div class="buttons">
                <button class="btn" id="logInBtn">Log In</button>
                <button class="btn" id="signUpBtn">Sign Up</button>
                <p><a href="#" id="forgetPassword">Forget password</a></p>
            </div>
        </div>
        
        </body>
</html>


CSS Code
body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    margin: 0;
    padding: 0;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #fafafa;
}

.content {
    text-align: center;
    background-color: #fff;
    padding: 30px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    max-width: 500px;
}

h1 {
    color: #2c3e50;
    font-size: 36px;
    margin-bottom: px;
	 font-family:lobster;
}

.image img {
    width: 95%;
    max-width: 300px;
}

.buttons {
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.btn {
    padding: 15px 20px;
    font-size: 16px;
    color: white;
    background-color: #3498db;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.btn:hover {
    background-color: #2980b9;
}

a {
    color: #3498db;
    text-decoration: none;
    font-size: 14px;
}

a:hover {
    text-decoration: underline;
}

JavaScript Code 

document.getElementById("logInBtn").addEventListener("click", function() {
    alert("Log In button clicked!");
});

document.getElementById("signUpBtn").addEventListener("click", function() {
    alert("Sign Up button clicked!");
});

document.getElementById("forgetPassword").addEventListener("click", function() {
    alert("Forget Password clicked!");
});


 

