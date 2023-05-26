<?php include "connection.php"?>
<DOCTYPE html>
<html>
    <head>
        <title>Contact Form</title>
        <style>
            .Form{
                align-items: center;
            }
        </style>
    </head>
    <body>
    <?php if(isset($_GET['submit']))
        {
           $mail=$_POST['mail'];
           $password=$_POST['password'];

           $hashFunction = "$2y$10$";
           $salt = "usesomesillystringforsalt$";

           $hash_salt = '$2a$07$usesomesillystringforsalt$';
           $password=crypt($password,$hash_salt);
           


        //    echo "My mail: ".$mail."<br/>"."My Password: ".$password;
        $query="INSERT INTO registration(Mail,password) ";
        $query.="VALUES ('$mail','$password')";
        $result=mysqli_query($connection,$query);

        if($result)
            {
                echo "the data updated";
            }
        else{
            echo "Data not updated";
        }
        }
        ?>
        <form action="contact_form.php" method="post" class="Form">
            <legend><h2>Registration Form</h2></legend> <br>

            <label for="mail">Mail: </label>
            <input type="text" name="mail">
            <label for="password">Password:</label>
            <input type="text" name="password">
            <input type="submit" name="submit" value="Submit">
        </form>
    <?php
        if(isset($_POST['submit'])){
            $id = $_POST['id'];
            $query="DELETE FROM registration ";
            $query.="WHERE id = '$id' ";
            $result=mysqli_query($connection,$query);
            if(!$result){
                die("Query failed".mysqli_query($connection));
            }
            else{
                echo "<br/> $id Record deleted";
            }
       }
   ?>
    <h1>Update record</h1>
    <form action="crud1.php" method="post">
        <input type="email" name="mail" placeholder="Enter your email">
        <input type="password" name="password" placeholder="Enter your password">
         <select name="id"><?php
          $query='SELECT *FROM registration';
          $result=mysqli_query($connection,$query);
          if(!$result)
          {
            die("query failed".mysqli_error($connection));
          }
          else
          {
            echo "<br>result is working<br/>";
            while($row=mysqli_fetch_assoc($result))
            {
                $id=$row['id'];
                echo "<option value='$id'>$id</option>";
            }
        } 
        ?>
        
        
        </select>
        <input type="submit" value="Update" name="submit">
    </form>


   <h1>Delete record</h1>
   <form action="crud1.php" method="post">
        <select name="id">
        <?php
            $query = "SELECT * FROM registration";
            $result = mysqli_query($connection,$query);
            if(!$result){
                die("query failed".mysqli_error($connection));
            }
            else
            {
                echo "Result is working <br/>";
                while($row=mysqli_fetch_assoc($result)){
                $id=$row['id'];
                echo"<option value='$id'>$id</option>";
                }
            }
        ?>
        </select>
        <input type="submit" value="Delete" name="submit">
    </form>
    <?php
     if(isset($_POST['submit']))
     {
        $id=$_POST['id'];
        $mail=$_POST['mail'];
        $password=$_POST['password'];

        $query="UPDATE registration SET ";
        $query.="Mail='$mail',";
        $query.="password='$password' ";
        $query.="WHERE id='$id' ";
 
        $result=mysqli_query($connection,$query);
        if(!$result)
        {
            die("Query failed".mysqli_error($connection));
        }
        else
        {
            echo "<br />Updated your record";
        }
     }

     ?>

     </body>
</html>