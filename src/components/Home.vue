<template>
    <div>
       
        <div id="home-page" class="home-height  p-4"> 
            <div class="container pt-3">
                <div class="row pb-5">
                    <div class="col-lg-6 col-md-10 " >
                     <marquee width="60%" direction="left" height="100px">
                     <h1> <i class="fab fa-angellist"></i>Welcome to My portfolio <i class="fab fa-angellist"></i></h1>
                    </marquee>

                     <img src="https://scontent.fbom12-1.fna.fbcdn.net/v/t1.6435-9/81458001_2873208282905552_6881817624410324992_n.jpg?_nc_cat=109&ccb=1-5&_nc_sid=174925&_nc_ohc=Lqqd74By05UAX_7oRRs&_nc_oc=AQm48J3Kde1UXwSAzo9n71yJWgW5Y6Z40m1fPTn-kZgH6WsdI4l3izkfnoQb8RogKmo&_nc_ht=scontent.fbom12-1.fna&oh=feac6eb5c06c74de36ad8dee3415dd28&oe=6142A296" class="MyImg"/>
                    <h1> <i class="fab fa-app-store-ios"></i>akash Patale </h1>
                    <h3 style="color:grey">{{title}}</h3>
                    <button class="HireBtn">Hire Me</button>
                    <hr/>

        <p class="dummy-text">
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        scrolls in the upper direction.

        </p>
                    </div>

                    <div class="col-6">

                       
                    </div>
                </div>
            </div>


        </div>
        
         <div id="home-page" class="bg-default p-4"> 
            <h2 style="marginBottom:3%"> Featured Projects  <hr style="width:30%;margin:auto;marginTop:1%"/></h2>
           <!-- ****************First Div*********************** -->
             <div class="container pt-3">
                <div class=" row pb-5">
                    <div class=" secondDiv col-lg-6 col-md-10 col-sm-11" >
                       <h4>Portfolio Made by HTML/CSS JavaScript</h4>
                       <div class="vl">

                       <p class="dummy-text"> This is a sample scrolling text that has scrolls in the upper direction.
                        A sample scrolling text that has scrolls in the upper direction.A sample scrolling text that has scrolls in the upper direction.</p>
                        <button class="HireBtn">GitHub</button>
                   </div>
                    </div>

                     <div class=" col-lg-6 col-md-10 col-sm-11" >
                         <div>
                             <img src="data:image/jpeg;base64,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" class="React-img"/>
                         </div>
                        
                    </div>

               <!-- ****************second Div*********************** -->

                    <div class=" firstDiv col-lg-6 col-md-10 col-sm-11" style="marginTop:6%" >
                         <div>
                             <img src="https://reactjs.org/logo-og.png" class="React-img"/>
                         </div>
                        
                    </div>
                     <div class=" firstDiv col-lg-6 col-md-10 col-sm-11" style="marginTop:6%" >
                       <h4>Portfolio Made by React js</h4>
                       <div class="vl">

                       <p class="dummy-text"> This is a sample scrolling text that has scrolls in the upper direction.
                        A sample scrolling text that has scrolls in the upper direction.A sample scrolling text that has scrolls in the upper direction.</p>
                                                <button class="HireBtn">GitHub</button>

                     </div>

                   
                    </div>

               <!-- ****************Third Div*********************** -->

                   
                     <div class="  secondDiv col-lg-6 col-md-10 col-sm-11" style="marginTop:6%" >
                       <h4>Portfolio Made by Vue js</h4>
                       <div class="vl">

                       <p class="dummy-text"> This is a sample scrolling text that has scrolls in the upper direction.
                        A sample scrolling text that has scrolls in the upper direction.A sample scrolling text that has scrolls in the upper direction.</p>
                           <button class="HireBtn">GitHub</button>
                   </div>

                        </div>

                         <div class="col-lg-6 col-md-10 col-sm-11" style="marginTop:6%" >
                         <div>
                             <img src="data:image/png;base64,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" class="React-img"/>
                         </div>
                        
                    </div>

            
                
                     

                </div>
             </div>



             </div>

        <div id="contact-page" class="contactpage p-4" > 
          <h2> Contact Me</h2>
          <form>
              <div>
                  <label for="name" >Enter Your Name</label>
                  <br/>
                  <input type="text" name="name" placeholder="Your Name" />
              </div>

              <div>
                  <label for="name" >Enter Your Email-ID</label>
                  <br/>
                  <input type="text" name="name" placeholder="Your EmaiID" />
              </div>

              <div>
                  <label for="name" >Enter Your Message</label>
                  <br/>
                  <input type="text" name="name" placeholder="Your Message for me" />
              </div>

              <div>
                  <button type="button" class="HireBtn">Contact Me</button>
              </div>
          </form>
        </div>

        <div id="home-page" class="Aboutmyself p-4">
            <h2>What Companies Think About Me  <hr style="width:50%;margin:auto;marginTop:1%;marginBottom:1%"/></h2> 
         <marquee width="80%" direction="up" height="250px">
             <h4>This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        scrolls in the upper direction.</h4>
    <br/>

       This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        This is a sample scrolling text that has scrolls in the upper direction.
        scrolls in the upper direction.

         </marquee>

            
        </div>

        <div id="footer-page" class="footer-page p-4"> 
            <h1>Have a Good Day..!</h1>
             
           
             <h5 style="margin-top:2%">&copy;2021 Developed By Aakash Patale  <hr style="width:50%;margin:auto;marginTop:1%;marginBottom:1%"/> </h5>
           
          </div>
      
              <div class="icon-bar">
  <a href="#" class="facebook"><i class="fa fa-facebook"></i></a> 
  <a href="#" class="twitter"><i class="fa fa-twitter"></i></a> 
  <a href="#" class="google"><i class="fa fa-google"></i></a> 
  <a href="#" class="linkedin"><i class="fa fa-linkedin"></i></a>
  <a href="#" class="youtube"><i class="fa fa-youtube"></i></a> 
