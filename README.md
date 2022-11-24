# Swethanag.github.co
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div>
        <div>

            <div class="d-flex flex-row">
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/seasons-switcher-spring-md-img.png" class="sizing" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/seasons-switcher-summer-md-img.png" class="sizing" />
            </div>
            <div class="d-flex flex-row">
                <img src=" https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/seasons-switcher-autumn-md-img.png" class="sizing" />
                <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/seasons-switcher-winter-md-img.png " class="sizing" />

            </div>
        </div>
        <div>

            <img id="bigimage" src="" />
        </div>
        <div class="m-2">
            <button class="button spring-button" id="springBtn" onclick="changeSeasonToSpring()">Spring</button>
            <button class="button summer-button" id="summerBtn" onclick="changeSeasonToSummer()">Summer</button>
            <button class="button autumn-button" id="autumnBtn" onclick="changeSeasonToAutumn()">Autumn</button>
            <button class="button winter-button" id="winterBtn" onclick="changeSeasonToWinter()">Winter</button>
        </div>
    </div>
</body>

</html>
