<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&family=Signika+Negative:wght@300&display=swap" rel="stylesheet">
    <title>Survey Form</title>
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
                            <input type="Radio" name="answer" id="Maybe" checked>Maybe
                        </label>
                   </P>
                   <P>
                    <label >
                        <input type="Radio" name="answer" id="Not-Sure" checked>Not Sure
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
