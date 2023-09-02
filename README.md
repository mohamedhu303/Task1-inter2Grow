<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <link href="https://fonts.googleapis.com/icon?family=Material+Icons|Material+Icons+Outlined" rel="stylesheet">

   <link rel="preconnect" href="https://fonts.googleapis.com">
   <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
   <link href="https://fonts.googleapis.com/css2?family=El+Messiri&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
   <title> Create a responsive Login Page</title>

   <style>
      *{
         font-family: 'El Messiri', sans-serif;
      }
      .contaner{
         margin: 10% 30%;
         width: 700px;
         height: 500px;
         display: flex;
      }
      .left{
         width: 50%;
         height: 400px;
         display: flex;
         background-image: url(https://img.freepik.com/free-photo/closeup-shot-sunflower-head-with-field-many-surface_181624-37260.jpg?w=900&t=st=1693567498~exp=1693568098~hmac=8bf8a6d073bef53db7365f72437bb3b8eab5661f69492872daa793277173fd50);
         background-size: cover;
      }

      .left .content-left{
         width: 80%;
         color: rgb(255, 255, 255);
         margin: 10% 0 0 10%;
      }
      
      .content-left p{
         margin-top:-30px;
         font-weight: 500;
      } 

      a{
         font-weight: 600;
         color: black;
      }

      .right{
         width: 50%;
         height: 400px;
      }

      .right .first{
         margin-left: 50%;
         font-size: 0.8em;
         color: rgba(0, 0, 0, 0.445);
      }

      .right h2{
         margin: 20px 0 0 5px;
         font-size: 1.6em;
      }

      .containue{
         display: flex;
         align-items: center;
         width: 100%;
         flex-direction: column;
      }

      button ,.containue a{
         width: 80%;
         border-radius: 999px;
         border-color: rgb(1, 123, 153);
         margin-bottom: 5px;
         align-items: center;
         display:flex;
         text-decoration: none;
         justify-items: center;
         background-color: white;
         cursor: pointer;
      }

      .containue a{
         background-color: none;
      }

      button:hover{
         background-color: rgba(0, 0, 0, 0.432);
      }

      button span{
         font-size: 1.4em;
         color: rgb(1, 123, 153);
         margin-left: 3px;
      }

      button i{
         font-size: 1.4em;
         color: rgb(1, 123, 153);
         margin-left: 3px;
      }

      form{
         padding-left: 10px;
      }

      label{
         display: block;
         color: rgba(0, 0, 0, 0.479);
         font-size: 0.8em;
      }
      input{
         display: block;
         border-radius: 999px;
         width: 80%;
         border-color: rgba(0, 0, 0, 0.527);
         height: 20px;
      }

      .submit{
         width: 70px;
         height: 40px;
         color:black;
         background-color: white;
         border-color: rgba(0, 0, 0, 0.678);
         border-radius: 10px;
         font-size: 1.1em;
         font-weight: 600;
         align-items: center;
      }

      .submit:hover{
         background-color: rgba(0, 0, 0, 0.432);
      }

      .forget{
         margin-left: 50%;
         font-size: 0.8em;
         color: rgba(0, 0, 0, 0.445);
      }

      form span{
         font-size: 0.8em;
         color: rgba(0, 0, 0, 0.445);
      }

   </style>
</head>
<body>
   <div class="contaner">
      <div class="left">
         <div class="content-left">
            <h1>Work with us</h1>
            <p>you should have any skill to join & contact us, We wait you.</p>
         </div>
      </div>

      <div class="right">
         <span class="first">Don't have an account? <a href="">Sign up</a></span>
         <h2>Welcome back!</h2>
         <div class="containue">
            <button>
               <a href="">
                  <i class="fa-brands fa-google"></i>
                  <span>   Containue with Google</span>
               </a>
            </button>

            <button>
               <a href="">
                  <i class="fa-brands fa-twitter"></i>
                  <span>   Containue with Twitter</span>
               </a>
            </button>
         </div>
         <br>
         <br>
         <form>
            <label>Enter your email address</label>
            <input type="email" required>

            <label>Enter your password</label>
            <input type="number" minlength="8">
            <a   class="forget" href="">forget your password</a>
            <input class="submit" type="submit">
            <span>Don't have an account? <a href="">Sign up</a></span>
         </form>
      </div>
   </div>
</body>
</html>
