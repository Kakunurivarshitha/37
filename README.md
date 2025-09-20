<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Regestration Form</title>
    <link rel="stylesheet" href ="regstyle.css">
</head>
<body>
    <h2> Regestration Form </h2>
    <form action="/submit"method="post">
        <div>
           <label for="username">UserName:</label>
           <input type="text"id="username" name="username" required>
        </div>
        <br>
        <br>
        <div>
            <label for="email">E-mail:</label>
            <input type="email" id="email" email name ="E-mail" required>
        </div> 
        <br>
        <br>
        <div>
            <label for ="password">password:</label>
             <input tyoe ="password" id ="password "name ="password" required>
         </div>  
         <br>
        <br> 
         <div>
            <label for =" confirm password"> confirm password:</label>
             <input tyoe =" confirm password" id ="confirm password "name ="confirm password" required>
         </div>
         <br>
        <br>
    </form>
</body>
</html>
