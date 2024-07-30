<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionHome">

        <h1 class="sidehead">Podcast Home Page:</h1>
        <div class="bg">
            <h1 class="podu">Podcasts:</h1>
            <div class="d-flex flex-row">
                <div class="center" onclick="display('sectionPuri')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" class="simg" />
                    <p class="mainname">Puri Jagannadh</p>
                    <p class="simpleText">24 episodes</p>
                </div>
                <div class="center" onclick="display('sectionTedx')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" class="simg" />
                    <p class="mainname">Tedx talks</p>
                    <p class="simpleText">12 episodes</p>
                </div>
            </div>
            <div class="d-flex flex-row">
                <div class="center" onclick="display('sectionSadhguru')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" class="simg" />
                    <p class="mainname">Sadhguru</p>
                    <p class="simpleText">49 episodes</p>
                </div>
                <div class="center" onclick="display('sectionOnpurpose')">
                    <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" class="simg" />
                    <p class="mainname">On purpose</p>
                    <p class="simpleText">49 episodes</p>
                </div>
            </div>
        </div>
    </div>
    <div id="sectionPuri">
        <h1 class="sidehead">
            Podcast Puri Jagannadh Page:
        </h1>
        <div class="mainbox">
            <div class="d-flex flex-row">
                <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" />
                <div class="podtext">
                    <p>Podcast</p>
                    <h1>Puri Jagannadh Podcast</h1>
                    <p>The Puri Jagannadh Podcast</p>
                </div>
            </div>

        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" />
            <div class="al">
                <h1 class="mainnameag">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" />
            <div class="al">
                <h1 class="mainnameag">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" />
            <div class="al">
                <h1 class="mainnameag">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/puri-jagannadh-img.png" />
            <div class="al">
                <h1 class="mainnameag">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <button class="button d-flex flex-row justify-content-right" onclick="display('sectionHome')">back</button>
    </div>
    <div id="sectionTedx">
        <h1 class="sidehead">
            Podcast Tedx Page:
        </h1>
        <div class="mainbox">
            <div class="d-flex flex-row">
                <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" />
                <div class="podtext">
                    <p>Podcast</p>
                    <h1>The Tedx Podcast</h1>
                    <p>The Tedx Podcast</p>
                </div>
            </div>

        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" />
            <div class="al">
                <h1 class="mainnameag1">The Science of friction</h1>
                <p class="simpletextag">Tribology:It's a funny sounding word you might...</p>
                <p class="dur">12min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tedx-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <button class="button" onclick="display('sectionHome')">back</button>
    </div>
    <div id="sectionSadhguru">
        <h1 class="sidehead">
            Podcast Sadhguru Page:
        </h1>
        <div class="mainbox">
            <div class="d-flex flex-row">
                <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" />
                <div class="podtext">
                    <p>Podcast</p>
                    <h1>The Sadhguru Podcast</h1>
                    <p>The Sadhguru Podcast</p>
                </div>
            </div>

        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Head or Heart</h1>
                <p class="simpletextag">Sadhguru shares his wisdom on how to make...</p>
                <p class="dur">16min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/sadhguru-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <button class="button" onclick="display('sectionHome')">back</button>
    </div>
    <div id="sectionOnpurpose">
        <h1 class="sidehead">
            Podcast On Purpose Page:
        </h1>
        <div class="mainbox">
            <div class="d-flex flex-row">
                <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" />
                <div class="podtext">
                    <p>Podcast</p>
                    <h1>The On Purpose with jay Podcast</h1>
                    <p>The Jay Shetty Podcast</p>
                </div>
            </div>

        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Patrick Bet Dravid</h1>
                <p class="simpletextag">Are you an enterpreneur or have dreams of mental...</p>
                <p class="dur">10min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" />
            <div class="al">
                <h1 class="mainnameag1">Molecular Gastronomy</h1>
                <p class="simpletextag">Anything happens there it will not cook,...</p>
                <p class="dur">15min</p>
            </div>
        </div>
        <div class="d-flex flex-row">
            <img class="indiimg" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/on-purpose-img.png" />
            <h1 class="mainnameag1">Molecular Gastronomy</h1>
            <p class="simpletextag">Anything happens there it will not cook,...</p>
            <p class="dur">15min</p>
        </div>
    </div>
    </div>
    <script type="text/javascript" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"></script>
</body>

</html>
