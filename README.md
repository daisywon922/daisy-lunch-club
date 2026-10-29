# Daisy 밥친구 도감

## GitHub Pages 배포
1. 이 폴더 안의 index.html, manifest.webmanifest, assets 폴더, .nojekyll을 저장소 루트에 올립니다.
2. GitHub Settings → Pages → Deploy from a branch → main / (root) → Save를 선택합니다.
3. 배포가 끝나면 표시된 HTTPS 주소를 아이폰 Safari에서 엽니다.
4. 공유 → 홈 화면에 추가로 앱 아이콘을 확인합니다.

## 유지한 기능
검색, 전체/조직별 보기, 식사 완료/취소 및 진행률, 구성원 추가/수정, 메모, 관리 제외/복구, 백업/복원, 완료 축하창, 밥알 효과, 2.5초 시작 스플래시를 유지했습니다.
첨부 HTML의 원본 밥 이미지로 홈 화면 아이콘도 구성했습니다. 별도 아이콘 파일은 원본 첨부에 없었습니다.

## 익명화와 저장
직원 이름은 가상 영어 이름으로, 소속은 A그룹·B그룹 및 A팀·B팀 형태로 교체했습니다. 원본 이름 매핑과 원본 파일은 포함하지 않습니다.
데모 저장 키와 백업 식별자를 분리하므로 이전 앱 기록과 백업을 불러오지 않습니다. 이 패키지는 이전 앱이 다른 주소에 저장했던 데이터를 삭제하지 않습니다.
기록은 사용하는 브라우저의 로컬 저장 공간에 저장되며 다른 사람과 공유되지 않습니다. 테스트에는 가상 정보만 입력하고 데모에서 만든 백업만 복원하세요. 직접 입력하거나 복원하는 문자열을 자동 익명화하는 기능은 없습니다.

## 아이폰 점검
viewport, 안전 영역 여백, 입력창 자동 확대 방지, 홈 화면 아이콘, standalone 설정과 상대 경로 manifest를 반영했습니다.
원래의 HTML 스플래시를 유지하며 iOS 전용 정적 시작 이미지는 추가하지 않았습니다. 오프라인 캐시 기능은 없습니다.
실제 아이폰 Safari에서 배포 주소와 홈 화면 실행, 키보드 표시, 백업/복원을 최종 확인하세요.

참고: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html
