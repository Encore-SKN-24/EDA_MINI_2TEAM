✅ 지금까지 한 작업, 한 줄 요약

개인 브랜치에서 작업 → 커밋 → 원격 푸시 → main으로 이동 → 최신 main 당김 → 개인 브랜치 정리 준비 완료

1️⃣ 개인 브랜치 생성 & 이동 ✅
git checkout -b hwang-in-kyu


main 기준으로 개인 브랜치 생성

팀플에서 이름 기반 브랜치명 👍

2️⃣ 파일 추가 → 커밋 ✅
git add inkyu.py
git commit -m '황인규의 커밋입니다'

1 file changed, 0 insertions(+), 0 deletions(-)


👉 파일은 생성됐지만 내용이 비어 있음
(문제 ❌ 아님, 파일 생성 커밋도 정상)

3️⃣ 개인 브랜치 원격 푸시 ✅
git push origin hwang-in-kyu


✔️ 원격 브랜치 생성
✔️ GitHub에서 PR 링크까지 안내됨 → 완벽

4️⃣ ❌ 브랜치 삭제 에러 (정상적인 에러)
git branch -d hwang-in-kyu
error: cannot delete branch 'hwang-in-kyu' used by worktree

💡 이유

지금 내가 그 브랜치에 서 있는데, 나 자신을 지울 수는 없음

👉 이 에러는 Git이 정상적으로 보호해 준 것

5️⃣ main 브랜치로 이동 (정답 행동) ✅
git switch main

6️⃣ main 최신 상태로 동기화 ✅
git pull


결과:

Fast-forward
 inkyu.py
 lifeisgoodlg.py
 minjun.py


👉 팀원들 작업까지 포함해서
최신 main 상태를 정확히 가져옴

🎯 지금 상태 정리
git branch

* main
  hwang-in-kyu


✔️ main: 최신

✔️ hwang-in-kyu: PR용 브랜치 (이미 원격에 있음)

🧹 이제 개인 브랜치 삭제해도 되는 시점
로컬 브랜치 삭제
git branch -d hwang-in-kyu

원격 브랜치까지 정리 (선택)
git push origin --delete hwang-in-kyu


⚠️ 단, PR 머지 완료 후에만 삭제하는 게 정석

🧠 전체 흐름 (암기용)
main
 └─ hwang-in-kyu (작업)
      ├─ add / commit
      ├─ push
      └─ PR
main
 └─ pull
 └─ 브랜치 삭제
