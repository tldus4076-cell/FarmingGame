# 기능 2 프롬프트: Assets 폴더 정리하기

아래 `text` 상자 안의 내용을 다음 AI 작업 요청으로 그대로 사용하세요.

```text
나는 게임 개발 초보자이고, Unity 6으로 3D 섬마을 농장 생활 RPG를 만들고 있어.

코랄 아일랜드의 "생활 + 농장 + RPG" 장르와 따뜻한 섬 분위기를 참고하지만, 원작을 복제하지 않고 나만의 게임을 만들 거야.

이번에는 기능 목록 2번인 "폴더 정리"만 하고 싶어.

참고 문서 위치:
- C:\Users\cum\OneDrive\문서\Farming game\FarmingGame_AI_Guide.md
- C:\Users\cum\OneDrive\문서\Farming game\FarmingGame_FeatureList.md

작업 폴더:
- C:\Users\cum\OneDrive\문서\Farming game

Unity 프로젝트 폴더:
- C:\Users\cum\OneDrive\문서\Farming game\IslandFarm

개발 환경:
- Unity 6 (6000.3.10f1)
- Universal 3D 템플릿, URP(Universal Render Pipeline, 범용 렌더 파이프라인)
- C#
- 목표 플랫폼은 Windows PC
- 새 Input System은 기능 7번에서 설치하므로 이번에는 건드리지 않음

현재 상태:
- 기능 1번 "Unity 프로젝트 만들기"는 Unity에서 직접 테스트하고 완료했어.
- 기능 2번부터는 아직 아무것도 하지 않았어.
- 현재 Scene은 Unity가 만들어 준 기본 SampleScene이야.
- Hierarchy에는 기본 Main Camera와 Directional Light가 있어.
- Console의 빨간 오류는 없어.
- 내가 컴퓨터에서 확인한 IslandFarm/Assets 안의 현재 내용은 아래와 같아.
  - Scenes 폴더 (안에 SampleScene.unity 가 있음)
  - Settings 폴더 (URP 설정 파일들)
  - InputSystem_Actions.inputactions 파일 (템플릿이 만들어 준 파일)
- 즉, Scenes 폴더는 Universal 3D 템플릿이 이미 만들어 둔 상태야.

이번 목표:
- Assets 아래에 Scenes, Scripts, Prefabs, Art, Audio, Materials, Data, UI 폴더 8개가 모두 보이게 해줘.
- 이미 있는 Scenes 폴더는 그대로 쓰고, 나머지 7개(Scripts, Prefabs, Art, Audio, Materials, Data, UI)만 새로 만들게 해줘.
- 폴더 이름은 영어 대소문자까지 정확히 아래와 같아야 해.

만들어야 할 폴더 8개 (Assets 바로 아래):
- Scenes   (장면 파일 보관, 이미 있음)
- Scripts  (C# 코드 보관)
- Prefabs  (재사용 물체 틀 보관)
- Art      (그림, 3D 모형 보관)
- Audio    (음악, 효과음 보관)
- Materials(물체 표면 재질 보관)
- Data     (아이템, 작물 같은 데이터 에셋 보관)
- UI       (화면 UI 관련 파일 보관)

작업 전 확인:
- 먼저 IslandFarm/Assets 안에 실제로 어떤 폴더와 파일이 있는지 확인해줘.
- 이미 있는 폴더(특히 Scenes)는 새로 만들지 말고 "이미 있음"이라고 알려줘.
- 이름이 비슷하지만 대소문자나 철자가 다른 폴더(예: scripts, Script, Material)가 있는지도 확인해줘.
- 폴더 상태를 실제로 확인할 수 없는 환경이면 확인했다고 말하지 말고, 내가 Unity Project 창에서 직접 확인하는 방법을 알려줘.

조건:
- 이번에는 기능 2번 "폴더 정리"만 안내해줘.
- 폴더는 반드시 Unity의 Project 창에서 만들게 해줘. (Project 창에서 만들면 Unity가 .meta 파일을 함께 만들어 줘서 안전해.)
- Windows 탐색기로 Assets 폴더 안에 직접 폴더를 만들거나 옮기라고 하지 마.
- Project 창에서 Assets 폴더를 마우스 오른쪽 버튼으로 눌러 Create > Folder 를 고르고, 이름을 바꾼 뒤 Enter 를 누르는 순서를 자세히 알려줘.
- 폴더 이름을 정하기 전에 Enter 를 누르면 "New Folder"로 남을 수 있으니 이름을 바로 입력하라고 알려줘.
- 폴더는 Assets 바로 아래에 만들게 해줘. 다른 폴더 안에 중첩해서 만들지 않게 해줘.
- 하위 폴더(예: Scripts/Player, Art/Characters)는 만들지 마. 필요할 때 해당 기능에서 만들 거야.
- 이미 있는 SampleScene.unity, Settings 폴더, InputSystem_Actions.inputactions 는 옮기거나 이름을 바꾸거나 삭제하지 마.
- Scenes 폴더 안의 SampleScene 이름 변경과 Farm 씬 만들기는 기능 3번에서 할 거야.
- 외부 Asset이나 Package를 설치하지 마.
- 새 C# 스크립트를 만들지 마.
- 기본 Main Camera와 Directional Light를 삭제하거나 수정하지 마.
- URP 설정 파일과 Settings 폴더 안의 파일을 바꾸지 마.
- 자동으로 폴더를 만드는 Editor 스크립트나 메뉴를 만들지 마.
- 폴더를 눈에 보이게 하려고 안에 빈 텍스트 파일이나 임시 파일을 넣지 마. (Unity는 빈 폴더도 Project 창에 보여줘.)

저작권 조건:
- Coral Island 원본 로고, 캐릭터, 그림, 3D 모델, 지도, 음악, 효과음, 대사, 코드를 가져오거나 복사하지 마.
- 이번에는 폴더만 만들고 외부 파일은 하나도 넣지 마.

코드 작성 조건:
- 이번 기능에는 코드가 필요 없어.
- C# 파일을 만들지 마.
- JSON이나 Unity 설정 파일을 손으로 생성하지 마.
- 폴더 정리는 Unity 화면에서 하는 작업이라서 코드 대신 정확한 클릭 순서가 중요해. 이 이유도 설명해줘.

저장 조건:
- 폴더 만들기는 파일 시스템에 바로 반영되지만, 마지막에 Ctrl + S 로 열려 있는 Scene을 한 번 저장하는 습관을 알려줘.
- 폴더 8개가 Project 창에 보이면 저장 완료야. 폴더 만들기만으로는 Scene이 바뀌지 않으므로 "변경 사항 없음" 상태일 수 있다고 알려줘.
- Unity를 닫기 전에 Project 창에 폴더 8개가 그대로 보이는지 다시 확인하게 해줘.

반드시 아래 형식으로 답해줘:

1. 기능 설명
2. 작업 전 폴더 확인 결과
3. 이번 기능에서 만들거나 수정할 파일과 폴더
4. Unity Project 창에서 폴더 만드는 방법 (폴더마다 번호 순서로)
5. 폴더가 잘 만들어졌는지 확인하는 방법
6. 오류 체크 포인트
7. 테스트 성공 기준
8. 저장 방법
9. 다음 기능으로 넘어가기 전 체크리스트

설명 스타일:
- 초등학생도 이해할 수 있게 아주 쉬운 한국말로 차근차근 설명해줘.
- 버튼을 누르는 순서를 번호로 자세히 알려줘.
- 영어 용어가 나오면 바로 뒤에 한국말 뜻과 역할을 알려줘.
- Assets(에셋, 게임 재료 보관함), Folder(폴더), Project 창(프로젝트 창), Scene(씬), Prefab(프리팹), Material(머티리얼), Script(스크립트), ScriptableObject(스크립터블 오브젝트, 데이터 카드)가 무엇인지 설명해줘.
- 각 폴더 8개에 무엇을 넣는지 "방 정리"에 비유해서 설명해줘.
- 왜 폴더를 미리 정리하면 나중에 편한지 설명해줘.
- 실제로 확인하지 못한 항목은 확인했다고 말하지 마.
- 이번 단계에서 코드가 필요 없는 이유도 설명해줘.
- 마지막에 내가 외워야 할 핵심을 5줄 이내로 정리해줘.

주의:
- 이번에는 기능 2번만 진행해줘.
- 기능 3번 Farm 씬을 미리 만들지 마. SampleScene 이름도 바꾸지 마.
- 기능 4번 이후의 땅, 조명, 플레이어, 카메라, UI 물체를 미리 만들지 마.
- 폴더 안에 아무 파일도 미리 넣지 마.
- 내가 Unity에서 직접 테스트한 뒤 "기능 2 완료"라고 말하기 전에는 다음 기능으로 넘어가지 마.
- 기능 2가 성공하면 다음 코드를 바로 만들지 말고, 내가 완료했다고 알려줄 때까지 기다려줘.
```

