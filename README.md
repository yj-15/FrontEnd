# FrontEnd


 **Bootstrap Grid System**
 --------------------------------------------------------
 
 Bootstrap이 가장 많이 사용되는 이유이자 반응형 웹페이지를 만들기 위해서 가장 많이 사용이 필요한 기능

기본적으로 12 column으로 나누어 기능 제공
테이블의 형식대로 row class와 col class로 자유로이 구성 가능 (Bootstrap에서 알아서 크기에 따라 반응형으로 동작하도록 만듦)

**[ Grid System Rule ]** 
- row 클래스는 container나 container-fluid 안에 있어야 정상지원 가능
- 내용은 col class 안에 있어야 하며, row 직속으로 배치
- 칼럼은 총 12 columns이 있는 것으로 정의하여 각 배치할 %에 따라서 class를 결정
ex) 같은 넓이의 3개의 칼럼을 쓰고자 한다면 3개의 col-xs-4 칼럼 사용
- 12 columns 넘어갈 시에 새로운 row로 column이 배치됨

**[ Grid System Column types ]**

|  Types | Description |
|--|--|
| col-xs- | 항상 가로로 배치 |
| col-sm- | 768px 이하에서 세로로 표시 시작|
| **col-md-** | **992px 이하에서 세로로 표시 시작**|
| col-lg- | 1200px 이하에서 세로로 표시 시작|

	 
