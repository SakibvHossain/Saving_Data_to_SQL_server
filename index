<?php
 require 'connection.php';

 if(isset($_POST["submit"])){
     $name = $_POST["name"];
     $email = $_POST["email"];
     $role = $_POST["role"];
     $logo = $_POST["logo"];
     $game = $_POST["game"];
     $code = $_POST["code"];
     
     
     $query = "INSERT INTO teams_database VALUES('','$name','$email','$role','$logo','$game','$code')";
     
     mysqli_query($conn, $query);
     echo
         "
         <script> alert('Data Inserted Successfully'); </script>
         ";
     
 }
?>

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Create Team</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
      <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
      <link rel="stylesheet" href="index.css">
  </head>
  <body>
    <div class="border" >
        
    <form class="" action="" method="post" autocomplete="off">
          
  
    <label for="">Name</label>
    <input type="text" name="name"  required value="">

    <label for="">Gmail</label>
    <input type="text" name="email"  required value="">
        
    <label for="">Team Role</label>
    <input type="text"  name="role"  required value="">
        
    <label for="">Team Logo</label>
    <input type="file"  name="logo" required value="">

    <label for="">Game Name</label>
    <select class="" name="game" required>
                        <option selected>Open this select Game</option>
                        <option value="Football">Football</option>
                        <option value="Cricket">Cricket</option>
                        <option value="Basketball">Basketball</option>
                        <option value="Handball">Handball</option>
                        <option value="Chess">Chess</option>
                        <option value="Badminton">Badminton</option>
                        <option value="Tennis">Tennis</option>
                        <option value="Hockey">Hockey</option>
                        <option value="Volleyball">Volleyball</option>
                        <option value="Table Tennis">Table Tennis</option>
                        <option value="Shooting">Shooting</option>
                        <option value="Baseball">Baseball</option>
                        <option value="Golf">Golf</option>
                        <option value="Kabaddi">Kabaddi</option>
                        <option value="Carrom Pool">Carrom Pool</option>
    </select>
        
       <label for="">Team Code</label>
    <input type="number" name="code" required value="">

            
          <div class="add_button_div_section">
              <button class="button add_fields"><i class="fa fa-plus"></i></button>
          </div>
        
          <div class="all_buttons">
              <div style="float: left">
                  <button class="button btn1" type="submit" name="submit">Create</button>
              </div>
              
              <div style="float: left">
                  <button class="button btn2">Edit</button>
              </div>
              
              <div style="float: left">
                  <button class="button btn3">Update</button>
              </div>
              
              <div style="float: left">
                 <button class="button btn4">Delete</button>
              </div>
          </div>
        </form>
    </div>
    <script src="https://kit.fontawesome.com/7a1e1ce7a3.js" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
      
      <script src="Team_create.js"></script>
  </body>
</html>
