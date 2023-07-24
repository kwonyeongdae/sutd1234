# 마크다운-간단-문법

# 제목 표시하기
## 공백이후는 h1과 같다 (타이틀이 됨)
### 샵갯수만큼 h1,h2,h3가 가능함
총 h6까지 가능함
줄바꿈은 공백 2개를 줘야함 엔터는 공백1개로 인식해서 띄어쓰기가 됨  

Mark
===
down
---

# 수평선 표시하기
---
***

# 목록 표시하기  
## 순서있는경우
(ol)
1. 순서는
2. 이런식으로
3. 해주면됨
  
## 순서없는 경우
(ul)  
- 수학
- 영어
- 과학

## 들여쓰기 표현  
ㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁㅁ  

    ㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠㅠ  

    ㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊㅊ  

## 코드 블럭
```esc키 아래의 자판임

@Controller 
@RequestMapping("/board")
@SessionAttributes("userid")
public class BoardController {
	@Autowired
	HttpServletRequest request; 

	@Autowired
	BoardSVC svc;
	@GetMapping("/")//get방식 요청
	public String index()
	{
		return "board/boardIndex";
		
	}
```

## 기본링크보기
[구글바로가기](http://google.com)

## 아이디를 사용하여 보여지는 문자열 표시하기
[구굴 바로가기][google]  
[google]: http://google.com "Google 사이트로 이동합니다"

## 문서 내부 참조  
[문서의 처음으로 이동](#마크다운-간단-문법)

## 강조하기
Hello *world*  
_Hello_ World  
Hello **World**  
__Hello__ World  
~~Hello~~ World

## 이미지 표현방법
<img ser="">
