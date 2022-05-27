
<!DOCTYPE html>
<html lang = "en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="Bootstrap/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap-theme.min.css">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <style>

        .logo{
            width: 100px;
            height: 100px;
            z-index: 1;
            transform: translate(100%, 100%);
            box-shadow: 0 0 8px 0 #000000;
        }
        .cover{
            width: 900px;
            z-index: 1;
            position: absolute;
            transform: translate(70%, -150%);
        }
        img{
            vertical-align: middle;
        }
        ul{
            display: flex;
            overflow: auto;
            text-align: center;
            align-items: center;
        }


        ul .active button{
            background-color: rgb(196, 50, 61);
            color: white;
        }
        ul:hover .active:hover button:hover{
            background-color: rgb(196, 50, 61);
            opacity: 95%;
            color: #fff7f7;
        }

        ul .active button {
            -webkit-border-radius: 28;
            -moz-border-radius: 28;
            border-radius: 28px;
            font-family: Arial;
            color: #ffffff;
            font-size: 20px;
            background: #d14b4b;
            padding: 10px 5px;
            text-decoration: none;
        }
        ul :not(.active) button {
            -webkit-border-radius: 28;
            -moz-border-radius: 28;
            border-radius: 28px;
            font-family: Arial;
            color: #170000;
            font-size: 20px;
            background: #ffffff;
            padding: 10px 5px;
            border: solid #dbdbdb 2px;
            text-decoration: none;
        }

        .wrapper .item{
            min-width: 110px;
            height: 110px;
            line-height: 110px;
            text-align: center;
            background: white;
            margin-right: 2px;
        }


        div#nav
        {
            width: 900px;
            margin-left: auto;
            margin-right: auto;
        }

        div#nav ul li
        {
            margin-right: 15px;
            float: left;
            font-size: 12px;
            list-style-type: none;
        }
        ::-webkit-scrollbar {
            width: 10px;
        }

        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }

        ::-webkit-scrollbar-thumb {
            background: #888;
            -webkit-border-radius: 28;
            -moz-border-radius: 28;
            border-radius: 28px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }
        .cart{

        }
        #heart{
            transition: width 500ms linear, height 500ms linear;
            transition: all 300ms linear;
        }
        #heart:hover{
            color: #ff1616;
        }
        .img-card{
            transition: width 500ms linear, height 500ms linear;
            transition: all 100ms linear;
        }
        .img-card:hover{
            opacity: 80%;
        }

    </style>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" ></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
    <script src="js/jquery-1.11.2.js"></script>
    <script src="Bootstrap/js/bootstrap.js"></script>
    <script type="text/javascript" src="//code.jquery.com/jquery-1.9.1.js"></script>
    <script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>
    <script type="text/javascript">
    </script>
    <title>Speciaty Cake</title>
    <link rel="icon" href="logo.png" type="image/x-icon">
</head>
<body>

<!--Mid Card-->
<section class="wrapper-box" style="max-width: 900px; margin: 0px auto; background: #fff; box-shadow: 0px 0px 0px rgb(0 0 0 / 20%);">
    <div>
<!--        cover and logo-->
        <img src="background.jpeg" width="900" height="596" class="rounded-3" style="display: block">
        <div class="cover">
            <img src="logo.jpeg" class="rounded-circle border border-dark logo" id="logo" width="100" height="100">
        </div>
<!--        heart svg-->
        <div class="mt-3">
            <a id="btn-like">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="currentColor" id="heart" class="bi bi-heart-fill" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"/>
                </svg>
            </a>
        </div>
        <div class="text-center">
<!--            title-->
            <h5 class="text-danger">أوديلا</h5>
            <h5 class="text-danger mt-3">قهوة مختصة | Specialty Coffee</h5>
<!--            Opening time-->
            <div class="alert alert-success px-0 py-0 pt-1 mt-4 text-white fw-bolder" style="background: #28a745">
                <h6>Open from 6:30 am to 12:00 pm</h6>
            </div>
<!--            Contact US and some icons-->
            <div class="row mb-5">
                <div class="col-2 offset-5">
                    <div class="card shadow-sm">
                        <h5 class="text-center fw-bolder mt-1">Contact US</h5>
                    </div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-instagram mx-1 mt-2 text-danger" viewBox="0 0 16 16">
                        <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"/>
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-geo-alt-fill mx-1 mt-2 text-danger" viewBox="0 0 16 16">
                        <path d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"/>
                    </svg>
                </div>
            </div>
            <div id="nav">
                <div id="nav">
<!--                    tabs-->
                    <ul id="navbuttons">
                        <li class="active nav-item item">
                            <button href="#a" data-toggle="tab" class="btn fw-bolder border border-danger border-1" style="width: 160px">
                                الحلويات Dessert
                            </button>
                        </li>
                        <li class="mx-3 nav-item item">
                            <button onclick="functionToExecute()" href="#b" data-toggle="tab" class="btn fw-bolder border border-danger border-1" style="width: 200px">
                                الايس كريم / Ice cream
                            </button>
                        </li>
                        <li class="mx-3 nav-item item">
                            <button href="#c" data-toggle="tab" class="btn fw-bolder border border-danger border-1" style="width: 200px">
                                الفطور / breakfast
                            </button>
                        </li>
                        <li class="mx-3 nav-item item">
                            <button href="#d" data-toggle="tab" class="btn fw-bolder border border-danger border-1" id="first" style="width: 260px">
                                المشروبات الباردة Cold Drinks
                            </button>
                        </li>
                        <li class="mx-3 nav-item item">
                            <button href="#e" data-toggle="tab" class="btn fw-bolder border border-danger border-1" style="width: 260px">
                                المشروبات الساخنة Hot Drinks
                            </button>
                        </li>
                    </ul>
                </div>
