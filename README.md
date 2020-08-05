<!DOCTYPE html>
<html>
  <head>
      <style>
        .navi {
          list-style:none;
          float:left;
          background-image: url("bar-01.png");
          width: 1300px;
          height: 80px;
        }

        .navi_li {
          float:left;
          margin:5px 200px 5px 10px;
          color: #ffffff;
          font-weight: bold;
          line-height: 70px;
        }

a:link {text-decoration:none; color: #ffffff}
a:visited {text-decoration:none; color: #ffffff}
a:active {text-decoration:none; color: #ffffff}
a:hover {text-decoration:none; color: #ffffff}
        </style>
  </head>
  <body>
          <div><a href="https://github.com/myriarm/1.html">
          <p align="center"><img border="0" src="main.png" title="개나대는 웹사이트" width="60%" /></p></a></div>
          <input type="button" value="야간모드" onclick="
          document.querySelector('body'). style.backgroundColor='black';
          document.querySelector('body'). style.color='white';
          ">
          <input type="button" value="주간모드" onclick="
          document.querySelector('body'). style.backgroundColor='white';
          document.querySelector('body'). style.color='black';
          ">
          <input type="button" value="금지된 버튼" onclick="
          alert('지금 이 창을 닫으면 너는 궁금해 죽을 것이나, 탐색을 계속할 경우 너의 두 눈을 버리게 될 것이다.')">
          <br>
          <input type="text" onchange="alert('')">
          <input type="button" value="검색" onclick="alert('내용을 입력하세요')">
          <ul class="navi">
                    <li class="navi_li"><a href="https://www.naver.com">소개| </a></li>
                    <li class="navi_li"><a href="https://www.naver.com">알림| </a></li>
                    <li class="navi_li"><a href="https://www.naver.com">정보| </a></li>
                    <li class="navi_li"><a href="https://www.naver.com">역대급| </a></li>
                    <li class="navi_li"><a href="https://www.naver.com">펌핑| </a></li>
          </ul>
  </body>
  </html>
