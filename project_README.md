### 프로젝트 구조
```
팀_프로젝트
├── assets
│   ├── css
│   │   └── style.css           # 기본 스타일 시트, 각 페이지별 css 파일 만들어서 폴더에 삽입
│   ├── images
│   │   └── logo.png            # 프로젝트에 사용하는 이미지 파일들, 다른 파일과 이름 겹치지 않게 해주세요
│   └── js/                     # 동적 html 생성에 필요한 js 코드        
├── templates/
│   ├── components/              # 컴포넌트 폴더, nav, footer 등을 컴포넌트화 한 파일
│   └── index.html              # 메인페이지에 사용될 파일
│   └── template.html           # HTML 기본 골격, 작성 시 기본 base로 사용
├── .gitignore                  # Git에서 제외할 파일 목록
├── app.py                      # 메인 Flask 애플리케이션
└── README.md                   # 프로젝트 설명 문서
```

### icon download
- html 파일에 기본적으로 icon을 사용할 수 있게 설정해두었습니다
- 원하는 아이콘은 해당 링크에서 찾아서 사용하시면 됩니다 https://fontawesome.com/search
- 아이콘 클릭 후 뜨는 코드를 복사해서 원하는 위치에 붙이면 바로 사용 가능합니다.
```
<!-- 아이콘 코드 예시 -->
<i class="fa-solid fa-building"></i>
```