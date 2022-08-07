# mypage

<!DOCTYPE html>
<html>
    <head>
        <!-- 웹페이지 보이지는 않지만, 필요한 설정을 해두는 곳이에요.
             우리가 집을 위해 미리 생각 해놓은 것을 적어두는 곳이라고 할 수 있죠!-->
        <meta charset=“UTF-8” />
        <meta http-equiv=“X-UA-Compatible” content=“IE=edge” />
        <meta name=“viewport” content=“width=device-width, initial-scale=1.0” />
        <meta property=“og:title” content=“르탄이 - 프로필 링크” />
        <meta property=“og:description” content=“어서와 코딩은 처음이지?” />
        <meta property=“og:image” content=“공유할 이미지” />
        <title>르탄이 - 프로필 링크</title>
        <style>
          @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
          * {
              font-family: "Pretendard",serif;
          }
          body {
            background-color: #44398A;
          }
          .profile {
            width: 100px;
            height: 100px;
            
            border-radius: 100%;

            border: 2px solid white;

            background-image: url('kakao.jpg');
            background-position: center;
            background-size: cover;
          }
          .main {
            color: white;
            font-size: 20px;

            margin-top: 30px;
            margin-bottom: 10px;
          }
          .sub {
            color: white;
            font-size: 14px;

            margin-top: 0px;
            margin-bottom: 30px;
          }
          .wrap {
            width: 300px;
            margin: 30px auto 0px auto;

            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
          }
          .wrap > a {
            width: 300px;
            height: 50px;

            background-color: white;
            border-radius: 8px;

            margin-bottom: 10px;

            font-size: 14px;
            font-weight: bolder;
            color: #44398A;

            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;

            text-decoration: none;

            box-shadow: 3px 3px 5px 0px black;
          }
          .wrap > a:hover {
            background-color: #f2f2f2;
          }
        </style>
    </head>
    <body>
      <div class="wrap">
          <div class="profile"></div>
          <h1 class="main">송재현</h1>
          <p class="sub">코딩.. 좋아하세요?</p>
          <a target="_blank" href="https://spartacodingclub.kr/">스파르타코딩클럽</a>
          <a target="_blank" href="https://hanghae99.spartacodingclub.kr/">항해99</a>
          <a target="_blank" href="https://chang.spartacodingclub.kr/">창업 부트캠프 창</a>
          <a target="_blank" href="https://ddingdong.spartacodingclub.kr/">띵동코딩</a>
      </div>
    </body>
</html>
