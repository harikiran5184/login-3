<html>
    <head>
        
        
     
     <link rel="shortcut icon" type="image/x-icon" href="">
     <style>
            @keyframes ani {
                from{ background-color: lightpink;}
                to{background-color: lightgray;}
            }
        body{
            background-color: wheat;
            background-image: url("https://wallpaperaccess.com/full/8278302.gif");
           
        }
        .back{
            color: coral;
            text-transform: capitalize;
            text-decoration: underline;
            

        }
        #p{
            
            color: deeppink;
            font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif ;
            
            text-align: center;
            text-overflow: clip;
            padding-bottom: 15px;
            margin-bottom: 5px;
            display:inline-flex;
        }
        .tra{
            background-color: lightgray;
            backface-visibility:inherit;
            border-radius: 10px;
            display:inline-table;
            margin-left: 40%;
            height: 80%;
            animation-name: ani;
            animation-duration: 10s;
        }
        .submit {
            text-align: center;
            color: darkgray;
            
        }
        #fir{
            display:inline-flex;
        }
     </style>
     <script>
        function myFunction()
        {   
            document.getElementById("fir").innerHTML="sucessfully done!";
            document.getElementById("fir").style.backgroundImage="linear-gradient(to right,lightgreen,white)";
            
            document.getElementById("tra").style.backgroundColor="lightgreen";
            document.getElementById("bd").style.backgroundImage="url('https://i.gifer.com/7efs.gif')";            
            document.getElementById("back").style.color="green";
        }
     </script>
    </head>
    <title> login page</title>   
    <body id="bd">
        <div class="back" id="back">
            <h1 style="text-align:center ;"> Login Form </h1>

        </div>
        <div class="tra" id="tra">
            <form>
                <label for="username" style="padding: 4px;color:deeppink;">Username:</label>
                <input type="text" id="p" name="username" placeholder="Enter your name" style="margin-top:30px;" required><br>
              
              
                <label for="DOB" style="padding: 4px;margin-right:32px;color:deeppink;">DOB:</label>
                <input type="date" id="p" name="DOB" required style="padding-left: 10px;"><br>
                <label for="roll" style="padding: 4px;margin-right:17px;color:deeppink;">Roll no:</label>
                <input type="number" id="p" name="roll" placeholder="Enter your roll"required><br>
                <label for="phone" style="padding: 4px;margin-right:24px;color:deeppink;">Phone:</label>
                <input type="number" id="p" name="username" placeholder="Enter your phone number" required><br>
                <label for="email" style="padding: 4px;margin-right:20px;color:deeppink;">E-mail:</label>
                <input type="mail" id="p" name="email" placeholder="Enter your E-mail" required><br>
                <label for="photo" style="padding: 4px;margin-right:26px;color:deeppink;">Photo:</label>
                <input type="file" id="p" name="photo" required><br>
                <label for="remark" style="padding: 4px;color:deeppink;margin-right:8px;">Remarks:</label>
                <input type="text" id="p" name="Remarks" placeholder="enter remarks here" required style="height: 100px;"><br></form>
        </div>
        <div class="submit">
            <button onclick="myFunction()" ><p>submit</p></button>
            

        </div>
        <marquee>
    <p id="fir"></p>
</marquee>
</body>
</html>
