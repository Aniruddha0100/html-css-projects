# html-css-projects
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>job application form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="apply_box">
            <h1>Job Application 
            <span class="title_small">(Web)</span>
        </h1>
        <form action="">
            <div class="form_container">

<div class="form_control">
<label for="First_name">First Name</label>
<input id="First_name" name="First_name" placeholder="enter first name..."/>

</div>
 
<div class="form_control">
    <label for="Last_name">Last Name</label>
    <input id="Last_name" name="Last_name " placeholder="enter last name.."/>

</div>
<div class="form_control">
    <label for="email">email</label>
    <input type="email" id="email" name="email" placeholder="enter email"/>
</div>
<div class="form_control">
    <label for="job_role">Job Role</label>
    <select name="job_role" id="job_role">
        <option value="">select role</option>
        <option value="army">army</option>
        <option value="navy">navy</option>
        <option value="air_force">Air force</option>
    </select>
</div>

<div class="textarea_control">
    <label for="adress">Adress</label>
    <textarea 
    name="adress" 
    id="adress" 
    rows="4" 
    cols="50"
     placeholder="enter address">
</textarea>
</div>

    <div class="form_control">
        <label for="city">city</label>
        <input id="city" name="city" placeholder="enter name of your city.."/>
     </div>
    
     <div class="form_control">
        <label for="pincode"> Pincode </label>
        <input
          type="number"
          id="pincode"
          name="pincode"
          placeholder="Enter Pincode..."
        />
      </div>

      <div class="form_control">
        <label for="start_date"> start date </label>
        <input
          type="date"
          id="start_date"
          name="start_date"
        />
      </div>

      <div class="form_control">
        <label for="upload"> Upload Your CV </label>
        <input type="file" id="upload" name="upload" />
      </div>






</div>
<div class="button_container">
    <button type="submit">Submit</button>
</div>

            </div>
        </form>
        </div>
    </div>
</body>
</html>
