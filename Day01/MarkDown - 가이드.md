# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
<br><br><br><br>

제목 1
======

제목 2
------
<br><br><br><br>

# 줄바꿈

`<br>`



# 폰트 스타일

*이탤릭체* 
_이탤릭체_

**강조**
__강조__

~~취소선~~
<u>밑줄</u>
<br><br><br><br>

# 리스트

1. 순서가 필요한 목록
1. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록(서브) 
   -  순서가 필요하지 않은 목록(서브) 
2. 순서가 필요한 목록
   1. 순서가 필요한 목록(서브)
   2. 순서가 필요한 목록(서브)
   
3. 순서가 필요한 목록

- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
<br><br><br><br>

# 링크

[GOOGLE](https://google.com)


[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

[상대적 참조](../users/login)

[Dribbble][Dribbble link]

[GitHub][1]

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"
<br><br><br><br>



# 이미지
![대체 텍스트](./aloha.png "툴팁 : aloha.png")

![참조 이미지][logo]

[logo]: http://alohasoft.kr/img/emoji/star.gif
 "툴팁 : aloha.png"

##### 이미지에 링크
[![Vue](./aloha.png)](http://alohasoft.kr)


 <br><br><br><br>




# 인라인 코드 강조

`background`혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<br><br><br><br>



# 코드 블록 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting. 
But let's throw in a tag.
```

<br><br><br><br><br>



# 테이블

 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |



<br><br><br><br><br>



# 인용문

인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3


<br><br><br><br><br>


# Raw HTML

<u>마크다운에서 지원하지 않는 기능</u>을 사용할 때 유용하며 대부분 잘 동작합니다.

<img width="150" src="http://www.gstatic.com/webp/gallery/4.jpg" alt="Prunus" title="A Wild Cherry (Prunus avium) in flower">

![Prunus](http://www.gstatic.com/webp/gallery/4.jpg)



<br><br><br><br>


# 수평선


---
(Hyphens)

***
(Asterisks)

___
(Underscores)



<br><br><br><br>