## 테스트 순서와 완료 기준 (참고용)

### 테스트 순서

1. Unity에서 `IslandFarm` 프로젝트를 엽니다.
2. 아래쪽 **Project 창**에서 `Assets` 폴더가 보이는지 확인합니다.
3. `Assets`를 마우스 오른쪽 버튼으로 누르고 **Create > Folder**를 고릅니다.
4. 이름 칸이 파랗게 바뀌면 `Scripts`를 입력하고 Enter를 누릅니다.
5. 같은 방법으로 `Prefabs`, `Art`, `Audio`, `Materials`, `Data`, `UI`를 만듭니다.
6. `Scenes`는 이미 있으니 새로 만들지 않습니다.
7. Project 창에 폴더 8개가 모두 보이는지 확인합니다.
8. Console 창(**Window > General > Console**)의 빨간 Error가 0개인지 확인합니다.
9. Play 버튼을 한 번 눌렀다가 다시 눌러 끕니다.
10. `Ctrl+S`를 누릅니다.

### 테스트 완료 기준

- [ ] `Assets` 바로 아래에 폴더 8개(Scenes, Scripts, Prefabs, Art, Audio, Materials, Data, UI)가 보인다.
- [ ] 폴더 이름의 철자와 대소문자가 정확하다.
- [ ] `New Folder`라는 이름의 폴더가 남아 있지 않다.
- [ ] `SampleScene`, `Settings`, `InputSystem_Actions`는 그대로 남아 있다.
- [ ] 폴더 안에 새 파일을 넣지 않았다.
- [ ] Console의 빨간 Error가 0개다.
- [ ] Play를 눌렀다 끌 수 있고 지금은 Play Mode가 끝난 상태다.

