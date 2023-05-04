# Job-Application-Form
<!DOCTYPE html>
<html>
    <head>
        <meta charsset="UTF-8" />
        <meta name="viewport" content="width=divice-width, initial-scale=1.0" />
        <title>job application form </title>
        <link rel="stylesheet" href="jobapplication.css" />

    </head>
    <body>
        <div class="container">
            <div class="apply_box">
                <h1>Job Application
                 <span class="web">(web)</span>
                </h1>
                <form action="" method="post">
                    <div class="form_conatiner">
                        <div class="form_control">
                            <label for="first_name">First Name</label>
                            <input id="first_name" type="text" name="first_name" placeholder="Enter Your First Name" autofocus required/>
                        </div>
                        <div class="form_control">
                            <label for="last_name">Last Name</label>
                            <input id="last_name" type="text" name="last_name" placeholder="Enter Your Last Name"  required/>
                        </div>
                        <div class="form_control">
                            <label for="email">Email</label>
                            <input id="email" type="email" name="email" placeholder="Enter Your Email"  required/>
                        </div>
                        <div class="form_control">
                            <label for="job_role">Job Role</label>
                            <select id="job_role" required>
                                <option value="">Select Job Role</option>
                                <option value="frontend">Frontend Developer</option>
                                <option value="backend">Backend Developer</option>
                                <option value="full_stack">Full Stack Developer</option>
                                <option value="ui_ux">UI UX Designer</option>
                            </select>
                        </div>
                        <div class="form_control">
                            <lable for="address">Address</lable>
                            <textarea id="address"  required >Enter your Address  </textarea>
                        </div>
                        <div class="form_control">
                            <label for="city">City Name</label>
                            <input id="city" type="text" name="city" placeholder="Enter Your City Name" required />
                        </div>
                        <div class="form_control">
                            <label for="pin_code">Pin Code</label>
                            <input id="pin_code" type="number" name="pin_code" placeholder="Enter Your Pin Code" required />
                        </div>
                        <div class="form_control">
                            <label for="date">Date</label>
                            <input id="date" type="date" name="date" placeholder="Enter Date" required />
                        </div>
                        <div class="form_control">
                            <label for="upload_cv">Upload Your CV</label>
                            <input id="upload_cv" type="file" name="upload_cv" placeholder="Upload Your CV" required />
                        </div>

                    </div>
                    <div class="button_container">
                       <span> <button type="reset" >Reset</button></span>
                       <span> <button type="submit">Apply Now</button></span>
                    </div>
                    
                </form>

            </div>
        </div>

    </body>
</html>
