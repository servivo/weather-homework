# weather-homework
Just a task I have done on how to replicate a page about weather forecast.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Weather</title>
  </head>
<body>
    <style>


button
{display: block;
margin: 0 auto;
border: 1px solid #1a64d6;
background: #1a64d6;
color: white;
font-size: 16px;
padding: 16px 24px;
border-radius: 30px;
transition: all 200ms ease;
cursor: pointer;
box-shadow: rgb(37 39 89 / 8%) 0px 8px 8px 0;
line-height: 22px;
margin-block-start: 1em;
    margin-block-end: 1em;
    }

.emoji
{color:blue;
font-size: 34px;
text-align: center;
line-height: 48px;}

.currently
{color: blue;
font-size: 34px;
text-align: center;
font-family: Arial, Helvetica, sans-serif;
margin: 0;
font-weight: bold;
line-height: 48px;}

.temp-now
{font-size: 34px;
text-align: center;
display: block;
line-height: 48px;
font-family: Arial, Helvetica, sans-serif;
font-weight: 400;
line-height: 48px;}

.max-now
{font-size: 34px;
font-family: Arial, Helvetica, sans-serif;
font-weight: bold;
}

.days

{text-align: center;
font-family: Arial, Helvetica, sans-serif;
padding: 10px 0;
    border-radius: 10px;
    transition: all 200ms ease-in-out;
    max-width: 400px;
    margin: 0 auto;
font-size: 1.17em;
font-weight: bold;}

.temp-min

{display: block;
margin: 0 auto;
text-align: center;
font-family: monospace;
font-size: 18px;
opacity: 0.7;}

.tomorrow {padding: 10px 0;
    border-radius: 10px;
    transition: all 200ms ease-in-out;
    max-width: 400px;
    margin: 0 auto;
}

    .tomorrow:hover {background: #fffbef;
    border-radius: 10px;}
    .saturday:hover {background: #fffbef;
    border-radius: 10px;}
    .sunday:hover {background: #fffbef;
    border-radius: 10px;}
    button:hover {
    background:white;
    color: blue;
    cursor: pointer;}

    .saturday {padding: 10px 0;
    border-radius: 10px;
    transition: all 200ms ease-in-out;
    max-width: 400px;
    margin: 0 auto;}

    .sunday {padding: 10px 0;
    border-radius: 10px;
    transition: all 200ms ease-in-out;
    max-width: 400px;
    margin: 0 auto;}
.author

{text-align: center;
font-size: 18px;
font-family: monospace;
display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;}


    </style>

  <div class="emoji">🌤</div>
<div class="currently">Currently 21° in Tokyo</div>
<span class="temp-now">13° / <strong> 23° </strong></span>

<div class="tomorrow">
<div class="days">🌧Tomorrow</div>
<span class="temp-min">10° /  <strong>22°</strong></span> </div>

<div class="saturday">
<div class="days">🌥 Saturday</div>
<span class="temp-min">5° /  <strong>17°</strong></span> </div>

<div class="sunday">
<div class="days">☀️ Sunday</div>
<span class ="temp-min">25° /<strong> 28° </strong></span> </div>

<button>Change city</button>

<div class="author">Coded by B. M.</div>

</body>
</html>
