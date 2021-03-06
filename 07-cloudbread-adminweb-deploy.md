###CloudBread 캠프 - CloudBread-Admin-Web 배포
이 문서에서는 CloudBread 캠프에서 CloudBread-Admin-Web을 웹앱에 배포하는 과정을 소개합니다.

###CloudBread Admin-Web 배포
다음 절차를 통해, 지금 방금 생성한 서비스에 CloudBread-Admin-Web을 배포할 수 있습니다. CloudBread는 앱 서비스의 *웹 앱*을 이용합니다.

1. 먼저, https://github.com/CloudBreadProject/CloudBread-Admin-Web 링크로 이동해 우측 상단의 *Fork*를 수행해 자신의 리포지토리로 포크 수행(배포에 필수)
2. https://portal.azure.com에 접속 후 좌측 상단 *리소스 그룹*에서 생성한 리소스 그룹 선택
3. 리소스 리스트에서 생성한 *앱 서비스* 타입의 지구본 아이콘 모양 *웹 앱* 선택
4. *게시 - 연속 배포* 선택
5. 연속 배포에서 *Github* 선택
6. *권한 부여* 항목에 자신의 github 계정 확인
7. 조직 선택 부분에 *개인* 확인
8. *프로젝트 선택*에서 위의 1번 과정에서 Fork를 수행한 자신의 리포지토리의 *CloudBread-Admin-Web*를 선택
9. *지점 선택*에서 최근의 ==**2.0.x 브랜치**== 설정 사용

위의 과정을 수행하시면 바로 배포가 이루어지며, 처음 수행시 5번 과정에서 Github 로그인을 요구할 수 있습니다.
일반적으로 5분 내에 잠시 후 배포가 완료됩니다.

Git에 익숙하시고 자신의 리포지토리에서 Visual Studio로 개발을 원하실 경우 CloudBread wiki -  https://github.com/CloudBreadProject/CloudBread/wiki 문서를 참고해 Git 명령으로 로컬 clone 하시고 Visual Studio에서 프로젝트를 열고 web.config를 수정해 바로 Visual Studio에서 배포 하시면 됩니다.