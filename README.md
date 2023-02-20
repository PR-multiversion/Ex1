# Ex1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Pattu raja">
    <meta name="description" content="Hi I'm PR. This is about me.">
    <link rel="icon" href="PR.jpg" type="image/x-icon">
    <title>Basic HTML</title>
    <style>
        body
        {
            background-color: whitesmoke;
        }
        header
        {
            display: flex;
            align-items: center;
            background-color: rgb(4, 24, 66);
            color: whitesmoke;
            padding-left: 100px;
            gap: 200px;
            letter-spacing: 2px;
            position: fixed;
            width: 100%;
            top: 0;
        }
        nav
        {
            display: flex;
            gap: 60px;
        }
        nav a
        {
            text-decoration: none;
            color: whitesmoke;
            font-size: 19px;
            font-weight: 800;
        }
        p{
            font-size: 17px;
            line-height: 23px;
        }
        input
        {
            margin-left: 60px;
        }
        button
        {
            margin-top: 15px;
            padding: 6px;
            font-size: 18px;
            font-weight: 700;
            border: none;
            background-color: rgb(4, 24, 66);
            border-radius: 5px;
            color: whitesmoke;
            margin-left: 50px;
        }
    </style>
</head>
<body>
    <header>
        <h2 style="font-weight: bold; font-family: 'Courier New', Courier, monospace;">PR CREATION</h2>
            <nav>
                <a href="#time">TIME TABLE</a>
                <a href="#IP">IP</a>
                <a href="#PR.html">AUTHOR</a>
            </nav>
    </header>
    <main style="margin-top: 70px;">
     <section id="IP">
        <h1>Overview of <abbr title="Internet Programming">IP</abbr></h1>
        <p>An Internet application is a client/server application that uses standard Internet protocols for connecting the client to the server. You can use exactly the same techniques to create a true Internet application, which is available publicly through the World Wide Web, or to create an intranet application. <br><br> Internet application is one that runs on your corporate intranet, and is only available to the staff in your corporation. Whenever we talk about Internet applications, we mean either true Internet applications or intranet applications.
            Internet applications are thin-client, thick-server. This means that the client end, the part the end-user sees and interacts with, is only responsible for the user interface. The client runs on a Web browser - the standard tool for accessing the Internet. All the processing is done at the server end - where your corporate data is.
        </p>
        <h1> What does an Internet Application Look Like?</h1>
        <p>
             Internet applications are client/server applications, and can be split into two pieces:
        </p>
        <ul>
           <li>Forms</li> 
           <li>Server-side programs</li> 
        </ul>

        <h1>FORM</h1>
        <form action="https://httpbin.org/get" method="get">
            <fieldset>
                <legend>Personal info</legend>
            <p>
                <label for="firstname">First Name :</label>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <input type="text" name="firstname" id="firstname"
            placeholder="Raja" autocomplete="on" required autofocus>
            </p>
            <p>
                <label for="lastname">Last Name :</label>
                &nbsp;&nbsp;&nbsp;&nbsp;
            <input type="text" name="lastname" id="lastname"
            placeholder="king" autocomplete="on" required>
            </p>
            <p>
                <label for="password">Password :</label>
                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <input type="password" name="password" id="passsword"
            placeholder="Keep secret"  required>
            </p>
            <p>
                <label for="phone" style="margin-right: 30px;">Phone :</label>
                &nbsp;&nbsp;&nbsp;&nbsp;
            <input type="tel" name="phpne" id="phone"
            placeholder="6666666666" pattern="[0-9]{3}[0-9]{3}[0-9]{4}" required>
            </p>
            <p>
                <label for="decade" style="margin-right: 45px;">Decade :</label>
            <input type="number" name="decade" id="decade"
            min="1950" max="2022" step="10" value="1960">
            </p>
            <p>
                <label for="food">Favorite Lang :</label>
                <input type="text" id="lang" list="lang-list">
                <datalist id="lang-list">
                    <option value="Java"></option>
                    <option value="Python"></option>
                    <option value="C++"></option>
                    <option value="C#"></option>
                </datalist>
            </p>
            <div style="display: flex;">
                <label for="message" style="margin-right: 70px;">Your Message</label>&nbsp;&nbsp;
                <textarea name="message" id="message" cols="30" rows="6" placeholder="Leave your meassage here"></textarea>
            </div>
            <div class="btn" style="display: flex;">
                <button id="form-btn"type="submit">Submit</button>
                <button id="form-btn" type="reset">Reset</button>
            </div>
          
        </fieldset>
    </form>
