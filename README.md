# kakao_profile
카카오톡 프로필 화면입니다.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Merry christmas</title>
    <link rel="stylesheet" type="text/css" href = "style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poor+Story&display=swap" rel="stylesheet">
</head>
<body>
    <div class="wrap">
        <div class="status_box">
            <!--        block 형태 쓰는게 better-->
            <span>모두 메리 크리스마스!</span>
        </div>
        <div class="profile-img">
            <img src="./icons/07.jpeg" alt="인생은 회전목마">
            <h3>전승현</h3>
        </div>
        <div class="funcs">
            <div class="button-box">
                <img src="./icons/mechat.png" alt="채팅">
                <span>나와의 채팅</span>
            </div>
            <div class="button-box">
                <img src="./icons/profileadmin.png" alt="프로필 관리">
                <span>프로필 관리</span>
            </div>
            <div class="button-box">
                <img src="./icons/kakaostory.png" alt="카카오스토리">
                <span>카카오 스토리</span>
            </div>
        </div>
    </div>

</body>
</html>
--------------------------------------------------------------
* {
    font-family: 'Poor Story', cursive;
    font-weight: bold;
}

.wrap {
    margin: 0 auto;
    background-color: #3b9446;
    width: 480px;
    height: 800px;
    border: 1px solid #b4b4b4;
    box-shadow: 10px 10px 10px #b4b4b4;
    position: relative;
}

.status_box {
    width: inherit;
    height: 470px;
    background-color: #941219;
}

.status_box span {
    display: block;
    text-align: center;
    line-height: 30;
    color: #fff;
    font-size: 20px;
}

.profile-img {
    width: 150px;
    height: 150px;
    position: absolute;
    float: left;
    margin: -75px 0 0 165px;
}

.profile-img > h3 {
    text-align: center;
    color: white;
    margin-top: 10px;
}

.profile-img > img {
    border-radius: 75px;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.button-box {
    float: left;
    width: 100px;
    height: 100px;
    text-align: center;
    margin: 150px 10px 20px 20px;
}

.button-box > img {
    padding: 20px;
    width: 60px;
    height: 60px;
}

.funcs > .button-box:nth-child(1) {
    margin-left: 65px;
}

.button-box > span {
    color: white;
}
![image](https://user-images.githubusercontent.com/79038451/147201380-7f476f8b-f70f-4888-b769-49650f341124.png)

