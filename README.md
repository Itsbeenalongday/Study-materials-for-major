# University

- [x] 전공 공부 자료 모음
- [x] 부족한 부분 파악하기
- [x] 자기관리

## 전공 필수 과목

<table stype = "border:1px solid green; text-align:center">
  <thead>
    <tr>
      <th style = "text-align:center">과목</th>
      <th style = "text-align:center">성적</th>
      <th style = "text-align:center">학점</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">이산수학</td>
      <td style="text-align:center">C+</td>
      <td style="text-align:center">3</td>
    </tr>
     <tr>
      <td style="text-align:center">컴퓨터 프로그래밍</td>
      <td style="text-align:center">A0</td>
      <td style="text-align:center">3</td>
    </tr>
     <tr>
      <td style="text-align:center">컴퓨터 프로그래밍 설계</td>
      <td style="text-align:center">A0</td>
      <td style="text-align:center">3</td>
    </tr>
     <tr>
      <td style="text-align:center">디지털회로</td>
      <td style="text-align:center">B+</td>
      <td style="text-align:center">4</td>
    </tr>
     <tr>
      <td style ="text-align:center">컴퓨터네트워크</td>
      <td style ="text-align:center">A0</td>
      <td style ="text-align:center">3</td>
    </tr>
     <tr>
      <td style ="text-align:center">자료구조</td>
      <td style ="text-align:center">A0</td>
      <td style ="text-align:center">4</td>
    </tr>
     <tr>
      <td style ="text-align : center">컴퓨터구조</td>
      <td style ="text-align : center">A+</td>
      <td style ="text-align : center">3</td>
    </tr>
     <tr>
      <td style ="text-align:center">운영체제</td>
      <td style ="text-align:center">A+</td>
      <td style ="text-align:center">3</td>
    </tr>
     <tr>
      <td style ="text-align:center">객체지향프로그래밍</td>
      <td style ="text-align:center">A+</td>
      <td style ="text-align:center">4</td>
    </tr>
     <tr>
      <td style ="text-align:center">알고리즘</td>
      <td style ="text-align:center">A+</td>
      <td style ="text-align:center">3</td>
    </tr>
     <tr>
      <td style ="text-align:center">컴퓨터통신</td>
      <td style ="text-align:center">A+</td>
      <td style ="text-align:center">3</td>
    </tr>
     <tr>
      <td style ="text-align:center">시스템프로그래밍및실습</td>
      <td style ="text-align:center">A+</td>
      <td style ="text-align:center">4</td>
    </tr>
     <tr>
      <td style ="text-align:center">도메인분석및SW설계</td>
      <td style ="text-align:center"></td>
      <td style ="text-align:center">3</td>
    </tr>
     <tr>
      <td style ="text-align:center">캡스톤 디자인</td>
      <td style ="text-align:center"></td>
      <td style ="text-align:center">6</td>
    </tr>
  </tbody>
</table>

## 전공선택
<table stype = "border:1px solid green; text-align:center">
  <thead>
    <tr>
      <th style = "text-align:center">과목</th>
      <th style = "text-align:center">성적</th>
      <th style = "text-align:center">학점</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:center">창의소프트웨어입문</td>
      <td style="text-align:center">A0</td>
      <td style="text-align:center">3</td>
    </tr>
    <tr>
      <td style="text-align:center">데이터베이스</td>
      <td style="text-align:center">A+</td>
      <td style="text-align:center">3</td>
    </tr>
    <tr>
      <td style="text-align:center">기계학습및데이터마이닝</td>
      <td style="text-align:center">A0</td>
      <td style="text-align:center">3</td>
    </tr>
    <tr>
      <td style="text-align:center">오픈소스SW 입문</td>
      <td style="text-align:center"> </td>
      <td style="text-align:center">3</td>
    </tr>
      <tr>
      <td style="text-align:center">IT전문 영어</td>
      <td style="text-align:center"></td>
      <td style="text-align:center">3</td>
    </tr>
     <tr>
      <td style="text-align:center">IT 집중 교육1, 2</td>
      <td style="text-align:center"></td>
      <td style="text-align:center">12</td>
    </tr>
  </tbody>
</table>

## Contents

+ 노트필기(2019 가을학기부터, 이전 학기것은 스캔해야함)

+ 프로그래밍과제 제외 문제풀이과제, 수기과제 

## git에 큰 파일 올리는 법

push 한 번 당 100MB의 용량을 넘지 못한다 그때 해결법

```bash

$ git lfs track <100M 넘는 파일>

$  java -jar bfg-1.13.0.jar --strip-blobs-bigger-than 100M

$ git repack && git gc # error날 시, 해당 명령하고 다시 위 명령 실행

$ git push

```