</div>
     

    </div>
</template>

<script>
    export default {
        name:'Home',
        data(){
            return{
                title: 'Front-End Developer'
            }
        }
    }
</script>

<style scoped>
.home-page{
    background-image: url('https://previews.123rf.com/images/tirachard/tirachard1802/tirachard180200064/95656773-creative-flat-lay-photo-of-workspace-desk-top-view-office-desk-with-laptop-blank-empty-notebooks-and.jpg');
}

.MyImg{
    width:250px;
    height:250px;
    border-radius: 50%;
    border: 2px solid palevioletred;

}

.dummy-text{
    text-align:start;
    justify-content:start;
    
}

.TopDiv{
    background-color:grey;
    padding:10px;
}
.HireBtn{
    background-color:white;
    color: palevioletred;
    padding:6px 25px;
    border: 1px solid palevioletred;
    border-radius:30px;
}

.HireBtn:hover{
    background-color:palevioletred;
    color:white;
}
.vl {
  border-left: 6px solid green;
  height: 100px;
  padding:2%
}

.React-img{
width:300px;
border-radius: 20px;
}
.contactpage{
    background-color:pink
}
.contactpage form{
    background-color:white;
    width: 600px;
    margin:auto;
    height:420px;
    padding:2%;
    border-radius: 20px;
}
.contactpage form div{
    margin-top: 5%;
}
.contactpage form input{
    width:400px;
    text-align:center;
    padding:8px 20px;
    border:1px solid black;
    border-radius:10px
}
.contactpage form button{
    margin-top:4%
}

.Aboutmyself{
    height:450px;
}

.footer-page{
    height:150px;
    background-color:pink;
    justify-content: space-between;
}


.icon-bar {
  position: fixed;
  top: 50%;
  -webkit-transform: translateY(-20%);
  -ms-transform: translateY(-50%);
  transform: translateY(-40%);
}

.icon-bar a {
  display: block;
  text-align: center;
  padding: 16px;
  transition: all 0.3s ease;
  color: white;
  font-size: 20px;
}

.icon-bar a:hover {
  background-color: #000;
}

.facebook {
  background: #3B5998;
  color: white;
}

.twitter {
  background: #55ACEE;
  color: white;
}

.google {
  background: #dd4b39;
  color: white;
}

.linkedin {
  background: #007bb5;
  color: white;
}

.youtube {
  background: #bb0000;
  color: white;
}

.content {
  margin-left: 75px;
  font-size: 30px;
}

