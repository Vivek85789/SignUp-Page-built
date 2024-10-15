# SignUp-Page-built
This is my first Project that I implemented using HTML and CSS.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SignUp</title>
    <link rel="stylesheet" href="project2.css">
</head>
<body>

    <div class="outer-box">
        <div class="inner-box">
            <header class="signUp-header">
                <h1>SignUp</h1>
                <p>It just takes 30 seconds</p>
            </header>
            <main class="signUp-body">
                <form action="#">
                    <p>
                        <label for="fullname">Full Name</label>
                        <input type="text" id="fullname" placeholder="Vivek Kumar" required>
                    </p>
                    <p>
                        <label for="email">Your Email</label>
                        <input type="email" id="email" placeholder="kumarvivek8034@gmail.com" required>
                    </p>
                    <p>
                        <label for="password">Your New Password</label>
                        <input type="password" id="password" placeholder="at least 8 characters" required>
                    </p>
                    <p>
                        <input type="submit" id="submit" value="Create Account">
                    </p>
                </form>
            </main>

            <footer class="signUp-footer">
                <p>Already have an Account? <a href="#">Login</a> </p>
            </footer>

        </div>
        <div class="circle c1"></div>
        <div class="circle c2"></div>
    </div>
    
</body>
</html>
