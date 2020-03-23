# sparta<!DOCTYPE html>
<html lang="en">

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <link href="https://fonts.googleapis.com/css?family=Nanum+Pen+Script&display=swap" rel="stylesheet">

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <style>
        .wrap {
            width: 600px;
            margin: auto;
        }

        * {
            font-family: 'Nanum Pen Script', cursive;
        }

        body {
            background-color: peachpuff;
        }

        .small-font {
            font-size: 30px;
        }

        .large-font {
            font-size: 50px;
        }

        .card-title2 {
            color: red;
        }

        .wrap2 {
            margin: auto;
        }

        .input-group-text {
            color: blue;
        }
    </style>
    <script>

        function addon1() {
            let txt = $('#input-addon1').val()
            if (txt == '') {
                alert('입력하세요!');
            }
        }

    </script>


</head>

<body>



    <div class="card wrap">
        <img src="https://image.chosun.com/sitedata/image/201908/05/2019080502376_0.jpg" class="card-img-top" alt="...">
        <div class="card-body">
            <span class="card-title large-font">갤럭시S10</span>
            <span class="card-title small-font">가격: </span>
            <span class="card-title2 small-font">1,200,000</span>
            <span class="card-title small-font">원/개</span>

            <p class="card-text">2019년 메인삼성스마트폰 갤럭시S10!</p>

        </div>
        <div class="input-group mb-3">
            <div class="input-group-prepend">
                <span class="input-group-text">주문자 이름</span>
            </div>
            <input type="text" id="basic-addon1" class="form-control">
        </div>
        <div class="input-group mb-3">
            <div class="input-group-prepend">
                <label class="input-group-text" for="inputGroupSelect01">수량</label>
            </div>
            <select class="custom-select" id="inputGroupSelect01">
                <option selected>---수량을 선택하세요---</option>
                <option value="1">One</option>
                <option value="2">Two</option>
                <option value="3">Three</option>
                <option value="4">four</option>
            </select>
        </div>




        <div class="input-group mb-3">
            <div class="input-group-prepend">
                <span class="input-group-text">주소</span>
            </div>
            <input type="text" class="form-control" id="basic-addon2">
        </div>

        <div class="input-group mb-3">
            <div class="input-group-prepend">
                <span class="input-group-text">전화번호</span>
            </div>
            <input type="text" class="form-control" id='basic-addon3'>



        </div>
        <div class="wrap2">
            <button onclick="addon1()" class="btn btn-primary">주문하기</button>

        </div>
    </div>


</body>

</html>
