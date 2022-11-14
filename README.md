# Vaccine reservation program

# 산업기사 문제 풀이과정1)
1)<br>
haeder nav section footer 페이지와<br>
홈화면 index <br>
백신예약 화면 join 그리고 DB로 연결해줄 join_P<br>
백신예약조회 화면 lookup 그리고 결과값을 출력해줄 lookup_P <br>
백신예약현황 화면인 status 페이지로 10페이지정도 되는것같다.<br>
2)<br>
테이블은 총 3개를 만들어야하며 tbl_jomin_202108, tbl_hosp_202108, tbl_vaccresv_202108 이있다<br>
문제지의 있는 데이터값을 sql를 통해서 넣어준후 join_p를 통해 추가 데이터값을 넣어준다<br>
DB연결<br>
![image](https://user-images.githubusercontent.com/96267331/201792920-e70dcaab-497c-498c-ae31-0a041d65c25e.png)<br>
index.jsp화면<br>
![image](https://user-images.githubusercontent.com/96267331/201790525-001149ea-f66b-41aa-9daf-07849e5918c7.png)<br>
haeder nav section footer jsp 파일을 한곳에 묶어 css를 입혀 만들어 준다.<br>
join.jsp 화면<br>
![image](https://user-images.githubusercontent.com/96267331/201790418-f3d7687c-0c0c-4f74-9d38-f729593c28af.png)<br>
form 태그안에 table태그를 통해서 데이터를 입력받을수있는 박스를 만들어준다. 그리고 만든 sql문을 이용하여 예약번호를 자동으로 입력받게한다.<br>
![image](https://user-images.githubusercontent.com/96267331/201792385-be154063-8273-4b7b-8e0e-b0244737e707.png)<br>
등록버튼을 눌렀을때 유효성검사를 하며 만약 비어있는 부분이있으면 그 부분으로 포커스가간다.<br>
![image](https://user-images.githubusercontent.com/96267331/201792405-7da0503d-c0a3-47d7-b9e9-e22bab6e9d5e.png)


