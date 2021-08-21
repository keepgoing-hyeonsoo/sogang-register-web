# 서강신청

---

## 주요 기술 스택

### context api

개발 초기 단계에서는 컴포넌트가 그렇게 많지 않아서 state 관리함에 있어서 큰 어려움이 없었지만, 컴포넌트가 많아지다보니 state를 넘겨줌에 있어서 depth 가 너무 깊어져서 불편함이 많았다. 사용자 로그인상태, 스낵바 경고창, 로딩상태 등 전역적인 state 관리가 필요한 경우에 context api 를 도입하여 개발을 하였다.

## 페이지 구성

### 개설 교과목 검색 페이지

#### [검색옵션&필터 설정 UI]

- **검색옵션** : 학년도/학기, 전공/영역, 학년, 학점, 요일, 검색어 옵션을 클릭하면 모달창이 열리면서 원하는 옵션을 선택할 수 있다. 선택한 옵션은 태그 형식으로 하단부에 표시된다.
- **필터옵션** : 필터옵션은 검색옵션을 통해 검색된 데이터들을 원하는 옵션에 맞게 필터링해주는 옵션이다.

![검색옵션](gif/검색옵션&필터옵션_2.gif)

#### [검색결과 렌더링]

**카드형식**의 UI를 채택하여, 직관성을 높이고자 하였다.

![카드](gif/카드.png)

#### [상세보기 사이드바]

- **과목정보 상세보기** : 해당 과목의 카드를 클릭하면, 과목정보에 대한 상세한 정보를 보여준다.
- **최근 본 과목** : 과목 클릭 시, 최근 본 과목을 사용자에게 보여주어서 UX를 개선시키고자 하였다.
- **즐겨찾기** : **과목정보 상세보기** 에서 즐겨찾기 아이콘을 클릭하면, 즐겨찾기 DB에 담기고 목록에 렌더링 시켜준다.

![상세보기](gif/즐겨찾기_2.gif)

### 마이페이지

### 피드백/문의 페이지

## 기술 스택 (Technique Used)

## 팀 정보 (Team Information)
