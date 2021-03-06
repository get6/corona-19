# 코로나 AWS API Gateway 가이드

URL: https://qvkm5mawta.execute-api.ap-northeast-2.amazonaws.com/corona

자세한 설명 URL: https://github.com/dhlife09/Corona-19-API/blob/master/README.md

GET으로 실행시 결과  
```
{
   "resultCode": "0",
   "TotalCase": "10,423",
   "TotalRecovered": "6,973",
   "TotalDeath": "204",
   "NowCase": "3,246",
   "city1n": "대구",
   "city2n": "경북",
   "city3n": "기타",
   "city4n": "경기",
   "city5n": "서울",
   "city1p": "65.31",
   "city2p": "12.66",
   "city3p": "10.54",
   "city4p": "5.81",
   "city5p": "5.66",
   "recoveredPercentage": 66.9,
   "deathPercentage": 1.96,
   "checkingCounter": "15,509",
   "checkingPercentage": "3.1",
   "caseCount": "10,423",
   "casePercentage": "2.1",
   "notcaseCount": "468,779",
   "notcasePercentage": "94.8",
   "TotalChecking": "494,711",
   "TodayRecovered": "197",
   "updateTime": "코로나바이러스감염증-19 국내 발생현황 (4.9. 00시 기준)",
   "resultMessage": "정상 처리되었습니다."
}
```

POST로 실행시 - 2020.04.09 오후 8시 05분 API 제공 서버 응답 오류  

post body에 전달되어야 할 parameter  
```
{
	“path” = “country”
}
```

결과
```
{
    "resultCode": "0",
    "data0_0": "합계",
    "data0_1": "39",
    "data0_2": "10,423",
    "data0_3": "6,973",
    "data0_4": "204",
    "data0_5": "20.10",
    "data1_0": "서울",
    "data1_1": "12",
    "data1_2": "590",
    "data1_3": "174",
    "data1_4": "2",
    "data1_5": "6.06",
    "data2_0": "부산",
    "data2_1": "0",
    "data2_2": "125",
    "data2_3": "97",
    "data2_4": "3",
    "data2_5": "3.66",
    "data3_0": "대구",
    "data3_1": "4",
    "data3_2": "6,807",
    "data3_3": "5,106",
    "data3_4": "139",
    "data3_5": "279.38",
    "data4_0": "인천",
    "data4_1": "0",
    "data4_2": "84",
    "data4_3": "31",
    "data4_4": "0",
    "data4_5": "2.84",
    "data5_0": "광주",
    "data5_1": "0",
    "data5_2": "27",
    "data5_3": "15",
    "data5_4": "0",
    "data5_5": "1.85",
    "data6_0": "대전",
    "data6_1": "0",
    "data6_2": "39",
    "data6_3": "20",
    "data6_4": "0",
    "data6_5": "2.65",
    "data7_0": "울산",
    "data7_1": "0",
    "data7_2": "40",
    "data7_3": "28",
    "data7_4": "1",
    "data7_5": "3.49",
    "data8_0": "세종",
    "data8_1": "0",
    "data8_2": "46",
    "data8_3": "16",
    "data8_4": "0",
    "data8_5": "13.44",
    "data9_0": "경기",
    "data9_1": "10",
    "data9_2": "606",
    "data9_3": "259",
    "data9_4": "11",
    "data9_5": "4.57",
    "data10_0": "강원",
    "data10_1": "0",
    "data10_2": "49",
    "data10_3": "24",
    "data10_4": "1",
    "data10_5": "3.18",
    "data11_0": "충북",
    "data11_1": "0",
    "data11_2": "45",
    "data11_3": "30",
    "data11_4": "0",
    "data11_5": "2.81",
    "data12_0": "충남",
    "data12_1": "1",
    "data12_2": "138",
    "data12_3": "105",
    "data12_4": "0",
    "data12_5": "6.50",
    "data13_0": "전북",
    "data13_1": "0",
    "data13_2": "17",
    "data13_3": "7",
    "data13_4": "0",
    "data13_5": "0.94",
    "data14_0": "전남",
    "data14_1": "0",
    "data14_2": "15",
    "data14_3": "4",
    "data14_4": "0",
    "data14_5": "0.80",
    "data15_0": "경북",
    "data15_1": "0",
    "data15_2": "1,320",
    "data15_3": "968",
    "data15_4": "47",
    "data15_5": "49.58",
    "data16_0": "경남",
    "data16_1": "2",
    "data16_2": "115",
    "data16_3": "82",
    "data16_4": "0",
    "data16_5": "3.42",
    "data17_0": "제주",
    "data17_1": "0",
    "data17_2": "12",
    "data17_3": "4",
    "data17_4": "0",
    "data17_5": "1.79",
    "data18_0": "검역",
    "data18_1": "10",
    "data18_2": "348",
    "data18_3": "3",
    "data18_4": "0",
    "data18_5": "-",
    "resultMessage": "정상 처리되었습니다."
}
```

