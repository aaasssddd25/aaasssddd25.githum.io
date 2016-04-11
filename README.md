<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8" />
    <title>&lt;한성대학교&gt; 주대원</title>
    <style>
        body {background-color:gainsboro; }
        .background {
            width:800px;
            background-color:lightgrey;
            border: 1px solid floralwhite;
            margin: 0 auto;
        }
        .header {
            background: rgb(180,227,145);
            background: -moz-radial-gradient(center, ellipse cover,  rgba(180,227,145,1) 0%, rgba(97,196,25,1) 50%, rgba(180,227,145,1) 100%);
            background: -webkit-radial-gradient(center, ellipse cover,  rgba(180,227,145,1) 0%,rgba(97,196,25,1) 50%,rgba(180,227,145,1) 100%);
            background: radial-gradient(ellipse at center,  rgba(180,227,145,1) 0%,rgba(97,196,25,1) 50%,rgba(180,227,145,1) 100%);
            filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#b4e391', endColorstr='#b4e391',GradientType=1 );
            width:800px; text-align:center; margin : 0 auto;
        }
        .menu {
            background-color:lightslategrey;
            position:fixed;
            left:50; width:100px; margin: 0 20px;
            border-radius: 30px; padding:10px;
            text-align: center;
        }
        .menu-header{
            font-size:24px;
        }
        .img  {
            float: right;
            padding: 20px;
        }
        .image-ridding {
            float: left;
            padding: 20px; width:300px;
        }
        .font-padding{
            padding-left:10px;
        }
    </style>
</head>
<body>
    <div>
        <h1 class="header">자기소개</h1>
        <hr />
        <div class="menu">
            <b class="menu-header">메뉴</b>
            <br />
            <br />
            <a href="#프로필">프로필</a>
            <br />
            <br />
            <a href=#취미>취미</a>
            <br />
            <br />
            <a href=#장래희망>장래희망</a>
            <br />
            <br />
        </div>
        <div class="background" id="font-padding">
            <br />
            <br />
            <h1 class="header" id="프로필">프로필</h1>
            <br />
            <img class="img" src="http://placehold.it/150x150" />
            <div class="font-padding">
                <p>이름 : 주대원</p>
                <p>나이 : 20살</p>
                <p>사는곳 : 경기도 부천시 오정구 오정동</p>
                <p>학력 : 한성대학교 재학 덕산고등학교졸업</p>
                <p>학번 : 1694043</p>
                <br />
                <hr />
                <br />
            </div>
            <h1 class="header" id="취미">취미</h1>
            <div class="font-padding">
                <img class="image-ridding" src="자전거타기.png" />
                <br />
                <p>저의 취미는 자전거타기입니다.</p>
                <p>주기적으로 주말마다 친구들과 자전거를 타고 공원산책을<br />합니다.</p>
                <p>방학때는 자전거를 타고 마포도 다녀왔습니다. </p>
                <br />
                <br />
                <br />
            </div>
            <br />
            <hr />
            <br />
            <h1 class="header" id="장래희망">장래희망</h1>
            <div class="font-padding">
                <img class="image-ridding" src="정보보안전문가.jpg" />
                <br />
                <p>저의 꿈은 정보보안전문가입니다.</p>
                <p>구체적으로는 회사들의 정보가 들어있는 공용,사설 클라우드를 보호하는 정보보안전문가가 되는것입니다.</p>
                <p>그 꿈을 이루기 위해서 따로 네트워크 공부와 보안의 기초를 배울것 입니다.</p>
                <br />
                <br />
                <br />
                <hr />
                <br />
            </div>
        </div>
    </div>
</body>
</html>
