# Hello World!
`# : 가장 큰 헤드라인 (제목) 문자를 표시`

# 마크다운 문법
## 1. 제목 (헤드라인, Headline)
* 1~6까지만 지원
``` makrdown
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
h1
=
h2
-
```

h1
==========
h2
----------
## 2. 수평선
* `*`나 `-`,`_` 등을 3개이상 쓰면 사용 가능
```
***
---
___
```

문단1
***
문단2
---
문단3
___

## 3. 줄바꿈
문장1
문장2

문장1(중간에 엔터)

문장2

문장1(띄어쓰기2칸이상)  
문장2

문장1(br태그)<br>
문장2


## 4. 꾸미기
**굵게**
*기울게*
***굵고 기울게***
~~취소선~~
<u>밑줄</u>

## 5. 인용문
* 박스를 통해서 특정 문구를 강조
* `>` 사용

```
> 첫번째 인용문
>> 두번째 인용문
>>> 세번째 인용문
>>>> 네번째 인용문
```
> 첫번째 인용문
>> 두번째 인용문
>>> 세번째 인용문
>>>> 네번째 인용문

> 나를 죽이지 못하는 시련은 나를 강하게 할 뿐이다  - *니체(독일의 철학자)*

## 6. 목록 (List)
* 목록 -> 순서가 있는 목록, 없는 목록
### 순서가 있는 목록
```
1. 첫번째
    1. 첫번째의 첫번째
    2. 첫번째의 두번째
2. 두번째 
3. 세번째
```

1. 첫번째
    1. 첫번째의 첫번째
    2. 첫번째의 두번째
2. 두번째 
3. 세번째

```
1. 첫번째
1. 첫번째
1. 첫번째
```
1. 첫번째
1. 첫번째
1. 첫번째

* 순서가 있는 목록을 사용시 : 첫번째 등장하는 숫자를 기준으로 오름차순으로 나열하고 중간에 등장하는 수샂가 무엇인지는 상관하지 않음

### 순서가 없는 리스트
```
* 목록
- 목록
+ 목록
    * Tab 들여쓰기 되고요
    * 스페이스로도 되고요
```
* 목록
- 목록
+ 목록
    * Tab 들여쓰기 되고요
    * 스페이스로도 되고요

## 코드
* 마크업 문법을 적용하지 않고, 날 그대로 나타내주는 문법
### 한줄코드

* \` (원화표시를 영어로, 백틱) 한개씩으로 시작과 끝을 감싸줌

`print('Hello World')` <br>
이 사람은 `진짜` 다.

### 여러줄코드(코드블록)
```python
conditon = True
if condition:
    print('ok!')
else:
    print('not ok!')

```
```html
<p> Html </p>
```

## 7. 테이블

* https://www.tablesgenerator.com/markdown_tables

```
|제목1|제목2|제목3|
|----|----|----|
|행1-1|헹1-2|헹1-3|
|행2-1|행2-2|행2-3|
```

|제목1|제목2|제목3|
|-|-|-|
|행1-1|헹1-2|헹1-3|
|행2-1|행2-2|행2-3|

|제목1|제목2|제목3|
|:-|:-:|-:|
|좌측 정렬|가운데 정렬|우측 정렬|
|행2-1|행2-2|행2-3|

## 8. 링크
### 텍스트 링크
```
[표현할 텍스트](연결할 링크 주소)
```
[네이버](http://www.naver.com)

### 이미지 불러오기
```
![설명](연결할 이미지 주소)
```
![고양이](https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg)

### 이미지에 링크 걸기

```
[![설명](연결할 이미지 주소)](연결할 링크 주소)
```

[![고양이](https://cdn.pixabay.com/photo/2014/04/13/20/49/cat-323262_1280.jpg)](https://naver.com)