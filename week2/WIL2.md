## 내가 배운것들 

### Fork
* 다른 유저의 레포지토리를 자신의 계정으로 복사하여 독립적으로 수정하고 관리
### Branch and merge
* 이름 양식 - "type/issue번호-간략한설명"
* 메인 브런치와 분리된 별도의 작업공간을 만들고 메인 브런치로 병합
### Pull Request
* Branch를 다시 병합하기 위한 절차
* 새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결
* Merge에 앞서 코드 리뷰
### Merge의 세가지 옵션
1. Merge commit
 * 두 브랜치를 공통 부모로 하는 새로운 commit ‘E’를 만듦
 * A, B, C의 커밋이 그대로 main 브랜치로 병합
2. Squash and Merge
* A, B, C의 커밋을 'squash’
* => 하나의 커밋으로 main 브랜치로 병합
3. Rebase and Merge
* A, B, C 커밋의 base를 재설정
* 모두 새로윤 커밋으로 변경

[과제2실습] (https://github.com/amelon0424/2024-1-Beginner-Study/pull/2)