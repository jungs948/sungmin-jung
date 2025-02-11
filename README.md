<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 151px; height: 56px; left: 1095px; top: 44px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 1135px; top: 50px; position: absolute; color: black; font-size: 36px; font-family: Inter; font-weight: 400; word-wrap: break-word">login</div>
    <img style="width: 1504px; height: 268px; left: 0px; top: 756px; position: absolute" src="https://via.placeholder.com/1504x268" />
    <img style="width: 1440px; height: 900px; left: 0px; top: -144px; position: absolute" src="https://via.placeholder.com/1440x900" />
    <div style="width: 121px; height: 64px; left: 660px; top: 548px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 683px; top: 561px; position: absolute; color: black; font-size: 32px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">RSVP</div>
    <div style="width: 233px; height: 26px; left: 608px; top: 280px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 637px; top: 268px; position: absolute"><span style="color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">10003 newyork</span><span style="color: black; font-size: 32px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word"> </span></div>
    <div style="width: 398px; height: 425px; left: 997px; top: 187px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
    <div style="width: 398px; height: 425px; left: 505px; top: 187px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
    <div style="width: 398px; height: 425px; left: 55px; top: 187px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
</div>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fine Drinks</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Inter', sans-serif;
            background-color: #6A1212;
            color: white;
            text-align: center;
        }
        .section {
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
        }
        .background-img {
            position: absolute;
            width: 100%;
            height: 100vh;
            top: 0;
            left: 0;
            object-fit: cover;
            z-index: -1;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            position: absolute;
            top: 30px;
            padding: 0 50px;
            font-size: 24px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
        }
        .home-button {
            background: #D9D9D9;
            padding: 10px 20px;
            color: black;
            font-size: 24px;
            font-weight: 400;
        }
        .content-container {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 80%;
            gap: 50px;
        }
        .image-container {
            width: 40%;
        }
        .image-container img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .text-container {
            width: 50%;
            text-align: left;
        }
        .text-container h1 {
            font-size: 96px;
            margin-bottom: 20px;
            font-family: 'Inria Serif', serif;
        }
        .text-container p {
            font-size: 24px;
            line-height: 1.6;
        }
    </style>
</head>
<body>
    <div class="section">
        <img class="background-img" src="your-updated-background-image.jpg" alt="Background">
        <div class="navbar">
            <a href="#">BACK PAGE</a>
            <a href="#" class="home-button">HOME</a>
            <a href="#">LOCATION</a>
            <a href="#">MY PAGE</a>
        </div>
        <div class="content-container">
            <div class="image-container">
                <img src="your-updated-image.jpg" alt="Fine Drinks Image">
            </div>
            <div class="text-container">
                <h1>Fine Drinks</h1>
                <p>We’ll be mixing tiki classics and some new creations using top-shelf spirits and organic mixers. Not a tippler? Not to worry—we’ll have a full menu of delicious mocktails on offer, too.</p>
            </div>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Good Vibes</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Inria Serif', serif;
            background-color: #6A1212;
            color: white;
            text-align: center;
        }
        .section {
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            position: relative;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            position: absolute;
            top: 30px;
            padding: 0 50px;
            font-size: 24px;
            background: #0F0000;
            height: 100px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
        }
        .home-button {
            background: #D9D9D9;
            padding: 10px 20px;
            color: black;
            font-size: 24px;
            font-weight: 400;
        }
        .content-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 80%;
            height: 80vh;
        }
        .text-box {
            width: 50%;
            text-align: left;
            background: rgba(255, 255, 255, 0.1);
            padding: 40px;
        }
        .text-box h1 {
            font-size: 96px;
            margin-bottom: 20px;
        }
        .text-box p {
            font-size: 32px;
            line-height: 1.6;
        }
        .image-box {
            width: 40%;
            height: 60%;
            background: rgba(255, 255, 255, 0.2);
        }
    </style>
</head>
<body>
    <div class="section">
        <div class="navbar">
            <a href="#">BACK PAGE</a>
            <a href="#" class="home-button">HOME</a>
            <a href="#">LOCATION</a>
            <a href="#">MY PAGE</a>
        </div>
        <div class="content-container">
            <div class="text-box">
                <h1>Good Vibes</h1>
                <p>Look out for guest DJs spinning vintage bossa nova and deep house, party games, a tiki photo booth and a top secret live performance right as the clock strikes midnight. Don’t miss the fun!</p>
            </div>
            <div class="image-box"></div>
        </div>
    </div>
