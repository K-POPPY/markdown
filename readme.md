# 제목(Header)

# 제목1
## 재목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

<br />

# 문장(Paragraph)

대한민국은 통일을 지향하며, 자유민주적 기본질서에 입각한 
평화적 통일 정책을 수립하고 이를 추진한다.  

<br />

# 줄바꿈(Line Breaks)

대한민국의 경제질서는 개인과 기업의 경제상의 자유와 창의를 존중함을 기본으로 한다.  
국무총리는 국무위원의 해임을 대통령에게 건의할 수 있다.  
국군은 국가의 안전보장과 국토방위의 신성한 의무를 수행함을 사명으로 하며<br />그 정치적 중립성은 준수된다. 형사피고인은 유죄의 판결이 확정될 때까지는 무죄로 추정된다.

<br />

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>  

<br />

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<br />

# 링크(Links)

<a href="https://google.com">GOOGLE</a>  
[GOOGLE](https://google.com)

<a href="https://google.com" title="NAVER로 이동!">NAVER</a>  
[NAVER](https://google.com "NAVER로 이동!")  
<a href="https://google.com" title="NAVER로 이동!" target="_blank">새창으로 NAVER열기</a>  

<br />

# 이미지(Image)

![]()  
![POPPY](https://res.cloudinary.com/dygttvrql/image/upload/v1673082699/portfolio_img/favicon/logo1_70_ed6nes.png)    

[![POPPY](https://res.cloudinary.com/dygttvrql/image/upload/v1673082699/portfolio_img/favicon/logo1_70_ed6nes.png)](http://frontyend.dothome.co.kr)  
링크있는  q이미지

<br />

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)
>> 중첩1
>>> 중첩2
>>>> 중첩3
>>>>> 중첩4
>>>>>> 중첩5
>>>>>>> 중첩6
>>>>>>>> 중첩7
>>>>>>>>> 중첩8
>>>>>>>>>> 중첩9
>>>>>>>>>>> 중첩10

<br />

# 인라인(inline) 코드 강조
CSS에서 `background` 혹은 `background-image`속성으로 요소에 배경이미지를 삽입할 수 있습니다.

<br />

# 블록(block) 코드 강조

```html
<a href="https://google.com">GOOGLE</a> 
```

```css
body {
  color: #333;
  font-size: 16px;
  font-weight: 400;
  line-height: 1.4;
  font-family: 'Nanum Gothic', sans-serif;
}
```

```javascript
// Copyrigth 년도 자동 업데이트
const thisYear = document.querySelector('.this-year');
thisYear.textContent = new Date().getFullYear(); // 올해년도
``` 

```bash
$ git commit -m 'Study Markdown'
``` 

```plaintext
대한민국은 통일을 지향하며, 자유민주적 기본질서에 입각한 
평화적 통일 정책을 수립하고 이를 추진한다.  
```

<br />

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

<br />

# 원시 HTML(Raw HTML)

<span style="text-decoration: underline;">대한민국은</span> 통일을 지향하며, <u>자유민주적</u> 기본질서에 입각한 <br /> 
평화적 통일 정책을 수립하고 이를 추진한다.  

<a href="https://google.com" title="NAVER로 이동!" target="_blank">taget="_blank" NAVER</a>  

<img width="150" src="https://res.cloudinary.com/dygttvrql/image/upload/v1673082699/portfolio_img/favicon/logo1_70_ed6nes.png" alt="POPPY" />

# 수평선(Horizontal Rule)
---
***
___   