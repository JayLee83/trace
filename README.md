# trace
<!DOCTYPE html>
<html>
	<head>
		<meta charset="EUC-KR">
		<title>수목원</title>
		<link rel="stylesheet" type="text/css" href="css/style.css">
	</head>
	<body>
		<div id="header">	
			<img src="imgs/main_image_test.jpg" alt="수목원 홍보 이미지" width="100%">
			<div class="menu">
				<ul>
					<li><a href="#">수목원소개</a></li>
					<li><a href="#">방문안내</a></li>
					<li><a href="#">관람안내</a></li>
					<li><a href="#">개인/단체 체험신청</a></li>
					<li><a href="#">고객센터</a></li>
					<li><a href="#">공지사항</a></li>
					
				</ul>
			</div>
		</div>
		<div id="main">
			<div class="info_title">+ 방문안내</div>
			<br><br>
			<div class="info_title_detail">관람안내</div>
			<div class="info_contants">
			★ 수목원은 자연과 더불어 사는 우리 인간에게 매우 소중한 존재입니다. 식물이나 시설을 훼손하거나 타인에게 방해가 되는 행동은 삼가시길 바랍니다.
			</div>
			<div class="info_title_detail">이용요금</div>
			
			<div class="info_contants">
				<table class="info_table">
					<tr>
						<th>평일</th>
						<td>8,000원</td>
					</tr>
					<tr>
						<th>주말</th>
						<td>10,000원</td>
					</tr>
					<tr>
						<th>공휴일</th>
						<td>10,000원</td>
					</tr>
				</table>
			</div>
			
			<div class="info_title_detail">교통안내</div>
			
			<div class="info_contants">
				☆ 버스: 터미널(서울 또는 지방 터미널 등)에서 출발하여 양평 터미널 도착<br>
				☆ 지하철: 용산역 또는 청량리역에서 용문역 도착<br>
				☆ 택시: 양평 터미널이나 용문역에서 택시 이동<br>
			</div>
		</div>
		
	</body>
</html>

@charset "EUC-KR";

*{
margin: 0;
padding: 0;
}

#header {
width:1000px;
}

#main {
width:1000px;
}

.menu{
text-align: center;
}

.menu ul{
margin: auto;
display: inline-block;
}

.menu li{
float: left;
list-style: none;
padding: 15px;
}

.menu a{
padding: 15px 25px;
text-decoration: none;
color: green;
}

a:hover{
background-color: #DBBABA;
color: black;
}

.info_title{
width: 900px;
height: 50px;
margin: 0 25px;
background-color: #AEAAAA;
line-height: 50px;
font-size: 15pt;
font-weight: bold;
}

.info_title_detail{
width: 800px;
height: 50px;
margin: 0 25px;
background-color: #E4E3E3;
line-height: 50px;
font-size: 15pt;
font-weight: bold;
}

.info_contants{
padding: 30px;
font-size: 14pt;
}

.info_table{
border: black solid 1px;
border-collapse: collapse;
}

.info_table tr td{
border: black solid 1px;
padding: 10px 30px;
}

.info_table tr th{
border: black solid 1px;
padding: 10px 30px;
}