</body>
</html>
<div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 1440px; height: 325px; left: 0px; top: 810px; position: absolute" src="https://via.placeholder.com/1440x325" />
    <img style="width: 1440px; height: 487px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/1440x487" />
    <div style="width: 280px; height: 72px; left: 572px; top: 302px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 596px; top: 316px; position: absolute; color: black; font-size: 36px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Take a Action!</div>
    <img style="width: 1440px; height: 558px; left: 0px; top: 471px; position: absolute" src="https://via.placeholder.com/1440x558" />
    <div style="width: 223px; height: 392px; left: 122px; top: 551px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
    <div style="width: 223px; height: 392px; left: 430px; top: 551px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
    <div style="width: 223px; height: 392px; left: 738px; top: 551px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
    <div style="width: 223px; height: 392px; left: 1057px; top: 551px; position: absolute; opacity: 0.40; background: #D9D9D9"></div>
    <div style="left: 158px; top: 668px; position: absolute; color: #0F0101; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">ABOUT</div>
    <div style="left: 448px; top: 668px; position: absolute; color: #0F0101; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">HISTORY</div>
    <div style="left: 782px; top: 668px; position: absolute; color: #0F0101; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">TASTE</div>
    <div style="left: 1075px; top: 668px; position: absolute; color: #0F0101; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">PEOPLE</div>
    <div style="width: 101px; height: 86px; left: 1217px; top: 44px; position: absolute; background: #0D0000"></div>
    <div style="width: 101px; height: 86px; left: 1217px; top: 173px; position: absolute; background: #0D0000"></div>
    <div style="width: 101px; height: 86px; left: 1217px; top: 173px; position: absolute; background: #0D0000"></div>
    <div style="left: 1251px; top: 187px; position: absolute; color: white; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">V</div>
    <div style="width: 101px; height: 86px; left: 1217px; top: 302px; position: absolute; background: #0D0000"></div>
    <div style="left: 1251px; top: 316px; position: absolute; color: white; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">N</div>
    <div style="left: 1249px; top: 58px; position: absolute; color: white; font-size: 48px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">G</div>
    <div style="width: 102px; height: 57px; left: 183px; top: 795px; position: absolute; background: #FEA706"></div>
    <div style="left: 205px; top: 809px; position: absolute; color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Book</div>
    <div style="width: 102px; height: 57px; left: 494px; top: 795px; position: absolute; background: #FEA706"></div>
    <div style="width: 102px; height: 57px; left: 798px; top: 795px; position: absolute; background: #FEA706"></div>
    <div style="width: 102px; height: 57px; left: 1115px; top: 795px; position: absolute; background: #FEA706"></div>
    <div style="left: 517px; top: 809px; position: absolute; color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Book</div>
    <div style="left: 821px; top: 809px; position: absolute; color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Book</div>
    <div style="left: 1138px; top: 809px; position: absolute; color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Book</div>
</div>
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hailey’s House</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Inria Serif', serif;
            background-color: #A1241E;
            color: white;
            text-align: center;
        }
        .section {
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding: 50px;
            position: relative;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background: black;
            padding: 20px 40px;
            font-size: 1.5rem;
            width: 100%;
            position: absolute;
            top: 0;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
        }
        .top-section {
            width: 100%;
            height: 30vh;
            background: url('your-image-url.jpg') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }
        .top-section p {
            font-size: 1.5rem;
            color: white;
            position: absolute;
            top: 10%;
        }
        .top-section button {
            font-size: 1.5rem;
            padding: 10px 20px;
            background-color: white;
            border: none;
            cursor: pointer;
        }
        .content {
            text-align: left;
            max-width: 80%;
            margin-top: 20px;
        }
        .content h1 {
            font-size: 5rem;
            margin-bottom: 20px;
        }
        .grid-layout {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            width: 100%;
            max-width: 80%;
            margin-top: 40px;
        }
        .grid-box {
            background: rgba(255, 255, 255, 0.2);
            padding: 40px;
            text-align: center;
            font-size: 2rem;
        }
    </style>
</head>
<body>
    <div class="section">
        <div class="navbar">
            <a href="#">Your order</a>
            <a href="#">My page</a>
            <a href="#">Rumb’s kind</a>
        </div>
        <div class="top-section">
            <p>Your 1s and 2s are always welcome, but please do let us know in advance so we bring enough drinks for everyone.</p>
            <button>Check out</button>
        </div>
        <div class="content">
            <h1>Hailey’s House</h1>
            <div class="grid-layout">
                <div class="grid-box">CH2. RUMB</div>
                <div class="grid-box">CH3. RUMB</div>
            </div>
            <p>Location</p>
            <p>Phone number - 646 407 7893</p>
        </div>
    </div>
</body>
</html>
<div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 1501px; height: 1024px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/1501x1024" />
    <div style="left: 978px; top: 569px; position: absolute"><span style="color: white; font-size: 36px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Red maple sunset<br/><br/></span><span style="color: white; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</span></div>
    <div style="width: 339px; height: 521px; left: 73px; top: 124px; position: absolute"><span style="color: white; font-size: 36px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">ABOUT <br/><br/></span><span style="color: white; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.Combine all  <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</span></div>
    <div style="left: 978px; top: 569px; position: absolute"><span style="color: white; font-size: 36px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Red maple sunset<br/><br/></span><span style="color: white; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</span></div>
    <div style="width: 76px; height: 53px; left: 1301px; top: 569px; position: absolute; background: #D9D9D9"></div>
    <div style="left: 1313px; top: 580px; position: absolute; color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">click</div>