## 사용 방법

1. 위 `text` 상자 안의 내용을 전부 복사해서 AI에게 보냅니다.
2. AI의 설명을 보면서 Unity Project 창에서 직접 폴더를 만듭니다.
3. 위 "테스트 완료 기준"을 하나씩 확인합니다.
4. 문제가 생기면 다음 기능을 요청하지 말고 Console의 첫 번째 빨간 오류 전문(또는 Project 창 모습)을 AI에게 설명합니다.
5. 성공하면 아래 완료 보고 문장을 사용합니다.

```text
기능 2 완료했어.

확인한 내용:
- Assets 아래 폴더 8개(Scenes, Scripts, Prefabs, Art, Audio, Materials, Data, UI) 확인
- 폴더 이름 철자와 대소문자 확인
- SampleScene, Settings, InputSystem_Actions 그대로 있음
- Console 빨간 오류 0개
- Play 실행과 종료 성공
- Ctrl+S 저장 완료

이제 FarmingGame_FeatureList.md의 기능 3번 하나만 확인해서,
FarmingGame_Feature1_Prompt.md와 같은 자세한 스타일로
FarmingGame_Feature3_Prompt.md 파일을 만들어줘.
아직 기능 3을 실제로 적용하거나 기능 4를 미리 만들지는 마.
```

## 기능 2에서 외울 것

- 폴더는 게임 재료를 종류별로 담는 서랍입니다.
- 폴더 8개는 `Scenes, Scripts, Prefabs, Art, Audio, Materials, Data, UI`입니다.
- `Scenes`는 템플릿이 이미 만들었으니 나머지 7개만 만듭니다.
- 폴더는 Windows 탐색기가 아니라 Unity Project 창에서 만듭니다.
- 기능 2 테스트가 끝나기 전에는 기능 3으로 넘어가지 않습니다.
