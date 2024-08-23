# forms

# PROGRAMS:

## INDEX.HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FORMS</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            color: black;
            margin: 0;
            padding: 0;
        }

        h1 {
            background-color: skyblue;
            color: #fff;
            padding: 20px;
            text-align: center;
            margin: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .container {
            max-width: 600px;
            margin: 50px auto;
            text-align: center;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin: 20px 0;
        }

        a {
            display: inline-block;
            text-decoration: none;
            color: #fff;
            background-color: skyblue;
            font-size: 18px;
            padding: 10px 30px;
            border-radius: 25px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        a:hover {
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <h1>Welcome to the Forms Website</h1>
    <div class="container">
        <ul>
            <li><a href="login.html">Login Form</a></li>
            <li><a href="contact.html">Contact Form</a></li>
            <li><a href="registration.html">Registration Form</a></li>
            <li><a href="application.html">Application Form</a></li>
            <li><a href="feedback.html">Feedback Form</a></li>
        </ul>
    </div>
</body>
</html>
```
## LOGIN.HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            background-color: skyblue;
            color: #fff;
            padding: 20px;
            text-align: center;
            margin: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container {
            max-width: 400px;
            margin: 50px auto;
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: skyblue;
            color: white;
            padding: 10px 0;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        input[type="submit"]:hover {
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <h1>Login Form</h1>
    <div class="form-container">
        <form action="https://example.com/login" method="post">
            <label for="login-username">Username:</label>
            <input type="text" id="login-username" name="username" required>
            
            <label for="login-password">Password:</label>
            <input type="password" id="login-password" name="password" required>
            
            <input type="submit" value="Login">
        </form>
    </div>
</body>
</html>
```

## CONTACT.HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Form</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            background-color: skyblue;
            color: #fff;
            padding: 20px;
            text-align: center;
            margin: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container {
            max-width: 400px;
            margin: 50px auto;
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: skyblue;
            color: white;
            padding: 10px 0;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        input[type="submit"]:hover {
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <h1>Contact Form</h1>
    <div class="form-container">
        <form action="https://example.com/contact" method="post">
            <label for="contact-name">Name:</label>
            <input type="text" id="contact-name" name="name" required>
            
            <label for="contact-email">Email:</label>
            <input type="email" id="contact-email" name="email" required>
            
            <label for="contact-message">Message:</label>
            <textarea id="contact-message" name="message" rows="4" required></textarea>
            
            <input type="submit" value="Send Message">
        </form>
    </div>
</body>
</html>
```

## REGISTRATION.HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            background-color: skyblue;
            color: #fff;
            padding: 20px;
            text-align: center;
            margin: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container {
            max-width: 400px;
            margin: 50px auto;
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: skyblue;
            color: white;
            padding: 10px 0;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        input[type="submit"]:hover {
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <h1>Registration Form</h1>
    <div class="form-container">
        <form action="https://example.com/register" method="post">
            <label for="register-username">Username:</label>
            <input type="text" id="register-username" name="username" required>
            
            <label for="register-email">Email:</label>
            <input type="email" id="register-email" name="email" required>
            
            <label for="register-password">Password:</label>
            <input type="password" id="register-password" name="password" required>
            
            <input type="submit" value="Register">
        </form>
    </div>
</body>
</html>
```

## APPLICATION.HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Application Form</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            background-color: skyblue;
            color: #fff;
            padding: 20px;
            text-align: center;
            margin: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container {
            max-width: 400px;
            margin: 50px auto;
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }

        input[type="text"],
        input[type="email"],
        input[type="tel"],
        input[type="file"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: skyblue;
            color: white;
            padding: 10px 0;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        input[type="submit"]:hover {
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <h1>Application Form</h1>
    <div class="form-container">
        <form action="https://example.com/apply" method="post">
            <label for="applicant-name">Full Name:</label>
            <input type="text" id="applicant-name" name="name" required>
            
            <label for="applicant-email">Email:</label>
            <input type="email" id="applicant-email" name="email" required>
            
            <label for="applicant-phone">Phone Number:</label>
            <input type="tel" id="applicant-phone" name="phone" required>
            
            <label for="applicant-resume">Resume:</label>
            <input type="file" id="applicant-resume" name="resume" required>
            
            <input type="submit" value="Apply">
        </form>
    </div>
</body>
</html>
```

## FEEDBACK.HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback Form</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #e0f7fa;
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1 {
            background-color: skyblue;
            color: #fff;
            padding: 20px;
            text-align: center;
            margin: 0;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .form-container {
            max-width: 400px;
            margin: 50px auto;
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }

        input[type="text"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: skyblue;
            color: white;
            padding: 10px 0;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
            transition: background-color 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        input[type="submit"]:hover {
            background-color: skyblue;
        }
    </style>
</head>
<body>
    <h1>Feedback Form</h1>
    <div class="form-container">
        <form action="https://example.com/feedback" method="post">
            <label for="feedback-name">Name:</label>
            <input type="text" id="feedback-name" name="name" required>
            
            <label for="feedback-comments">Comments:</label>
            <textarea id="feedback-comments" name="comments" rows="4" required></textarea>
            
            <input type="submit" value="Submit Feedback">
        </form>
    </div>
</body>
</html>
