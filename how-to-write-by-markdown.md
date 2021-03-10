# 2. 마크다운 사용법(문법)
## 2.1. 헤더Headers
* 글머리: 1~6까지만 지원
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a H7(지원하지 않음)

:star:2까지는 github에서 보았을때 줄이 쳐져있습니다!

## 2.2. BlockQuote
이메일에서 사용하는 ```>``` 블럭인용문자를 이용한다.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

## 2.3. 목록
### ● 순서있는 목록(번호)
순서있는 목록은 숫자와 점을 사용한다.
```
1. 첫번째
2. 두번째
3. 세번째
    1. 3-1
    2. 3-2
(탭을 두번 눌러 띄워진 상태)
```
1. 첫번째
2. 두번째
3. 세번째
    1. 3-1
    2. 3-2


### ● 순서없는 목록(글머리 기호: `*`, `+`, `-` 지원)
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑

:star:아쉽게도 github는 색상 지원이 흑백밖에 없습니다..

혼합해서 사용하는 것도 가능하다(내가 선호하는 방식)

```
* 1단계
  - 2단계
    + 3단계
      + 4단계
```

* 1단계
  - 2단계
    + 3단계
      + 4단계

## 2.4. 코드
```
텍스트 내용안의 시작부분에 ```
끝 부분에 ```가 들어있으면 코드처럼 보이게 된다.
```
## 2.5. 수평선 ```<hr/>```
아래 줄은 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 *페이지 나누기* 용도로 많이 사용한다.

```
* * *

***

*****

- - -

---------------------------------------
```

* 적용예
* * *

***

*****

- - -

---------------------------------------


## 2.6. 링크
* 외부링크
```
사용문법: [Text](url)
적용예: [Google](https://google.com, "google link")
```
Link: [Google](https://google.com, "google link")

:star:"google link"는 보기 편하는 용도로 넣는것이지 필수는 아닙니다!


* 자동연결
```
일반적인 URL 혹은 이메일주소인 경우 적절한 형식으로 링크를 형성한다.
<url>

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>
```

* 외부링크: <http://example.com/>
* 이메일링크: <address@example.com>

## 2.7. 강조
```
*single asterisks*
_single underscores_ 

**double asterisks**
__double underscores__

~~cancelline~~
```

*single asterisks* \
_single underscores_ 

 **double asterisks** \
 __double underscores__ 

 ~~cancelline~~


## 2.8. 이미지
```
![text](path url)
![text](path url "Optional title")
```
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0)
![석촌호수 러버덕](http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0 "RubberDuck")

:star:(path url) 부분에 로컬 사진을 넣거나, 인터넷 사진 링크를 넣어도 가능!

사이즈 조절 기능은 없기 때문에 ```<img width="" height=""></img>```를 이용한다.

예
```
<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="px(픽셀) 크기 설정" alt="RubberDuck"></img>
```

<img src="http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>
<img src="http://cfile6.uf.tistory.com/image/2426E646543C9B4532C7B0" width="40%" height="30%" title="%(비율) 크기 설정" alt="RubberDuck"></img>

:star:width는 좌우 길이, height는 상하 길이!

## 2.9. 줄바꿈
```
3칸 이상 띄어쓰기를 하면 줄이 바뀐다.
역슬래시(\) 사용도 가능!
```