</section>
<br>
<h1> CSE Time Table</h1>
<section id="time">
   <details>
    <summary>Anna University Regional Campus Tirunelveli - CSE Department </summary>
    <p>
        8th Semester timetable.
        Click here to see the <a href="Timetable.html">TIME TABLE</a>
    </p>
   </details>
</section>
    </main>

    
<footer>

    <section id="third">
        <p>
            <hr><br>
             &lt;&lt;&lt; &copy; <a href="PR.html">PR </a>&gt;&gt;&gt;
        </p>
    </section>
    <p>
        <a href="#">Back to top</a>
        <br>
    </p>
</footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Author</title>
     <style>
        body
        {
            overflow: hidden;
            background-color: rgb(4, 24, 66);
            color: whitesmoke;
        }
        .container 
        {
            height: 100vh;
            display: flex;
            justify-content: center;
            
        }

        .container .auth-cont
        {
            width: 700px;
            height: 500px;
            background-color: #450094;
            margin-top: 30px;
            border-radius: 10px;
            padding: 20px;
            font-size: 20px;
        }
        img{
            border-radius: 15px;
            background-color: #450094;
        }
        a
        {
            color: whitesmoke;
        }
     </style>
</head>

<body>
    <h2><a href="index.html">HOME</a> </h2>
    <div class="container">
        
        <div class="img-cont">
            <figure>
                <img src="https://t3.ftcdn.net/jpg/03/94/96/38/240_F_394963897_S5JAvnyyLA6YdirGrgqHXKDZmImlouK7.jpg" alt="PR Logo">
                <figcaption>PR CREATION</figcaption>
            </figure>
        </div>
        <div class="auth-cont">
           <ul>
            <li>
                This page is created by PR. He is currently studying in <strong>Anna University Regional Campus Tirunelveli.</strong>
            </li><br><br>
            <li>He is the best programmmer in<abbr title="Computer Science Engineering"> CSE </abbr> Department.
            </li><br><br>
            <li>His goal is to become a Full stack developer.</li>
            <br><br>
            <li>He is the best in playing chess and drawing.</li>
            <br><br>
            <li>This is the basic web page for beginners.</li>
            <br><br>
            <li>
                Some HTML tags and CSS property were covered in this page and all are basic concepts.
            </li>
           </ul> 

           
        </div>
   
