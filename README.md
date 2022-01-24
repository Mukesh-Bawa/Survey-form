<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&family=Signika+Negative:wght@300&display=swap">
<style>
  :root{
    --font-family: 'Poppins', sans-serif;

    --color-white: #f3f3f3;
    --color-darkblue: #1b1b32;
    --color-darkblue-alpha: rgba(27,27,50,0.8);
    --color-green: #37af65; 
     
    --accent-left: rgba(58,58,158,0.8);
    --accent-right: rgba(136,136,206,0.7);

    --size-subheading: 1.125rem;
    --size-lable: 1.125rem;
}

   
   

*,
::before,
::after{
    box-sizing: border-box;
}

body{
    --font-family: var(--font-family);
    font-weight: 400;
    line-height: 1.6;
    background: linear-gradient( to right, var(--accent-left), var(--accent-right)),
    url("https://imgur.com/GevQBct.jpeg");
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    color: var(--color-white);
    margin: 0;

}

button,input,textarea,select{
    font-family: inherit;
}
    
.container{
    margin: 3.125rem auto;
    text-align: center;
    font-weight: 400;
    font-size: 25px;
}

.text-center{
    text-align: center !important;
    
}

.description{
    font-size: var(--size-subheading);
    margin: 1rem auto;
   }


header{
   
    padding: 2rem 1rem 1rem 1rem;
    text-shadow: 1px 1px #333333;
    
}

h1{
    font-weight: 400;
    line-height: 1.2;
    margin: 0;
   
}

form{
    background: var(--color-darkblue);
    padding: 2.5rem 0.625rem;
    border-radius: 0.3rem;
    width: 60%;
    margin: auto;
    height: auto;

}

.form-group{
    display:flex;
    flex-direction: column;
    margin: 2rem;
    font-size: 1.1rem;

}

.form-group p{
    line-height: 1;
    margin: 0.5rem 0.1rem;

}

.form-label{
    font-size: var(-size-lable);
}

.Form-control{
    display: block;
    width: 100%;
    font-size: 1rem;
    height: 2.5rem;
    padding: 0.375rem 0.75rem;
    border-radius: 0.3rem;
    border:1px solid #dddddd;
    margin-top: 0.4rem;

}

input[type="radio"],
input[type="checkbox"]{
    width: 1rem;
    height: 1rem;
}

input[type="checkbox"]{
    margin-right: 0.5rem;
}

textarea{
    font-size: 1.2rem;
    padding: 0.375rem 0.75rem ;
    width: 100% ;
    height: auto ;
    border: none;
    margin: 0.5rem 0;
    border-radius: 0.5rem;
}
 button{
     background-color:var(--color-green);
     border: none;
     cursor: pointer;
     color: var(--color-white);
     padding: 0.80rem;
     font-size: var(--size-lable);
     border-radius: 0.8rem;
 }

</style>  
  
  
  
</head>
<body>
    
   <div class="container">
        <header id="text-center">
            <h1>Survey Form</h1>
             <p id="discription">
            <em>Thank you for taking the time to help us improve the platform </em></p> </header> 
    </div>
    <form action="#" id="Survey Form" class="form-label">
    <div class="form-group">
        <label for="Name" id="name">Name :</label>
            <input type="text"
               id="Name"
               class="Form-control"
               placeholder="Enter Your Name" 
               required
            /></div>
    <div class="form-group">
        <label for="Email" id="Email">Email :</label>
            <input type="text"
                id="Email"
                class="Form-control"
                placeholder="Enter Your Email"  
                required
            /></div>
              <div class="form-group">
                <label for="Number" id="Number">Age :</label>
                    <input type="Number" min="10" max="99"
                        id="Age"
                        class="Form-control"
                        placeholder="Enter Your Age" 
                        required
                    /></div>

                 <div class="form-group">
                     <label for="dropdown"  >Which option best describes your current role? </label>
                     <select name="dropdown" id="dropdown" class="Form-control">
                        <option >Select Current Role</option>
                        <option disabled>current role</option>
                        <option value="Student">Student</option>
                        <option value="Full-time job">Full Time Job</option>
                        <option value="Full-time Learner">Full Time Learner</option>
                        <option value="Prefer not to say">Prefer Not To Say</option>
                        <option value="Other">Other</option>
                    </select>
                 </div>

                 <div class="form-group">
                     <p>Would you recommend this to a friend?</p>
                     <P>
                         <label >
                             <input type="Radio" name="answer" id="definately" checked>Definitely
                         </label>
                    </P>
                     <P>
                        <label >
                            <input type="Radio" name="answer" id="Maybe">Maybe
                        </label>
                   </P>
                   <P>
                    <label >
                        <input type="Radio" name="answer" id="Not-Sure" >Not Sure
                    </label>
                  </P></div>
                  <div class="form-group">
                    <label for="dropdown">What is your favorite feature?</label>
                    <select name="dropdown" id="dropdown" class="Form-control">
                        <option value="Challenge">Select Favorite Feature</option>
                       <option disabled>current role</option>
                       <option value="Challenge">Challenge</option>
                       <option value="Project">Project</option>
                       <option value="Community">Community</option>
                       <option value="Open Source">Open Source</option>
                       <option value="Other">Other</option>
                   </select>
                </div>
                <div class="form-group">
                <p>What would you like to see improved? (Check all that apply)</p>
                   <label >
                    <input type="Checkbox"
                     id="Checkbox" 
                     value="Front-end Project"/>Front-End Project
                    </label>
                    <p>
                    <label >
                        <input type="Checkbox"
                         id="Checkbox" 
                         value="Back-end Project"/>Back-End Project
                        </label>
                    </p>
                    <p>
                        <label >
                            <input type="Checkbox"
                             id="Checkbox" 
                             value="Challenges"/>Challenges
                            </label>
                        </p>
                        <p>
                            <label >
                                <input type="Checkbox"
                                 id="Checkbox" 
                                 value="Video"/>Video
                                </label>
                            </p>
                            <p>
                                <label >
                                    <input type="Checkbox"
                                     id="Checkbox" 
                                     value="Wiki"/>Wiki
                                    </label>
                            </p></div>
                            <div class="form-group">
                                <p>Any comments or suggestions?</p>
                                <textarea name="comments" id="comments" cols="50" rows="6"
                                placeholder="Enter Your Comment here.." required></textarea>
                                <div class="form-group">
                                    <button type="submit" id="submit">Sumbit</button>
                                </div>
                           

      </div>

    </form>

</body>
</html>
