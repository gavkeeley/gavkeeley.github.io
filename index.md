<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="icon" href="/static/map_icon.svg">

        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A==" crossorigin=""/>
        <link href="/static/style.css" rel="stylesheet">
        
    </head>
    <body>
        <header>
            <!--HEADER - STAYS AT THE TOP-->
            <div class="px-3 py-2 headerBar text-white" style="background-color: #0062b3;">
                <div class="container">
                    <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
                        <a href="/" class="d-flex align-items-center my-2 my-lg-0 me-lg-auto text-white text-decoration-none" style="font-size: 30px;">
                            <i class="fas fa-map-marked-alt fa-lg" style="margin-left: 20px; margin-right: 20px;"></i>
                            Kutana
                        </a>
                        <ul class="nav col-12 col-lg-auto my-2 justify-content-center my-md-0 text-small">
                            <li>
                                <a href="/" class="nav-link text-white hover-white">
                                    <i class="fas fa-list-ol fa-fw fa-lg bi d-block mx-auto" style="margin-top:10px; margin-bottom: 10px;"></i>
                                    Post List
                                </a>
                            </li>
                            <li>
                                <a href="/map" class="nav-link text-white hover-white">
                                    <i class="fas fa-map-marked-alt fa-fw fa-lg bi d-block mx-auto" style="margin-top:10px; margin-bottom: 10px;"></i>
                                    Post Map
                                </a>
                            </li>
                            <li>
                                <a href="/users" class="nav-link text-white hover-white">
                                    <i class="fas fa-user fa-fw fa-lg bi d-block mx-auto" style="margin-top:10px; margin-bottom: 10px;"></i>
                                    Users
                                </a>
                            </li>
                            <li>
                                <a href="/groups" class="nav-link text-white hover-white">
                                    <i class="fas fa-users fa-fw fa-lg bi d-block mx-auto" style="margin-top:10px; margin-bottom: 10px;"></i>
                                    Groups
                                </a>
                            </li>
                            <li>
                                <a href="/post" class="nav-link text-white hover-white">
                                    <i class="fas fa-edit fa-fw fa-lg bi d-block mx-auto" style="margin-top:10px; margin-bottom: 10px;"></i>
                                    Post
                                </a>
                            </li>
                            <li>
                                <a href="/signout" class="nav-link text-white hover-white">
                                    <i class="fas fa-sign-out-alt fa-fw fa-lg bi d-block mx-auto" style="margin-top:10px; margin-bottom: 10px;"></i>
                                    Log Out
                                </a>
                            </li>
                            <li>
                                <a href="/profile" class="nav-link text-white hover-white">
                                    <!--USERS PERSONAL AVATAR SHOULD BE DYNAMICALLY INSERTED BELOW-->
                                    <img src="/static/avatars/0{{avatar_id}}.svg" alt="" height="29" class="bi d-block mx-auto" style="margin-top: 3px; margin-bottom: 3px;">
                                    My Profile
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <!--END OF HEADER - STAYS AT THE TOP-->
        </header>

        <!--MAIN BODY CONTENT (FROM HERE CONTENT DIFFERS FROM BASE.HTML)-->
        Content

        <!-- SCRIPTS -->
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js"></script>
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
        <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>
        <script src="/static/index.js"></script>
        <!--END OF SCRIPTS -->
        
        <!--END OF MAIN BODY CONTENT (FROM HERE CONTENT DIFFERS FROM BASE.HTML)-->
    </body>
</html>

