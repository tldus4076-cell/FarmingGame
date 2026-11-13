# 기능 1 프롬프트: Unity 6 Universal 3D 프로젝트 만들기

아래 `text` 상자 안의 내용을 다음 AI 작업 요청으로 그대로 사용하세요.

```text
나는 게임 개발 초보자이고, Unity 6으로 3D 섬마을 농장 생활 RPG를 만들고 있어.

코랄 아일랜드의 "생활 + 농장 + RPG" 장르와 따뜻한 섬 분위기를 참고하지만, 원작을 복제하지 않고 나만의 게임을 만들 거야.

이번에는 기능 목록 1번인 "Unity 프로젝트 만들기"만 하고 싶어.

참고 문서 위치:
- C:\Users\cum\OneDrive\문서\Farming game\FarmingGame_AI_Guide.md
- C:\Users\cum\OneDrive\문서\Farming game\FarmingGame_FeatureList.md

작업 폴더:
- C:\Users\cum\OneDrive\문서\Farming game

만들 Unity 프로젝트 폴더:
- C:\Users\cum\OneDrive\문서\Farming game\IslandFarm

개발 환경 목표:
- Unity 6의 설치된 안정 버전 사용
- Universal 3D 템플릿 사용
- URP(Universal Render Pipeline, 범용 렌더 파이프라인) 사용
- C# 사용
- 목표 플랫폼은 Windows PC
- 나중에 Unity의 새 Input System을 사용할 예정이지만 이번 기능에서는 설치하지 않음
- 3D 게임으로 시작
- 위에서 비스듬히 내려다보는 농장 게임 카메라는 나중 기능에서 만듦

현재 상태:
- C:\Users\cum\OneDrive\문서\Farming game 폴더에는 설명용 Markdown 문서만 있어.
- Unity 프로젝트는 아직 만들지 않았어.
- 완료된 기능은 아직 없어.
- 이번 단계에서는 게임 코드, 농장, 플레이어, 카메라 시스템을 만들지 않아.

이번 목표:
- Unity Hub에서 Unity 6 Universal 3D 프로젝트를 정확한 위치와 이름으로 만드는 방법을 안내해줘.
- 프로젝트를 연 뒤 기본 SampleScene 또는 새 빈 Scene에서 Play 버튼을 눌러 오류 없이 실행되는지만 확인하고 싶어.
- Unity 버전과 렌더 파이프라인이 맞는지 확인하고 싶어.

작업 전 확인:
- 먼저 작업 폴더에 IslandFarm Unity 프로젝트가 정말 없는지 확인해줘.
- 이미 IslandFarm 프로젝트가 있다면 절대 덮어쓰거나 삭제하지 마.
- 이미 있다면 `Assets`, `Packages`, `ProjectSettings` 폴더가 있는 정상 Unity 프로젝트인지 확인하고, 새로 만드는 대신 현재 상태를 알려줘.
- 폴더 상태를 실제로 확인할 수 없는 환경이면 확인했다고 말하지 말고, 내가 직접 확인하는 방법을 알려줘.

조건:
- 이번에는 기능 1번 "Unity 프로젝트 만들기"만 안내해줘.
- Unity Hub에서 누를 메뉴와 버튼을 순서대로 알려줘.
- Unity 6 버전 선택 방법을 알려줘.
- 템플릿은 Universal 3D를 선택해줘.
- Project name은 IslandFarm으로 해줘.
- Location은 C:\Users\cum\OneDrive\문서\Farming game 으로 해줘.
- 최종 프로젝트 경로가 C:\Users\cum\OneDrive\문서\Farming game\IslandFarm 이 되는지 확인하게 해줘.
- Unity Cloud 연결은 필수가 아니라고 알려줘.
- 버전 관리 연결은 이번 단계에서 만들지 마.
- 외부 Asset이나 Package를 설치하지 마.
- 새 C# 스크립트를 만들지 마.
- Assets 폴더 구조는 다음 기능에서 만들 것이므로 이번에는 만들지 마.
- Scene 이름 변경은 다음 기능에서 할 것이므로 이번에는 하지 마.
- 기본 Main Camera와 Directional Light를 삭제하거나 수정하지 마.
- URP 설정 파일을 수동으로 바꾸지 마.
- 자동 설정용 Editor 스크립트나 메뉴를 만들지 마.

저작권 조건:
- Coral Island 원본 로고, 캐릭터, 그림, 3D 모델, 지도, 음악, 효과음, 대사, 코드를 가져오거나 복사하지 마.
- 프로젝트 이름은 개발용 이름인 IslandFarm을 사용해줘.
- 이번에는 Unity 기본 리소스만 사용해줘.

Unity Hub 안내에 반드시 포함할 내용:
- Unity Hub를 여는 방법
- Projects에서 New project를 누르는 방법
- 설치된 Unity 6 Editor를 선택하는 방법
- Universal 3D 템플릿을 고르는 방법
- Project name에 IslandFarm을 입력하는 방법
- Location에는 부모 폴더인 C:\Users\cum\OneDrive\문서\Farming game 을 선택하는 이유
- Create project를 누른 뒤 가져오기와 컴파일이 끝날 때까지 기다리는 방법
- Windows 방화벽이나 Unity 로그인 창이 나왔을 때 프로젝트 생성과 관계없는 선택은 건너뛸 수 있다는 설명

프로젝트가 열린 뒤 확인할 내용:
- Unity 창 제목 또는 프로젝트 위치에서 IslandFarm인지 확인
- Project 창에 Assets와 Packages가 보이는지 확인
- Hierarchy 창에 기본 Main Camera와 Directional Light가 보이는지 확인
- Console 창을 여는 메뉴 경로를 알려주기
- Console의 빨간 Error 개수를 확인하기
- Play 버튼을 한 번 눌렀다가 다시 눌러 종료하기
- 기본 화면이 단색 또는 빈 화면이어도 정상이라는 설명
- Play Mode가 끝난 상태인지 확인하기

중요한 테스트 상황:
- C:\Users\cum\OneDrive\문서\Farming game\IslandFarm 폴더가 생기면 성공.
- 그 폴더 안에 Assets, Packages, ProjectSettings 폴더가 있으면 성공.
- Unity에서 프로젝트가 정상적으로 열리면 성공.
- Hierarchy에 기본 Main Camera와 Directional Light가 보이면 성공.
- Play를 눌렀을 때 Unity가 멈추거나 강제 종료되지 않으면 성공.
- Console에 빨간 컴파일 Error가 0개이면 성공.
- 빈 Game 화면은 아직 물체를 만들지 않았으므로 실패가 아니라 정상임.

오류 상황 안내:
- Universal 3D 템플릿이 보이지 않을 때 확인할 방법을 알려줘.
- Unity 6 Editor가 설치되지 않았을 때 Unity Hub의 Installs에서 설치하는 방법을 알려줘.
- 프로젝트 생성이 실패하면 경로, 디스크 공간, 권한을 확인하는 방법을 알려줘.
- OneDrive 동기화 때문에 파일 잠금 오류가 생길 경우 먼저 Unity를 닫고 동기화 상태를 확인하도록 알려줘.
- 오류가 생겨도 프로젝트 폴더를 바로 삭제하라고 하지 마.
- Console에 빨간 오류가 있으면 첫 번째 오류를 펼쳐 전문을 보내달라고 알려줘.

코드 작성 조건:
- 이번 기능에는 코드가 필요 없어.
- C# 파일을 만들지 마.
- JSON이나 Unity 설정 파일을 손으로 생성하지 마.
- Unity 프로젝트처럼 보이게 빈 폴더만 임의로 만들지 마.
- Unity Hub가 실제 프로젝트 파일을 만들게 해줘.

저장 조건:
- 프로젝트가 열리면 기본 Scene을 Ctrl + S로 한 번 저장하는 방법을 알려줘.
- 저장 위치를 묻는 창이 나올 경우 이번 기능에서는 기본 Assets 안에 `SampleScene` 이름으로 저장해도 된다고 알려줘.
- Scene 폴더 생성과 Farm 씬 생성은 기능 2번과 3번에서 할 것이므로 미리 하지 마.

반드시 아래 형식으로 답해줘:

1. 기능 설명
2. 작업 전 폴더 확인 결과
3. 이번 기능에서 만들거나 수정할 파일
4. Unity Hub에서 프로젝트 만드는 방법
5. Unity 프로젝트가 열린 뒤 확인 방법
6. Unity 6과 Universal 3D 확인 방법
7. 오류 체크 포인트
8. 테스트 성공 기준
9. 저장 방법
10. 다음 기능으로 넘어가기 전 체크리스트

설명 스타일:
- 초등학생도 이해할 수 있게 아주 쉬운 한국말로 차근차근 설명해줘.
- 버튼을 누르는 순서를 번호로 자세히 알려줘.
- 영어 용어가 나오면 바로 뒤에 한국말 뜻과 역할을 알려줘.
- Project(프로젝트), Universal 3D, URP, Scene(씬), Hierarchy(하이어라키), Console(콘솔), Play Mode(플레이 모드)가 무엇인지 설명해줘.
- 실제로 확인하지 못한 항목은 확인했다고 말하지 마.
- 이번 단계에서 코드가 필요 없는 이유도 설명해줘.
- 마지막에 내가 외워야 할 핵심을 5줄 이내로 정리해줘.

주의:
- 이번에는 기능 1번만 진행해줘.
- 기능 2번 폴더 정리를 미리 하지 마.
- 기능 3번 Farm 씬을 미리 만들지 마.
- 플레이어, 농장 바닥, 카메라, 조명, UI, 시간, 저장 기능을 미리 만들지 마.
- 내가 Unity에서 직접 테스트한 뒤 "기능 1 완료"라고 말하기 전에는 다음 기능으로 넘어가지 마.
- 기능 1이 성공하면 다음 코드를 바로 만들지 말고, 내가 완료했다고 알려줄 때까지 기다려줘.
```

