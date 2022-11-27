# ImageTool

이미지 편집 툴 구현하기

![캡처](https://user-images.githubusercontent.com/100124429/204134926-10193dc4-7f8b-4b7c-8399-dc082ffda686.PNG)

- 기술스탯 및 개발툴
    - Javascript ES6, HTML5, CSS3
    - fabric.js 5.2.4
    - FileSaver.js 2.0.0
    - bootstrap 5.2.2
    - VSCODE
    - Git, Github
    
- 구현 기술
    - 마우스로 이미지를 이동, 선택할 수 있습니다 
    - 이동, 회전, 사이즈 변경, crop, 제출을 버튼 클릭 시 개별 기능 사용 가능합니다.
    - 토글 기능 추가하였습니다.
    - 라이브러리 내 aCoords 요소로 왼쪽 상단 절대 좌표를 가져옵니다.
    - innerHTML으로 왼쪽 하단 div에 절대 좌표를 텍스트로 보여줍니다.
    - 크롬, 엣지에서 가동함을 확인했습니다.
    - onvas의 높이와 너비를 구하여 getZoom 메소드에 비율을 적용합니다.
    - setDimensions로 캔버스의 높이와 너비를 설정하고 setViewportTransform로 뷰포트를변환합니다.
    - toDataURL로 space를 영역을 정한 뒤 Blob을 생성합니다.
    - FileSaver.js를 이용하여 이미지를 다운로드 합니다.
    
