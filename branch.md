1. branch

* git에서 branch는 특정 커밋에 대한 참조
* 여러 개발자들이 동시에 다양한 작업을 할 수 있게 해준다
* 브랜치는 다른 브랜치와 병합(merge)를 통해 작업한 내용을 하나의 브랜치로 모을 수 있다.

2. checkout
   
* 내가 사용할 브랜치를 지정하는 것
* 브랜치를 바꿀때 사용한다
```
$ git checkout <branch>

<branch> -> 바꿀 branch
```

3. merge

* 브랜치들을 하나의 브랜치로 병합할 때 사용하는 명령어
* 충돌(conflict)가 날 수 있다.
  * 같은 파일이 브랜치에서 각각 수정될 경우
  * 한 브랜치의 파일만 바뀐 경우 바뀐 쪽으로 변경된다(conflict 나지 않는다)
  * 두개 다 바뀌지 않았을 때는 base 내용을 따른다 
```
$ git merge <branch>

<branch> -> 병합할 branch
```

