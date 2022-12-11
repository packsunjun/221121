# 221121
https://soulno.tistory.com/57                     - 무료 html 탬플릿
https://laragon.org/download/                   -  웹서버 DB서버 동시가능
https://www.cafe24.com/infra/web-hosting/ - 무료 쇼핑몰, 저렴한 호스팅
https://www.dothome.co.kr/web/free/index.php - 무료 호스팅(서버임대)
https://kr.linkedin.com/                             - 구직채용

      <title>문서의 동적 구성</title>

    <script>
        function createDIV() {
            let obj = document.getElementById("parent");
            let newDIV = document.createElement("div");
            newDIV.innerHTML = "새로 생성된 Div입니다.";
            newDIV.setAttribute("id", "myDiv");
            newDIV.style.backgroundColor = "yellow";
            newDIV.onclick = function () {
                var p = this.parentElement; // 부모 HTML 태그 요소
                p.removeChild(this); // 자신을 부모로부터 제거
            };
            obj.appendChild(newDIV);
        }
    </script>


    <title>HTML DOM tree</title>
    
	<script>
	var p = document.getElementById("firstP");
	var text = "p.id = " + p.id + "\n";
	text += "p.tagName = " + p.tagName + "\n";
	text += "p.innerHTML = " + p.innerHTML + "\n";
	text += "p.style.color = " + p.style.color + "\n";
	text += "p.onclick = " + p.onclick + "\n";
	text += "p.childElementCount = " + p.childElementCount + "\n";
	text += "너비 = " + p.offsetWidth + "\n";
	text += "높이 = " + p.offsetHeight + "\n";
	alert(text);
	</script>

        <title>document.getElementBy TagName()</title>
	
        <script>
        function change() {
            let spanArray = document.getElementsByTagName("span");
            for (let i = 0; i < spanArray.length; i++) {
                let span = spanArray[i];
                span.style.color = "orchid";
                span.style.fontSize = "20px";
            }
        }
    </script>
<a href="https://packsunjun.github.io/221121/"><img src="https://img.shields.io/badge/Github-3DDC84?style=flat-square&logo=GitHub&logoColor=white"/></a><br>
<img src="웹 캡처_25-11-2022_144944_.jpeg" width="300" height="1000">>
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fpacksunjun%2F221121&count_bg=%23C8C83D&title_bg=%23FF0000&icon=&icon_color=%23FF00C7&title=%EC%A1%B0%ED%9A%8C%EC%88%98&edge_flat=true)](https://hits.seeyoufarm.com)
