<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Inbox - Primary</title>
    <link href='http://fonts.googleapis.com/css?family=Roboto:400,700' rel='stylesheet' type='text/css'>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            height: 100%;
            font-family: 'Roboto', sans-serif;
            font-size: 14px;
            line-height: 24px;
        }

        header, section.pane {
            padding: 1em 0.5em 0.6em 1em;
        }

        header {
            height: 52px;
            background-color: #DA4336;
            color: white;
            vertical-align: top;
        }

       
        header h1 {
            display: inline;
            font-size: 1rem;
            font-weight: normal;
            vertical-align: top;
          margin-left:50px;
        }

        section.side  {
            position: absolute;
            top: 52px;
            left: 0;
            width:64px;
            bottom: 0;
            background-color: white;
         height:110%;
        }
        section.mainarea {
            position: absolute;
            top: 52px;
            left: 64px;
            right: 0;
            bottom: 0;
            background-color: white;
            box-shadow: -1px 0px 6px #CCC;
        }

        section.list,
        section.content {
            position: absolute;
            top: 0;
            bottom: 0;
            background-color: white;
            box-shadow: -1px 0px 6px #CCC;
            overflow-y: scroll;
        }

        section.list {
            width: 40%;
            left: 0;
            z-index: 1;
          height:180%;
        }
        section.content {
            width: 60%;
          height:180%;
            right: 0;
        }
      span.클릭{
        color:blue;
      }
      .메뉴{position:absolute;
   top:14px;
   left:7px;
   width:30px;
   margin:0;   
 }
    
    .검색{position:absolute;
      background-color:#da4336;
      width:33px;
        margin:0;
        left:400px;
       top:12px;
          }
    .local1{position:absolute;
          width:20px;
        margin:0;
        left:1050px;
       top:13px;
     
    }
      .폴더{position:absolute;
          width:24px;
        margin:0;
        left:1023px;
       top:17px;
     
    }
        .메세지{position:absolute;
          width:27px;
        margin:0;
        left:990px;
       top:17px;
        }
       .휴지통 {position:absolute;
          width:27px;
        margin:0;
        left:960px;
       top:11px;
        }
      ul{
        list-style-type:none;
        padding:0px;
        margin:5px 0px 30px 0px;
      }
h3{
  margin-bottom:3px;
  font-size:15px;
}
      h2{
        font-size:17px;
      }
.new{float:right;
  background-color:blue;
  color:white;   
  padding:0px 1px;
 
 

    }
.new1{float:right;
  background-color:green;
  color:white;
   padding:0px 1px;
    }
      .new2{float:right;
  background-color:orange;
  color:white;
          padding:0px 1px;
      
    }
      li{
          font-size:8pt;
      color:gray;
    
       
      }
     .clock{
       float:right;
     }
      .box{ 
      float:right;
        background-color:red;
        color:white;
        padding:0px 5px;
        
      }
       .box1{ 
      float:left;
        background-color:red;
        color:white;
        padding:0px 5px;
        
      }
      
      div.항목{
      border-bottom:1px solid #dfe0e4;
        
            }
      .아래항목{
        padding-top:10px;
      }
      .프로필{
          width: 30px;
      height: 30px;
      margin-bottom: -45px;
      border-radius: 20px;
      }
            .프로필1{ position:absolute;
          width: 30px;
      height: 30px;
      margin-bottom: -45px;
      border-radius: 20px;
              top:410px;
      }
      
            .프로필2{ position:absolute;
          width: 30px;
      height: 30px;
      margin-bottom: -45px;
      border-radius: 20px;
              top:480px;
      }
      .날짜{
        float:right;
      }
      .별{float:right;
        width:35px;
      
      }
      .inbox{
        position:absolute;
        width:35px;
        top:120px;
        left:10px;
      }
      .people{
         position:absolute;
        width:34px;
        top:170px;
        left:11px;
        
      }
            .local{
         position:absolute;
        width:34px;
        top:220px;
        left:12px;
        
      }
         .info{
         position:absolute;
        width:27px;
        top:270px;
        left:16px;
        
      }
      
    </style>