## 사용 방법

1. 위 `text` 상자 안의 내용을 전부 복사해서 AI에게 보냅니다.
2. AI의 설명을 보면서 Unity Hub에서 직접 프로젝트를 만듭니다.
3. `FarmingGame_FeatureList.md`의 기능 1 성공 기준을 모두 시험합니다.
4. 문제가 생기면 다음 기능을 요청하지 말고 Console의 첫 번째 빨간 오류 전문을 AI에게 보냅니다.
5. 성공하면 Scene을 `Ctrl+S`로 저장합니다.
6. 아래 완료 보고 문장을 사용합니다.

```text
기능 1 완료했어.

확인한 내용:
- IslandFarm 프로젝트 폴더 생성 확인
- Assets, Packages, ProjectSettings 폴더 확인
- Unity 6에서 프로젝트 열기 성공
- Play 실행과 종료 성공
- Console 빨간 오류 0개
- Ctrl+S 저장 완료

이제 FarmingGame_FeatureList.md의 기능 2번 하나만 확인해서,
FarmingGame_Feature1_Prompt.md와 같은 자세한 스타일로
FarmingGame_Feature2_Prompt.md 파일을 만들어줘.
아직 기능 2를 실제로 적용하거나 기능 3을 미리 만들지는 마.
```

## 기능 1에서 외울 것

- Unity 프로젝트는 게임 파일 전체를 담는 큰 가방입니다.
- 이번 프로젝트는 Unity 6의 Universal 3D로 만듭니다.
- 프로젝트 최종 경로는 `C:\Users\cum\OneDrive\문서\Farming game\IslandFarm`입니다.
- Console의 빨간 오류가 0개인지 확인합니다.
- 기능 1 테스트가 끝나기 전에는 기능 2로 넘어가지 않습니다.
