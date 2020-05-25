# educated-html5-css5-newbie
- naver : https://cafe.naver.com/doithtml5
- youtube 공짜 동영상 제공 : https://www.youtube.com/watch?v=bYgCtRqfi7o&feature=youtu.be
- 실행 : https://jsfiddle.net/
- source code : https://github.com/funnycom/html5-css3
- 숙제 1 : https://jsfiddle.net/charleslee/s1tzyLp5/
- 숙제 2 : 선택자 문제는 풀지 못함. : https://jsfiddle.net/charleslee/pxmswc12/

```text
프로젝트 2: 벚꽃 시즌 안내 페이지 만들기

이제까지 배운 내용으로는 웹 페이지를 더 다양한 효과들을 주어 꾸밀 수 있습니다. 이를 바탕으로 올해 벚꽃 시즌에 관한 정보를 제공해주는 페이지를 만들어 봅니다.

본 프로젝트에서는 다음과 같은 교재의 내용을 주로 다루게 됩니다. (다른 강의도 충분히 참고해주세요!)
•강의 08 CSS 박스모델

•강의 09 CSS 레이아웃


•강의 12. 다재다능한 CSS3 선택자


다음 제공해드리는 HTML 및 CSS 파일을 기반으로 하여, 프로젝트를 완성해보세요.
•파일 다운로드: http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000140+type@asset+block@project2.zip


JSFiddle용 이미지 링크(필요시 활용):
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@seoul.PNG
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@cherryblossom.png
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@incheon.PNG
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@map.PNG
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@jeju.PNG
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@busan.PNG
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@jeonju.png
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@deagu.png

폰트:
http://edxlearning.lge.com/asset-v1:LGE+J00002707+P00000239+type@asset+block@IropkeBatangM.woff




요구사항
1.테두리 및 배경 스타일 적용하기
• h3 요소에 다음의 스타일을 적용해봅니다
•배경색: palevioletred
•글씨 색: white
•왼쪽 위/아래 코너의 곡률: 10px
•오른쪽 위/아래 코너의 곡률: 40px

2. 다단 레이아웃 만들기
•아이디가 "intro"인 section 요소를 두 단으로 만들어봅니다.
•두 단 사이에 구분은 1px의 검은색 실선으로 합니다.

3. 선택자 사용해보기
•"지역별 명소" (class 명이 "spot"인 div 요소 내) 부분에 다수의 radio button (input 요소의 유형)이 있습니다. 
해당 input 요소의 "value" 값에 따라 화면 배치를 다르게 해봅니다.
•"seoul"인 경우, position: absolute에서 top은 10px, left는 10px
•"incheon"인 경우, position: absolute에서 top은 10px, left는 40px
•"jeonju"인 경우, position: absolute에서 top은 10px, left는 70px
•"deagu"인 경우, position: absolute에서 top은 10px, left는 100px
•"busan"인 경우, position: absolute에서 top은 10px, left는 130px
•"jeju"인 경우, position: absolute에서 top은 10px, left는 160px

4. 선택자 사용해보기 (심화)

•input 요소(radio button)이 선택됨에 따라 해당 요소의 value 값과 동일한 이름의 이미지가 화면에 보여지도록 합니다.

•참고: 선택된 input 요소는 "input:checked" 선택자를 통해 알 수 있습니다.
```

- 숙제 3 : https://jsfiddle.net/charleslee/ch14a95t/

