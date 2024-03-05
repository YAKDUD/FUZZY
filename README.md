<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>CHUBAKA GANG MEMBERSHIP</title>

 </head>  
 <body>  

     <h1>CHUBAKA GANG MEMBERSHIP</h1>
    
     <form>
        <section>
          <label for="fullname">Full Name:</label>
          <input type="text" id="fullname" name="fullname" required>
        </section>

        <section>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </section>

        <section>
        <label for="password">Password:</label>  
        <input type="password" id="password" name="password" required>
        </section>

        <section>
            <label for="gender">Gender</label>
            <select id="gender" name="gender">
              <option value="male">Male</option>
              <option value="female">Female</option>
            </select>
        </section>

        <section>
            <label>
                <input type="checkbox" id="banger" name="banger">
            </label>
        </section>

        <section>
            <label for="comments">comments:</label>
            <textarea id="comment" name="comments" rows="4"></textarea>
        </section>

        <button type="submit">submit</button>
     </form>

     </body>
     </html>