</div>
    
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time table</title>
    <style>
        body{
            display: flex;
            flex-direction: column;
            justify-content: center;
            background-color: aqua;
        }
        table,caption,th,tr,td
        {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 10px;
            text-align: center;
            font-size: 16px;
        }
        caption,td{
            font-family:'Courier New', Courier, monospace;
            font-size: 18px;
            font-weight: 600;
        }
        th{
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        th:nth-child(4)
        {
            border-bottom-color: aqua;
            background-color: aqua;
        }
        th:nth-child(7)
        {
            border-bottom-color: aqua;
            background-color: aqua;
        }
        th:nth-child(10)
        {
            border-bottom-color: aqua;
            background-color: aqua;
        }
        tr:nth-child(even)
        {
            background-color: rgb(4, 24, 66);
            color: whitesmoke;
        }
        
     
    </style>
</head>
<body>
    <H2><a href="index.html">HOME</a> </H2>
    <table>
        <caption>TIME TABLE</caption>
        <tr>
            <th>Hours</th>
            <th>1</th>
            <th >2</th>
            <th>&nbsp;</th>
            <th>3</th>
            <th>4</th>
            <th></th>
            <th>5</th>
            <th>6</th>
            <th></th>
            <th>7</th>
            <th>8</th>
        </tr>
        
        <tr>
            <th>Days</th>
            <th>9.00-9.50 AM</th>
            <th>9.50-10.40 AM</th>
            <th></th>
            <th>11.00-11.50 AM</th>
            <th>11.50-12.40 AM</th>
            <th></th>
            <th>1.30-2.20 PM</th>
            <th>2.20-3.10 PM</th>
            <th></th>
            <th>3.20-4.10 PM</th>
            <th>4.10-5.00 PM</th>
        </tr>
       
        <tr>
            <th>Monday</th>
            <td colspan="2">CS8661 MNB/CS8662 EGJ</td>
            <td style="border-block-color: aqua;">B</td>
            <td colspan="2">CS8661 MNB/CS8662 EGJ</td>
            <td style="border-block-color: aqua;">L</td>
            <td>CS8602/CA</td>
            <td></td>
            <td style="border-block-color: aqua;">B</td>
            <td colspan="2"></td>
        </tr>
       
        <tr>
            <th>Tuesday</th>
            <td>CS8602/CA</td>
            <td>CS8651/MNB</td>
            <td style="border-block-color: aqua;background-color: aqua;color: black;">R</td>
            <td>CS8691/JR</td>
             <td>CS8603/SS</td>
             <td style="border-block-color: aqua;background-color: aqua;color: black;">U</td>>
            <td colspan="2">CS8661/MNB</td>
            <td style="border-block-color: aqua;background-color: aqua;color: black;">R</td>
            <td colspan="2">CS8661/MNB</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>CS8651/MNB</td>
            <td>CS8603/SS</td>
            <td style="border-block-color: aqua;">E</td>
            <td>CS8601/EGJ</td>
             <td>CS8691/JR</td>
             <td style="border-block-color: aqua;">N</td>>
            <td colspan="2">HS8581/DC</td>
            <td style="border-block-color: aqua;">E</td>
            <td colspan="2"></td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td>CS8601/EGJ</td>
            <td>CS8691/JR</td>
            <td style="border-block-color: aqua;background-color: aqua;color: black;">A</td>
             <td colspan="2">CS8602/CA</td>
             <td style="border-block-color: aqua;background-color: aqua;color: black;">C</td>>
            <td colspan="2">CS8662/EGJ</td>
            <td style="border-block-color: aqua;background-color: aqua;color: black;">A</td>
            <td colspan="2">CS8662/EGJ</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>CS8603/SS</td>
            <td>CS8601/EGJ</td>
            <td >K</td>
             <td>CS8602/CA</td>
             <td>CS8651/MNB</td>
             <td >H</td>>
            <td colspan="2">CS8661/SS</td>
            <td>K</td>
            <td colspan="2"></td>
        </tr>
    </table>
    <br>
    <br>
    <table class="name">
        <tr class="row-name">
            <th>S.NO</th>
            <th>SUB CODE</th>
            <th colspan="3">SUB NAME</th>
            <th>STAFF NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>CS8651</td>
            <td>Internet Programming</td>
            <td>3</td>
            <td>3</td>
            <td>Dr.M.Nava Barathy</td>
        </tr>
        <tr>
            <td>2</td>
            <td>CS8691</td>
            <td>Artificial Intelligence</td>
            <td>3</td>
            <td>3</td>
            <td>Dr.J.Roselin</td>
        </tr>
        <tr>
            <td>3</td>
            <td>CS8601</td>
            <td>Mobile Computing</td>
            <td>3</td>
            <td>3</td>
            <td>Dr.E.Golden Julie</td>
        </tr>
        <tr>
            <td>4</td>
            <td>CS8602</td>
            <td>Compiler Design</td>
            <td>5(3T+2P)</td>
            <td>4</td>
            <td>Dr.C.Akila</td>
        </tr>
        <tr>
            <td>5</td>
            <td>CS8603</td>
            <td>Distributed Systems</td>
            <td>3</td>
            <td>3</td>
            <td>Dr.S.Sabena</td>
        </tr>
        <tr>
            <th colspan="6" >PRACTICALS</th>
        </tr>
        <tr>
            <td>1</td>
            <td>CS8661</td>
            <td>Internet Programming Laboratory</td>
            <td>4</td>
            <td>2</td>
            <td>Dr.M.Nava Barathy</td>
        </tr>
        <tr>
            <td>2</td>
            <td>CS8662</td>
            <td>Mobile Computing Laboratory</td>
            <td>4</td>
            <td>2</td>
            <td>Dr.E.Golden Julie</td>
        </tr>
        <tr>
            <td>3</td>
            <td>CS8611</td>
            <td>Mini Project</td>
            <td>2</td>
            <td>1</td>
            <td>Dr.S.Sabena</td>
        </tr>
        <tr>
            <td>4</td>
            <td>HS8581</td>
            <td>Professional Communication</td>
            <td>2</td>
            <td>1</td>
            <td>Mr.D.Christopher</td>
        </tr>
        
    </table>
</body>
</html>
