## 팀 규칙 문서

**팀 규칙**은 아래와 같습니다.
- main 직접 push 금지
- 모든 변경은 issue 기반
- 모든 커밋 메시지에 issue 번호 포함
- 모든 작업은 feature branch 에서 진행
- PR 후 최소 1명 리뷰
- pull 사용 금지, fetch 후 직접 merge/rebase 판단

## 각 팀원들의 브랜치 명
- feature/<이슈번호>-<작업명>
- 예시: feature/2-makeReadMeFile

## PR전략
- 브랜치에서는 자유롭게 작업
- PR 머지는 squash merge 기본

## 커밋 양식
- git commit -m"<이슈번호> 커밋메시지"
- 예시: git commit-m"[#2] 팀 협업 규칙 문서 작성"

## 커밋시 주의사항
git push --set-upstream origin feature/2-makeReadMeFile
위와 같이 메인브랜치에 merge하지 마시고, 브랜치 만드셔서 업로드 해주세용.