# AKASH-SUNGSAM
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div id="sectionHome" class="align">
        <img class="home-img1" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/software-developer-img.png">
        <h1 class="home-heading">My Projects</h1>
        <p class="home-paragraph">These are a few of my Static Website Projects that i have developed using HTML, CSS and Bootstrap</p>
        <div class="align">
            <div class="d-flex flex-row justify-content-center">
                <img onclick="display('sectionAdvance')" class="home-img2" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advanced-technologies-img.png">
                <img class="home-img3" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/diwali-img.png">
            </div>
            <div class="d-flex flex-row justify-content-center ">
                <img class="home-img2" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/food-img.png">
                <img class="home-img3" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/news-paper-img.png">
            </div>
        </div>
    </div>
    <div id="sectionAdvance">
        <img class="advance-bg-img1" src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/advanced-technologies-img.png">
        <div class="advance-card d-flex flex-column justify-content-end">
            <h1 class="advance-heading">Advanced Technologies</h1>
            <p>Machinery and equipment from the application of scientific knowledge.</p>
            <div class="advance-button">
                <button class="button">Learn more</button>
                <button onclick="display('sectionHome')" class="btn btn-primary">Back</button>
            </div>
        </div>
    </div>
    <script type="text/javascript" src="https://new-assets.ccbp.in/frontend/content/static-ccbp-ui-kit/static-ccbp-ui-kit.js"></script>
</body>

</html>