</div>
<div style="width: 100%; height: 100%; position: relative; background: white">
    <img style="width: 654px; height: 859px; left: 793px; top: 0px; position: absolute" src="https://via.placeholder.com/654x859" />
    <img style="width: 793px; height: 1366px; left: 0px; top: -33px; position: absolute" src="https://via.placeholder.com/793x1366" />
    <div style="width: 234px; height: 94px; left: 1005px; top: 623px; position: absolute; opacity: 0.80; background: #D9D9D9; border: 1px black solid"></div>
    <div style="width: 251px; height: 81px; left: 1041px; top: 636px; position: absolute; color: black; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Make your own <br/>       Cocktail! </div>
    <div style="width: 348px; height: 255px; left: 944px; top: 246px; position: absolute; color: white; font-size: 40px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">choose a flavor<br/>make an order<br/>watch the show<br/>smell it<br/>taste it</div>
</div>
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 1423px; height: 1065.35px; left: 0.43px; top: -30px; position: absolute; opacity: 0.40">
        <img style="width: 1423px; height: 949.62px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/1423x950" />
        <div style="width: 277.96px; height: 272.27px; left: 944.47px; top: 793.09px; position: absolute"><span style="color: white; font-size: 36px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Red maple sunset<br/><br/></span><span style="color: white; font-size: 24px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</span></div>
        <div style="width: 207.76px; height: 161.27px; left: 1171.60px; top: 423.11px; position: absolute; color: white; font-size: 20px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</div>
        <div style="width: 1367.03px; height: 38.90px; left: 12.33px; top: 802.57px; position: absolute">
            <div style="width: 1441px; height: 30px; left: 0px; top: 11px; position: absolute; background: #5C0202"></div>
            <div style="width: 20px; height: 240px; left: 358px; top: 41px; position: absolute; background: #8F0B0B"></div>
        </div>
        <div style="width: 590px; height: 579px; left: 246px; top: 134px; position: absolute; background: #D9D9D9"></div>
    </div>
    <div style="width: 228px; height: 169px; left: 861.43px; top: 325px; position: absolute; color: white; font-size: 20px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</div>
</div>
<div style="width: 100%; height: 100%; position: relative; background: white">
    <div style="width: 1440px; height: 1024px; left: 0px; top: 0px; position: absolute; background: linear-gradient(0deg, rgba(0, 0, 0, 0.20) 0%, rgba(0, 0, 0, 0.20) 100%); box-shadow: 4px 4px 4px; filter: blur(4px); backdrop-filter: blur(4px)"></div>
    <div style="width: 1440px; height: 1024px; left: 0px; top: 203px; position: absolute"></div>
    <div style="left: 653px; top: 56px; position: absolute; color: white; font-size: 36px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Options </div>
    <div style="width: 402px; height: 388px; left: -19px; top: 78px; position: absolute; background: #865F5F; border-radius: 9999px"></div>
    <div style="left: 88px; top: 228px; position: absolute; color: black; font-size: 40px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">classic old <br/>fashioned</div>
    <div style="width: 402px; height: 388px; left: 122px; top: 597px; position: absolute; background: #F36666; border-radius: 9999px"></div>
    <div style="width: 402px; height: 388px; left: 888px; top: -231px; position: absolute; background: #0B0000; border-radius: 9999px"></div>
    <div style="width: 402px; height: 388px; left: 687px; top: 272px; position: absolute; background: #901B1B; border-radius: 9999px"></div>
    <div style="left: 767px; top: 442px; position: absolute; color: black; font-size: 40px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">gin and tonic</div>
    <div style="left: 196px; top: 767px; position: absolute; color: black; font-size: 40px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">moscow muel</div>
    <div style="width: 402px; height: 388px; left: 1089px; top: 715px; position: absolute; background: #FF0808; border-radius: 9999px"></div>
    <div style="width: 188px; height: 141px; left: 1230px; top: 874px; position: absolute; color: black; font-size: 40px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">mojito</div>
    <div style="left: 412px; top: 175px; position: absolute; color: white; font-size: 20px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</div>
    <div style="left: 566px; top: 722px; position: absolute; color: #FFFEFE; font-size: 20px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</div>
    <div style="width: 204px; height: 233px; left: 1072px; top: 91px; position: absolute; color: #FFFEFE; font-size: 20px; font-family: Inria Serif; font-weight: 400; word-wrap: break-word">Combine all ingredients <br/>in a cocktail shaker and <br/>dry shake. Add ice and <br/>shake again. Double <br/>strain into a martini<br/> glass and garnish with <br/>a twist of orange.</div>
</div>