</head>    
<body>
    <header>
<img class="메뉴" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/메뉴icon.png" alt="메뉴">
  
<img class="검색" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/검색icon.png" alt="검색"> 

<img class="local1" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/move icon.png" alt="local"> 

<img class="폴더" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/폴더 icon.png" alt="폴더"> 

<img class="메세지" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/메세지icon.png" alt="메세지"> 

<img class="휴지통" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/휴지통icon.png" alt="휴지통"> 
      
<img class="휴지통" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/휴지통icon.png" alt="휴지통"> 
 
      
<h1>Primary</h1>
    </header>
  
    <section class="side pane">
  
        <img class="프로필" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/nhnsvc.jpg" alt="프로필">
      <div class="icon">
<img class="inbox" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/inbox1.PNG"
     alt="inbox">
        
        <img class="people" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/people.PNG"
     alt="people">
            <img class="local" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/local.PNG"
     alt="local">
        
        <img class="info" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/info.PNG"
     alt="info">
        
      </div>
       <img class="프로필1" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/프로필1.PNG" alt="프로필">
      <img class="프로필2" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/프로필1.PNG" alt="프로필">
    </section>
  
    <section class="mainarea">
        <section class="list pane">
    <div class="항목"> 
      <h3>social</h3>
 <ul>
  <li class="new">1 new</li>
   <li class="아래항목">google+</li>
  
</ul>
          </div>
          
  <div class="항목">  
    <h3>Promotions</h3>
 <ul>
   <li class="new1">2 new</li>
   <li>Zagat, Google Offers</li>
 
</ul>
          </div>
            <div class="항목"> 
              <h3>Updates</h3>
<ul>
  <li class="new2">1 new</li>

  <li>google play</li>

</ul>  
          </div>

  <div class="항목">  
    <h3>Andy Brown</h3>
          <ul>
            <li class="clock">1:45pm</li>


    <li class="아래항목">hello!!I'm trying to schedule a board game night this week, when would you be..</li>
                         <li class="box">work</li>
 
</ul>  
          </div>
          <div class="항목">  
            <h3>Andy Brown</h3>
          <ul>

<li>hello!!</li>
</ul> 
          </div>
          
  <div class="항목">
    <h3>Andy Brown</h3>
          <ul>

<li>hello!!</li>
</ul> 
          </div>
            <div class="항목">  
              <h3>Andy Brown</h3>
           <ul>

<li>hello!!</li>
</ul> 
          </div>
        
        </section>
        <section class="content pane">
          <div class="항목"> 
            <h2>Board game now?</h2>
            <ul>
              <li><img class="별" src="https://googledrive.com/host/0B4o_ybv-191Cd00tdXZtSEp6cnc/별icon.png" alt="별"></li>
         
              <li>fun</li>
              <li>inbox</li>
             

            </ul>
          </div>
                 <div class="항목"> 
                    <h3>Regis Miller</h3>
            <ul>
                <li class="날짜">sep 29</li>
             
             
              <li> I'm trying to schedule a board game night this week, when would you be...</li>
             
            </ul>
          </div>
          </div>
                 <div class="항목"> 
                     <h3>Peter Johnson</h3>
            <ul>
                <li class="날짜">sep 29</li>
            
               
              <li> I'm trying to schedule a board game night this week, when would you be...</li>
             
            </ul>
          </div>
      
       <div class="항목"> 
         <h3>Rachel Shin</h3>
             <ul>
                <li class="날짜">sep 29</li>
              
               
              <li>to me</li>
               <li>spe 29 <span class="클릭 ">view details</span></li>
               <li class="내용">Sunday works! If you can get Dexter and Sophie I will handle the chips and salsa.
                 <br>
                 <span class="클릭">▶ Show quoeted text</span>

</li>
              
            </ul>
      </div>
 
      
        </section>
    </section>
  </body>
</html>