@media  screen and (max-width: 400px) {
  body{
          background-image: url("https://previews.123rf.com/images/tirachard/tirachard1802/tirachard180200064/95656773-creative-flat-lay-photo-of-workspace-desk-top-view-office-desk-with-laptop-blank-empty-notebooks-and.jpg");
 background-repeat: no-repeat;
  background-size: cover;
  overflow-x: hidden;

  }

  .MyImg{
    width:200px;
    height:200px;
    border-radius: 50%;
    border: 2px solid palevioletred;

}
.firstDiv{
    display:none
}

.secondDiv{
    margin-bottom:35%
}

.dummy-text{
    text-align:start;
    justify-content:start;
    
}

.TopDiv{
    background-color:grey;
    padding:10px;
}
.HireBtn{
    background-color:white;
    color: palevioletred;
    padding:6px 25px;
    border: 1px solid palevioletred;
    border-radius:30px;
}

.HireBtn:hover{
    background-color:palevioletred;
    color:white;
}
.vl {
  border-left: 6px solid green;
  height: 100px;
  padding:2%
}

.contactpage{
    background-color:pink
}
.contactpage form{
    background-color:white;
    width: 300px;
    margin:auto;
    height:420px;
    padding:2%;
    border-radius: 20px;
}
.contactpage form div{
    margin-top: 5%;
}
.contactpage form input{
    width:200px;
    text-align:center;
    padding:8px 20px;
    border:1px solid black;
    border-radius:10px
}
.contactpage form button{
    margin-top:4%
}

.Aboutmyself{
    height:450px;
}

.footer-page{
    height:150px;
    background-color:pink;
    justify-content: space-between;
}


.icon-bar {
 display:none
}


  
}


@media  screen and (min-width: 401px) and (max-width: 768px){
  body{
          background-image: url("https://previews.123rf.com/images/tirachard/tirachard1802/tirachard180200064/95656773-creative-flat-lay-photo-of-workspace-desk-top-view-office-desk-with-laptop-blank-empty-notebooks-and.jpg");
 background-repeat: no-repeat;
  background-size: cover;
  overflow-x: hidden;

  }

  .MyImg{
    width:250px;
    height:250px;
    border-radius: 50%;
    border: 2px solid palevioletred;

}
.firstDiv{
    display:none
}

.secondDiv{
    margin-bottom:20%
}

.dummy-text{
    text-align:start;
    justify-content:start;
    
}

.TopDiv{
    background-color:grey;
    padding:10px;
}
.HireBtn{
    background-color:white;
    color: palevioletred;
    padding:6px 25px;
    border: 1px solid palevioletred;
    border-radius:30px;
}

.HireBtn:hover{
    background-color:palevioletred;
    color:white;
}
.vl {
  border-left: 6px solid green;
  height: 100px;
  padding:2%
}

.contactpage{
    background-color:pink
}
.contactpage form{
    background-color:white;
    width: 300px;
    margin:auto;
    height:420px;
    padding:2%;
    border-radius: 20px;
}
.contactpage form div{
    margin-top: 5%;
}
.contactpage form input{
    width:200px;
    text-align:center;
    padding:8px 20px;
    border:1px solid black;
    border-radius:10px
}
.contactpage form button{
    margin-top:18%
}

.Aboutmyself{
    height:450px;
}

.footer-page{
    height:150px;
    background-color:pink;
    justify-content: space-between;
}


.icon-bar {
 display:none
}


  
}


@media  screen and (min-width: 769px) and (max-width: 1240px){
  body{
          background-image: url("https://previews.123rf.com/images/tirachard/tirachard1802/tirachard180200064/95656773-creative-flat-lay-photo-of-workspace-desk-top-view-office-desk-with-laptop-blank-empty-notebooks-and.jpg");
 background-repeat: no-repeat;
  background-size: cover;
  overflow-x: hidden;

  }

  .MyImg{
    width:250px;
    height:250px;
    border-radius: 50%;
    border: 2px solid palevioletred;

}
.firstDiv{
    display:block;
}

.secondDiv{
    margin-bottom:10%
}

.dummy-text{
    text-align:start;
    justify-content:start;
    
}

.TopDiv{
    background-color:grey;
    padding:10px;
}
.HireBtn{
    background-color:white;
    color: palevioletred;
    padding:6px 25px;
    border: 1px solid palevioletred;
    border-radius:30px;
}

.HireBtn:hover{
    background-color:palevioletred;
    color:white;
}
.vl {
  border-left: 6px solid green;
  height: 100px;
  padding:2%
}

.contactpage{
    background-color:pink
}
.contactpage form{
    background-color:white;
    width: 500px;
    margin:auto;
    height:420px;
    padding:2%;
    border-radius: 20px;
}
.contactpage form div{
    margin-top: 5%;
}
.contactpage form input{
    width:300px;
    text-align:center;
    padding:8px 20px;
    border:1px solid black;
    border-radius:10px
}
.contactpage form button{
    margin-top:10%
}

.Aboutmyself{
    height:450px;
}

.footer-page{
    height:150px;
    background-color:pink;
    justify-content: space-between;
}


.icon-bar {
 display:none
}


  
}




</style>