<!--                content tabs-->
                <div class="tab-content">
                    <div id="a" class="tab-pane fade in active">
                        <div class="row">
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/1.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        قهوة اليوم
                                        <br>
                                        COFFEE OF THE DAY
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        10 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/2.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كيميكس
                                        <br>
                                        CHEMEX
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        15 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/3.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        في 60
                                        <br>
                                        V60
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        15 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/4.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        اسبريسو
                                        <br>
                                        ESPRESSO
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        10 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/5.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        فلات وايت
                                        <br>
                                        FLAT WHITE
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        16 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/6.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كورتادو
                                        <br>
                                        CORTADO
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        14 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/7.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كابتشينو
                                        <br>
                                        CUPPCCINO
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        16 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/8.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        لاتيه
                                        <br>
                                        LATTE
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        17 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/9.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        سبانيش
                                        <br>
                                        SPANISH
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        18 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="a/10.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        سولتد كراميل
                                        <br>
                                        Salted Caramel
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        18 ريال
                                    </h4>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div id="b" class="tab-pane fade">
                        <div class="row">
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/1.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        أوديلا سيجنتشر
                                        <br>
                                        Odila Signature
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        21 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/2.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كولد برو
                                        <br>
                                        Cold Pro
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        15 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/3.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        ايس سولتيد كراميل
                                        <br>
                                        ICED SALTED CARAMEL
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        20 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/4.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        موهيتو سيجنتشر
                                        <br>
                                        Mohito Signature
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        19 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/5.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        موهيتو بلاك
                                        <br>
                                        Mohito Black
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        19 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/6.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        ايس درب
                                        <br>
                                        Ice drip
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        16 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/7.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        موهيتو فيمتو
                                        <br>
                                        vimto mojito
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        18 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="b/8.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        سبانش بارد
                                        <br>
                                        Cold Spanish
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        19 ريال
                                    </h4>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div id="c" class="tab-pane fade">
                        <h5>ﻻ توجد منتجات حالياً</h5>
                    </div>
                    <div id="d" class="tab-pane fade">
                        <div class="row">
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="d/1.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        ايس كريم الفراولة
                                        <br>
                                        strawberry ice cream
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        10 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="d/2.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        ايس كريم الليمون
                                        <br>
                                        lemon ice cream
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        10 ريال
                                    </h4>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div id="e" class="tab-pane fade">
                        <div class="row">
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/1.png" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كوكيز الفول السوداني
                                        <br>
                                        Peanut cookies
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/2.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كوكيز الشوكولاته
                                        <br>
                                        Chocolate cookies
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/3.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        براوني
                                        <br>
                                        Brownie
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        12 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/4.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كيك حليب بالتوت
                                        <br>
                                        Raspberry milk cake
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/5.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كيك الزعفران
                                        <br>
                                        Zafran cake
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/6.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        أوديلا كيك
                                        <br>
                                        Odila cake
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/7.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        فرنش توست
                                        <br>
                                        French Toast
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        24 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/8.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كيكة التمر و التوفي
                                        <br>
                                        Date Toffee Pudding
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/9.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كيكة المولتن بالشوكلاته
                                        <br>
                                        Volcano Cake
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/10.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        تشيز كيك الزعفران
                                        <br>
                                        Saffron CheeseCake
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        26 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/11.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كوكيز سولتد كراميل
                                        <br>
                                        Salted Caramel Cookies
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        9 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 mx-4">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/12.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        وافل
                                        <br>
                                        Waffle
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        12 ريال
                                    </h4>
                                </div>
                            </div>
                            <div class="col-5 offset-1">
                                <div class="card cart mb-5 bg-white shadow-lg" style="border-radius: 30px;">
                                    <img src="e/13.jpeg" height="400" class="mx-5 my-5 mt-3 img-card" style="border-radius: 30px 30px 0px 0px;">
                                    <h4 class="fw-bolder">
                                        كرسبي تشوكلت
                                        <br>
                                        Crispy Chocolate
                                    </h4>
                                    <h4 class="text-end fw-bolder mx-3 mb-5">
                                        12 ريال
                                    </h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
<!--            Text-->
            <h6 class="text-dark opacity-75 ">
                صنع بال
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-heart-fill text-danger" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M8 1.314C12.438-3.248 23.534 4.735 8 15-7.534 4.736 3.562-3.248 8 1.314z"/>
                </svg>
                بواسطة
                <a href="#" class="text-primary">
                    قائمة الطلبات
                </a>
            </h6>
        </div>
    </div>
</section>
<script>
    document.getElementById("first").click()
</script>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
</body>
</html>
