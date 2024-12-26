# first-coding-for-me-with-html-css
my first web for me its not so good , bec i try to laern and do what i can do 

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>e.gu4  </title>

        <link rel="website icon" type="png" href="icon.jpg">
        <body>
        <style>
            table, th, td, caption {
                border: 2pt solid black; 
            } 

        </style> 
      </body>
        <link rel="stylesheet" href="style.css">
        <!-- هذا للبرمجة -->
    <body dir="rtl">

        <header>
            <footer>
            <h1> تجربه الموقع </h1> <!-- h1 يرمز لحجم الخط-->
        </footer>
        <hr>
        </header>
        <section>
            <footer>
            <h3>هذا هو موقعي الاول</h3> 
            <p>انا افضل آنا</p> <br><br><hr><!--النص-->
            <p>صوره تجريبيه</p><br><br>
            <img src="test.jpg" height="200" width="150" alt="تعذر العرض">
            </footer>
            <hr> <!--خط-->
            </section>
            <header>
            <section>
                <footer>
            <h3>فورم تجريبي</h3> 
            <from>
                <labe for="name">اسم المستخدم</label>
            <input type="text" id="name"> <br>
            
            <label for="number">العمر</label>
            <input type="text" id="number">
            
            <hr>
            <h3>ايش انت؟</h3>

            <input type="radio" id="male" name="gender">
            <label for="male">ذكر</label>
            <input type="radio" id="female" name="gender">
            <label for="female">انثى</label>
            <hr>
          <h3>كيف دخلت الموقع "لا تقول مني تكفى"</h3>
          <p>خيارات متعددة</p><br>
        <input type="checkbox" id="from you" name="from you">
         <label for="from you">منك </label><br>
         <input type="checkbox" id="not from you" name="not from you">
         <label for="not from you">مو منك</label><br>
         <input type="checkbox" id="i found it" name="i found it">
         <label for="i found it">لقيته</label><br><br>
          
         <h3>وين ساكن؟</h3>
         <select id="city" name="city">
            <option value="...">...</option>
            <option value="الرياض">الرياض</option>
            <option value="القصيم">القصيم</option>
            <option value="مصر">مصر</option>
            <option value="المدينة المنورة">المدينة المنورة</option>

        </select> <br>
         <br>

         <input type="submit" value="انتهى">
        
        </from>


        </footer>
    </header>
            </section>
        <hr>
            <section>
            <footer>
            <h3>اهم الاشياء التي تحتاجها</h3>
            <ol class="list">
                <li>الاشياء الاولى</li>
                <li >الاشياء الثانيه</li>
                <li>الاشياء الثالثه</li>
                <li>عبدالله AB</li>
            </ol>
            </footer>
            <script>

          
         let ios = document.querySelectorAll("li")
         ios.remove();
         
            </script>

     <hr>
        <section>
        <footer>
            <h3>اهم الاشياء التي تحتاجها</h3>
    <input type="text" id="search" onkeyup="onsearch()" placeholder="ابحث هنا...">
    
    
                  
            
            </footer>
            
             </section>
                <hr>
            <section>
             <footer>
              <e>فيديو تجريبي</e><br>
           <video width="400" height="400" controls>
            <source src="vid.mp4 " type="video/mp4"> 
           </video> 
           </footer>
            </section>
        <hr>
            <section>
                <footer>
            <p>تسجيل  صوتي تجريبي 3> </p> <br><br>
                
             <audio controls>
                <source src="1000229066.mp3" type="audio/mp3">
             </audio>
            </section>
            <hr>
        </footer>
            <section>
                <footer>
             <p><h2>جدول تجريبي</h2></p> 
              
             <table>

            <caption>هنا عنوان الجدول المفروض</caption>
               
             <th>اليوم</th>
             <th>الوقت</th>
             
            </tr>

            <tr>
             <td> الاربعاء</td>
             <td>5:54am</td>

              </tr>
             
              <tr>
              <td> الخميس</td>
              <td>10:30pm</td>

              </tr>

             <tr>

            <td>الاحد</td>
            <td>5:30pm</td>    
             </tr>

             <tr>

            <td colspan="2"> يوم الاثنين فراغ</td>    
             </tr>
              </table>
            </footer>

            </section>
         <hr>
            
         <footer>            
                <div>
                    Oh, simple thing, where have you gone?
                    I'm getting old, and I need something to rely on
                    So, tell me when you're gonna let me in
                    I'm getting tired, and I need somewhere to begin
                
                </div>
            </footer>