```text
프로젝트 3: 가변 레이아웃과 미디어 쿼리를 활용하여 반응형 웹 페이지 만들기

2017년도를 기점으로 PC 브라우저보다 Mobile 브라우저에서 더 많은 웹 트래픽이 발생한다고 합니다. 이에 PC와 Mobile을 모두 고려한 웹 페이지를 설계하는 것의 중요성이 계속해서 커지고 있으며, 이를 위해 반응형 웹 페이지를 잘 디자인 하는 것은 매우 중요한 사항이 되었습니다. 이러한 반응형 웹의 가장 보편적인 방법으로 (1) 가변 레이아웃과 (2) 미디어 쿼리가 있습니다. 본 프로젝트에서는 이 두 가지 기법을 활용하여 별도로 파일을 제공하는 웹 페이지를 개선하는 작업을 진행합니다.

본 프로젝트의 원활한 진행을 위해서는 교재에 있는 "넷째마당 반응형 웹 사이트 만들기" 챕터, 그리고 동영상 14장, 15장의 내용을 충분히 숙지하셔야 합니다. 별도의 파일로 제공하는 PC를 위한 화면 구성이 되어 있는 웹 페이지 코드를 수정하여, Mobile에서 접속했을 때 적절한 화면 구성을 출력하는 것이 본 프로젝트의 목표입니다.

•가변 레이아웃 학습 자료

(1) 교재 14장 2절, 3절
(2) 동영상 "14 반응형 웹이란?" 챕터 내 "[동영상] 반응형 웹 디자인"

•미디어 쿼리 학습 자료
(1) 교재 14장 4절, 5절
(2) 동영상 "14 반응형 웹이란?" 챕터 내 "[동영상] 미디어 쿼리"



프로젝트 설명

1. 프로젝트 진행을 위해 기본으로 제공되는 페이지는 기본적으로 1200px의 너비에 최적화 되어 있습니다.
2. 하지만 어떤 너비의 윈도우에서도 적절하게 화면을 보여줄 수 있는 반응형 페이지로 만드는 것이 이번 과제입니다.
3. 레이아웃은 크게 3개의 컨테이너로 구분할 수 있으며, 각각이 현재는 고정된 레이아웃으로 구성되어 있습니다.
4. 고정된 레이아웃에 가변 레이아웃 기법을 적용하여 화면의 크기에 따라 레이아웃이 실시간으로 조정되어야 합니다.
5. 또한 화면 특정 너비보다 작아지게 되면, 미디어 쿼리를 통해 완전히 새로운 레이아웃이 적용되어야 합니다.
5. 가급적 index.html 파일은 건드리지 않고, style.css에서 적절하게 코드 수정 및 추가를 통해 과제를 완성합니다.
6. 아래 동영상과 같이 동작하는 코드를 완성하여 제출하면 됩니다. (하기 요구사항 2개 충족 必)
7. 새로 추가 또는 수정해야 하는 코드는 많지 않으나, 일단은 제공되는 코드와 그에 따른 동작을 이해해야 합니다.
8. 필요에 따라 제공하는 코드 이해를 위해 레이아웃 관련 내용 복습을 진행해야 할 수도 있습니다. (float 속성 등)
9. 본 문제의 해결 방법은 다양하게 있습니다. 종합적인 내용 복습을 통한 학습 효과를 기대해 볼 수 있겠습니다.
10. 좀 더 본 과제를 깊이 있게 수행하고자 하는 분들을 위한 보너스 문제 3개가 제공됩니다. (점수에는 반영 X)
11. 보너스 문제 내용도 반영하여 과제 제출해 주시면 구현 내용에 대해 상세히 리뷰해 드리도록 하겠습니다. (학습효과 배가)

요구사항 (채점 기준이 되니 반드시 숙지 필요)

1. 동적으로 윈도우 크기가 변함에 따라 컨테이너 요소들이 가변 길이를 취하도록 합니다. (가변 레이아웃 적용)
2. 페이지의 너비가 600px 또는 그보다 작아지게 되면 컨테이너들을 세로 방향으로 차례대로 배치합니다. (미디어 쿼리 적용)
※ 채점 기준이 되므로 충분히 숙지해 주시고 동영상 화면과 비교해서 동일하게 동작하는지 꼭 확인해 주세요.

보너스 문제 (채점에는 포함되지 않으나 학습효과에 도움)

1. <picture> 엘리먼트를 활용하여 화면 너비에 따라 다른 이미지를 불러오도록 한다. (이미지 크기가 다른 것을 활용)
2. 폰트 크기가 스크린 크기에 비례하여 조정되도록 한다. (폰트 단위를 px가 아닌 다른 것을 쓰기)
3. <meta> 태그 내에서 viewport 관련 설정을 통해 디바이스 화면 너비에 딱 맞게 랜더링 되도록 한다.
[참고] 위의 내용을 구현하는 방법은 다양하게 있습니다. 관련하여 문의사항이 있는 경우 부담없이 Discussion 게시판에 올려주세요.
```

# 
