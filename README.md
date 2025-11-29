<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Legacy Made Ventures</title>

<style>
    body {
        margin: 0;
        padding: 0;
        background: #0c0c0c;
        color: #f5f5f5;
        font-family: "Helvetica Neue", Arial, sans-serif;
        letter-spacing: 0.4px;
    }

    .container {
        max-width: 900px;
        margin: 0 auto;
        padding: 60px 20px;
        text-align: center;
    }

    h1 {
        font-size: 48px;
        font-weight: 300;
        text-transform: uppercase;
        letter-spacing: 8px;
        margin-bottom: 10px;
        color: #f1f1f1;
    }

    h2 {
        font-size: 18px;
        font-weight: 300;
        letter-spacing: 6px;
        text-transform: uppercase;
        color: #c5a46d; /* luxury gold tone */
        margin-top: 0;
        margin-bottom: 50px;
    }

    p {
        font-size: 17px;
        line-height: 1.7;
        max-width: 700px;
        margin: 20px auto;
        color: #dcdcdc;
    }

    .divider {
        width: 60px;
        height: 1px;
        background: #c5a46d;
        margin: 40px auto;
        opacity: 0.7;
    }

    footer {
        margin-top: 60px;
        font-size: 13px;
        color: #777;
    }
</style>
</head>

<body>

<div class="container">
    <h1>Legacy Made Ventures</h1>
    <h2>Private Holding Company</h2>

    <div class="divider"></div>

    <p>
        A privately held entity focused on long-term value creation through real estate ownership, 
        strategic investments, and disciplined asset protection.  
    </p>

    <p>
        Our approach is simple: acquire intelligently, operate efficiently, and build with intention.
        Every decision, structure, and investment is designed with generational strength in mind.
    </p>

    <div class="divider"></div>

    <p>
        For inquiries or formal correspondence:<br>
        <strong>info@legacymadeventures.com</strong>
    </p>

    <footer>
        © <span id="year"></span> Legacy Made Ventures. All Rights Reserved.
    </footer>
</div>

<script>
    document.getElementById("year").textContent = new Date().getFullYear();
</script>

</body>
</html>
