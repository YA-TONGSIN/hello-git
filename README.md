# hello-git

git과 GitHub 사용법 연습용 저장소.

2026-10-06 생성.

---

## 올리는 순서 (이 저장소로 연습한 것)

```bash
git init                 # 로컬 저장소 시작
git add .                # 올릴 파일 선택
git commit -m "메시지"    # 로컬에 기록
git remote add origin <주소>   # 올릴 곳 지정 (최초 1회)
git push -u origin main  # 실제로 올림
```

두 번째부터는 세 줄이면 된다.

```bash
git add .
git commit -m "메시지"
git push
```

## 용어

| 명령 | 뜻 |
|---|---|
| `add` | "이 파일들을 다음 기록에 포함시킬게" |
| `commit` | "여기까지를 하나의 기록으로 저장" (내 컴퓨터 안) |
| `push` | "그 기록들을 GitHub로 보냄" |
| `origin` | 올릴 곳의 별명. 보통 내 GitHub 저장소 |
| `main` | 기본 가지(branch) 이름 |

`commit`은 내 컴퓨터에만 저장된다. `push`를 해야 GitHub에 올라간다.
이 둘을 헷갈리면 "분명 저장했는데 GitHub에 없다"가 된다.

## 다음

2027년 1월, `obbkit` 저장소를 같은 순서로 올린다.
절차는 `C:\Users\신운종\.openclaw\workspace\공개프로젝트_01.md` 의 "공개 절차" 참고.
