# hsn
<!DOCTYPE html>
<html>
<head>
 <title>hvlst server note</title>
</head>
<body>
 <a href="ÄÚµå 2.html">ºñ¹Ð¹øÈ£ ÀÔ·ÂÇÏ±â</a>
</body>
</html> 
<!DOCTYPE html>
<html>
<head>
 <title>암호를 입력해주세요.</title>
 <style>
  body {
   background-color: lightblue;
   padding: 30px;
  }
 </style>
 <script>
  function checkPassword() {
   var password = document.getElementById("passwordBox");
   var passwordText = password.value;
   if(passwordText == "hvlstadmin") {
    return true;
   }
   alert("OH! 당신은 관리자가 아니군요! 다시한번 시도해보세요!");
   return false;
   }
 </script>
</head>
<body>
 <p style="font-size: 30pt;">천상계 온라인 서버 개발노트를 위한 암호를 입력하시오.</p>
 <p>암호를 입력 후에 밑에 있는 다 되었습니다. 글을 클릭헤주세요. (한/영 구분 필수)</p>
 <p>암호:<input id="passwordBox" type="password"/></p>
 <a href="코드 3.html" onclick="return checkPassword();">
  다 되었습니다.
 </a>
</body>
</html>
