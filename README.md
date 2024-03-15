# 자체제작 노션

### [바로가기📝📝](https://yejinotion.vercel.app/)

### 컴포넌트 구조

![IMG_07539C7B41D2-1](https://github.com/prgrms-fe-devcourse/FEDC5-5_Project_Notion_VanillaJS/assets/81412212/9d81d1a6-0da4-4dbc-8108-ccdc8a39d44c)

https://github.com/prgrms-fe-devcourse/FEDC5-5_Project_Notion_VanillaJS/assets/81412212/002fa0f9-3285-48cf-a155-58a563ae4d70

<!-- ## 📌 과제 설명
에디터를 활용한 노션 클론 프로젝트 with VanillaJS

## 👩‍💻 요구 사항과 구현 내용
### 기본 요구사항

- [x]  글 단위를 Document라고 합니다. Document는 Document 여러개를 포함할 수 있습니다.
- [x]  화면 좌측에 Root Documents를 불러오는 API를 통해 루트 Documents를 렌더링합니다.
    - [x] Root Document를 클릭하면 오른쪽 편집기 영역에 해당 Document의 Content를 렌더링합니다.
      -> `EditPage.js`
    - [x] 해당 Root Document에 하위 Document가 있는 경우, 해당 Document 아래에 트리 형태로 렌더링 합니다.
      -> 재귀로 구현
    - [x] Document Tree에서 각 Document 우측에는 + 버튼이 있습니다. 해당 버튼을 클릭하면, 클릭한 Document의 하위 Document로 새 Document를 생성하고 편집화면으로 넘깁니다.
- [x] 편집기에는 기본적으로 저장 버튼이 없습니다. Document Save API를 이용해 지속적으로 서버에 저장되도록 합니다.
      -> `EditPage.js` 에서 onEditing. 디바운스 이용
- [x] History API를 이용해 SPA 형태로 만듭니다.
    - [x] 루트 URL 접속 시엔 별다른 편집기 선택이 안 된 상태입니다.
    - [x] /documents/{documentId} 로 접속시, 해당 Document 의 content를 불러와 편집기에 로딩합니다.
      -> history API와 커스텀이벤트 이용

### 보너스 요구사항
- [x] 기본적으로 편집기는 textarea 기반으로 단순한 텍스트 편집기로 시작하되, 여력이 되면 div와 contentEditable을 조합해서 좀 더 Rich한 에디터를 만들어봅니다.
  -> # 입력으로 < h1> < h2> < h3> 전환
- [x] 편집기 최하단에는 현재 편집 중인 Document의 하위 Document 링크를 렌더링하도록 추가합니다.
  -> `SubPages.js`
- [x] 편집기 내에서 다른 Document name을 적은 경우, 자동으로 해당 Document의 편집 페이지로 이동하는 링크를 거는 기능을 추가합니다.
  -> `Editor.js` '@'입력시 linkWrap요소 생성 및 display를 조절하여 링크를 걸 수 있는 페이지 목록 표시

### 추가 구현사항
- [x] Document목록에 토글을 이용하여 각 하위페이지 표시여부 전환


### 구현 결과
배포 링크 : https://yejinotion-jcg2u8i4j-yejins-projects.vercel.app/

![IMG_07539C7B41D2-1](https://github.com/prgrms-fe-devcourse/FEDC5-5_Project_Notion_VanillaJS/assets/81412212/9d81d1a6-0da4-4dbc-8108-ccdc8a39d44c)


https://github.com/prgrms-fe-devcourse/FEDC5-5_Project_Notion_VanillaJS/assets/81412212/002fa0f9-3285-48cf-a155-58a563ae4d70



## ✅ PR 포인트 & 궁금한 점

- [ ] 컴포넌트 분리가 잘 되었나요? 컴포넌트 간의 콜백함수 전달이 적절한가요?
- [ ] SideBarList에서 Documents 목록을 재귀를 이용하여 그렸는데, 적절한지 궁금합니다.
- [ ] SideBarList에서 Document의 토글 여부를 localStorage와 classname을 이용해서 파악했는데, 다른 방법이 있을까요?
- [ ] 링크걸 페이지 검색화면에 트라이탐색을 이용했는데, 입력때마다 트라이를 새로만드는 한계가 있었습니다. 추가나 삭제 시 해당 노드만 변경하려면 페이지id도 필요한데, 노드에 id와 title모두 저장하는 것이 필요할까요?
- [ ] @입력후 링크걸 페이지 입력칸을 만들기 위해 span요소를 추가하는 방식으로 했는데, 이부분에 개선점을 여쭤보고 싶습니다.
- [ ] Editor.js에서 반복적으로 사용한 부분에 대해 함수로 분리했는데, 알맞게 했는지 알고싶습니다

 -->
