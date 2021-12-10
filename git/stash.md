
# stash
- [지옥에서 온 Git - stash](https://www.youtube.com/watch?v=ArNd5sSwD04)
- 작업중에 커밋하기 전에 다른 브랜치로  checkout 해야 할 경우 사용

- 다음과 같은 상황 고려
1. master 브랜치에서 작업
2. 커밋
3. test 브랜치 생성
4. test 브랜치 에서 작업
5. 여기서 master 브랜치로 체크아웃하면 test 브랜치의 내용이  master 에도 적용됨

- stash 하기
```bash
git stash save
```
```bash
git stash apply
```