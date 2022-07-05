# Handwritten Assignment

## Contents

- 프로그래밍과제 제외 문제풀이 과제, 수기과제 모음

## git에 큰 파일 올리는 법

push 한 번 당 100MB의 용량을 넘지 못한다 그때 해결법

```bash

$ git lfs track <big file>

$ java -jar bfg-1.13.0.jar --strip-blobs-bigger-than 100M

$ git repack && git gc # error날 시, 해당 명령하고 다시 위 명령 실행

$ git push

```
