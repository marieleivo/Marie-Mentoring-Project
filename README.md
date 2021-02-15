<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=>, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    h1 {
        text-align: center;
        font-style: normal;
        padding: 10px;
        font-family: 'Trebuchet MS';
    }

    h2 {
        text-align: center;
        font-style: italic;
    font-family:'Trebuchet MS';

    
    }
    p {text-align: center;
    padding: 15px 50px;
    width: 40pc;
    margin: auto;
    font-family:'Trebuchet MS';
    font-size: smaller;
    font-weight: bold;
    background-color: pink;
    box-shadow: 5px 5px 10px ;
}



    button {
        padding: 15px 20px;
        color:black;
        background-color: rgb(219, 215, 215);
        display: block;
        text-decoration: none;
        font-size: 10px;
        font-weight: bold;
        border-radius: 30px;
        margin: auto;
        border: 1px solid #7b7981;
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3);
        transition: all 200ms ease-in-out;
        font-family: 'Trebuchet MS';
    }

    button:hover {
        background-color: white;
        color: pink;
        
    }

    p2 {font-style: italic;
font-family: 'Trebuchet MS';
font-size: smaller;
margin: auto;
text-align: center;
display: block;
font-weight: bolder;}

    img {display: block;
margin: auto;
border-radius: 5px;}
hr {width: 160px;}

svg {display: block;
margin: auto;}
body {background-color: rgb(194, 191, 191);}


</style>

<body>
    <h1>Welcome to Mariellevie 🌸</h1>
    <h2>Social psychological mentoring</h2>
    <hr>
    <p>Hello! Few words about me, Marie the founder of Marielle.vie. I am a wellbeing enthusiast professional of social
    psychology having several years of experience serving in human resources in the private sector in Finland and abroad.
    Now I am willing to concentrate on helping individuals to get the best out of their personal potential by providing
    social psychological mentoring. Besides mentoring and interest in human behavior I am challenging myself in the Startup
    world more specifically - digital marketing.
</p>
<hr>

    <br>
    
    <img src=https://s3.amazonaws.com/shecodesio-production/uploads/files/000/005/023/original/Marie_CV.jpg?1613322215 width="200S"
    >
    <br>
    <br>

    <button>Participate</button>
    <br>
    <br>
    
    <a href= "https://www.linkedin.com/in/marie-leivo-9660b2131/">
    <svg xmlns="http://www.w3.org/2000/svg" width="34" height="34" viewBox="0 0 34 34" class="global-nav__logo">
        <title>LinkedIn</title>
    
        <g>
            <!---->
            <path
                d="M34,2.5v29A2.5,2.5,0,0,1,31.5,34H2.5A2.5,2.5,0,0,1,0,31.5V2.5A2.5,2.5,0,0,1,2.5,0h29A2.5,2.5,0,0,1,34,2.5ZM10,13H5V29h5Zm.45-5.5A2.88,2.88,0,0,0,7.59,4.6H7.5a2.9,2.9,0,0,0,0,5.8h0a2.88,2.88,0,0,0,2.95-2.81ZM29,19.28c0-4.81-3.06-6.68-6.1-6.68a5.7,5.7,0,0,0-5.06,2.58H17.7V13H13V29h5V20.49a3.32,3.32,0,0,1,3-3.58h.19c1.59,0,2.77,1,2.77,3.52V29h5Z"
                fill="currentColor"></path>
        </g>
        

    </svg>
    <br>

    <p2>Coded by Marie Leivo</p2>
    <script>

        function apply() {
            let firstName = prompt("What is your first name?");
            let age = prompt("How old are you?");
            let heading = document.querySelector("h1");
            if (age >= 18) {
                heading.innerHTML = "Hi " + firstName + "! Happy to have you here with us 🌸 ";
            } else {
                heading.innerHTML =
                    "Sorry " + firstName + "!" + " Unfortunately you can't participate to the mentoring yet 😔 ";
            }
        }

        let applyButton = document.querySelector("button");
        applyButton.addEventListener("click", apply);

    </script>
</body>

</html>
