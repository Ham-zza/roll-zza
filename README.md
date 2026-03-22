# roll-zza

TRPG 플랫폼 롤20 편의성 개선 유저 스크립트를 공유하기 위한 저장소입니다.<br>
gemini가 작성한 코드 초안을 바탕으로 디테일을 수정했습니다.

<br>

<strong>1. font-resizer 글자수 크기 조절<br></strong>

   버튼 UI를 통해 채팅창의 글자 크기만 조절할 수 있는 단순한 기능입니다.<br>
   적용 시 채팅창 우측 하단에 크기 조절 버튼이 추가되어 글자 크기를 늘리거나 줄일 수 있습니다.

<br>



# 사용자 스크립트 추가하기

1. 크롬이나 웨일 브라우저 주소창 우측에서 <img width="16" height="16" alt="c" src="https://github.com/user-attachments/assets/b2727c88-52d4-4a89-8f04-461035a4d526" />
이렇게 생긴 아이콘을 클릭하고, '확장앱 관리자' 또는 '확장 프로그램 관리'를 클릭합니다.
2. 'Tampermonkey'를 검색해 설치, 확장 프로그램 관리 페이지에서 활성화합니다. (Tampermonkey는 사용자 스크립트를 편하게 관리할 수 있도록 해주는 확장 프로그램입니다.)
3. 다시 <img width="16" height="16" alt="c" src="https://github.com/user-attachments/assets/b2727c88-52d4-4a89-8f04-461035a4d526" /> 아이콘을 누르면 Tampermonkey가 추가되어 있는 것을 확인할 수 있습니다. 여기서 Tampermonkey를 클릭하면 나타나는 창에서 '새 스크립트 만들기'를 선택합니다.
4. 3에서 스크립트 작성 창으로 이동하면, 입력창에 본 저장소에서 사용하고자 하는 스크립트를 통째로 복사해 붙여넣기 합니다.
5. 그 상태에서 ctrl+s를 눌러 저장합니다.
6. 다시 Tampermonkey를 클릭하면 아래와 같이 추가한 스크립트가 나타납니다. 이걸 on 상태로 만들어줍니다.<br>
   <img width="270" height="259" alt="스크린샷 2026-03-22 오후 11 42 07" src="https://github.com/user-attachments/assets/82e21aff-393b-4073-8dcc-5f81c43fec96" />
8. Roll20 채팅방에 들어갔을 때 우측 하단 전송 버튼 옆에 글자 크기 조절 버튼이 나타나면 스크립트 적용 성공입니다!
