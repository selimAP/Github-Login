<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login screen</title>
    <link rel="stylesheet" href="style.css">

    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Blinker:wght@100;200;300;400;600;700;800;900&display=swap" rel="stylesheet">
</head>
<body>
    <div class="login-form">
        <div class="logo">
            <a href="https://github.com/"><ion-icon name="logo-github" class="logo"></ion-icon></a>
            
        </div>
        <div class="title">
            <h1>Sign in to GitHub</h1>
            <form method="post" class="form">
                <div class="txt_field">
                    <label for="">Username</label>
                    <input type="text" required>
                </div>
                <div class="txt_field">
                    <label for="">Password</label>
                    <div class="pass"><a href="https://github.com/password_reset">Forgot Passwort?</a></div>
                    <input type="password" required>
                </div>
                <input type="submit" class="sign" value="Sign in">
            </form>
            <div class="new">
                <div class="border">
                <p>New to GitHub?&nbsp;<a href="https://github.com/signup?source=login"> Create an account</a>.</p>
            </div>
            </div>
        </div>
        <div class="footer">
            <ul>
                <li><a href="https://docs.github.com/en/site-policy/github-terms/github-terms-of-service">Terms</a></li>
                <li><a href="https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement">Privacy</a></li>
                <li><a href="https://github.com/security">Security</a></li>
                <li class="contact"><a href="https://support.github.com/?tags=dotcom-direct">Contact Github</a></li>

            </ul>
        </div>
    </div>

    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
</body>
</html>