<hr>

<Style>
    .box {
        background-color: #090c0c;
        width: 500px;
        height: 50px;
        border: 15px solid rgba(6, 10, 16, 0.347);
        padding: 50px;
        margin: 20px;
    }
</Style>

        <marquee direction="reverse">
            شرايكم بالحركه
        </marquee>
    
        <hr>
       

        <hr>
         
          <h5>clicks:<span id="clicks">0</span></h5>
          <button type="button" onclick="add()">+</button>

          <script>
            let cliks = 0;
            function add() {
              cliks++;
              document.getElementById("clicks").innerText = cliks;
            }
          </script>

        <footer> 
            <p>جميع المراجع</p>
         <a href="https://www.google.com/search?gs_ssp=eJzj4tTP1TewzEouK1ZgNGB0YPBir8wvLSlNSgUAUQAG7g&q=youtube&rlz=1C1VDKB_enSA1122SA1122&oq=&gs_lcrp=EgZjaHJvbWUqDwgAEC4YJxjHARjqAhjRAzIPCAAQLhgnGMcBGOoCGNEDMgkIARAjGCcY6gIyCQgCECMYJxjqAjIPCAMQLhgnGMcBGOoCGNEDMgkIBBAjGCcY6gIyCQgFECMYJxjqAjIJCAYQIxgnGOoCMgkIBxAjGCcY6gLSAQw0MDcwODIxN2owajeoAgiwAgE&sourceid=chrome&ie=UTF-8">هنا</a>

            </footer> <br>

        <footer>
            <p> <h2>نهاية الموقع  </h2>
        
        

        </footer>
        <script src="script.js"></script>
    </body>
</html>


(and this is css)

body {
    background-color: rgb(246, 248, 249);
    background-image: url("icon.jpg");
    background-attachment: fixed;
    background-size: 100% 100%;
    margin: 0px 500px 0px 500px;
}
    background-image {
        position: fixed;
        top: 0px;
     }
    


p {
    color: rgb(6, 8, 9);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    display: inline;
   }
   
   a {
       color: #d3d7d7;
       background-color: rgb(35, 91, 110);
       font-size: 16px;
       font-weight:bolder;
       display: inline;
   }
   a:hover {
       color: rgb(190, 28, 28);
       background-color: #d3d7d7;
   }
   h1 {
       color: rgb( 250, 250, 250);
       background-color: rgb(35, 91, 110);
      border-style: solid;
       border-color: rgb(11, 10, 10);
       border-width: 1.5px;
       border-radius: 10px;
       position: sticky;
       top: 0px;
       text-align: center; 
       
   }
   
   h2 {
 border-style: double;
 border-color: rgb(11, 10, 10);
       border-width: 1.5px;
       border-radius: 10px;
       color: rgb(208, 216, 219);
       background-color: rgb(3, 51, 70);
       text-align:center;
   }
   h3 {
       color: rgb(236, 240, 242);
   background-color: rgb(7, 67, 91);
   border-style : solid;
   border-width: 1.5px;
   border-radius:5px;
   border-color: rgb(11, 10, 10);
   text-align: center;
   position: static;
   top: 0px;
   
   }

   footer {
    color: rgb(236, 240, 242);
    background-color: rgb(210, 213, 215);
    border-style : solid;
    width: 700px;
    border-width: 1.5px;
    border-radius:10px;
    text-align: center;
    border-color: rgb(11, 10, 10);
  
   }

   label, labe {
    color:black;
   } 

   th, td, caption {
    color :black;
   }

    ol, ul {
    color :black;
    text-align: right;
   }

   audio {
    color :black;
    text-align: right;
   }


   marquee {
text-align: center;

   }

   hr {
    color:rgb(6, 8, 9);

   }

   .box {
    background-color: #009999;
    width: 500px;
    height: 50px;
    border: 15px solid rgba(4, 73, 157, 0.347);
    padding: 50px;
    margin: 20px;
   }

   table {
    width: 600px;
    height: 0px;
    position: relative;
    right: 60px;
    bottom: 16px
   }
   e { color: rgb(6, 8, 9);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    display: inline;
    position: relative;
top: 10px;
   }
   video {
    position: relative;
    bottom: 40px;
    
   }

   

