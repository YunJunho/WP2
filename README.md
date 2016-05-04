##7일차 (5/3)
github 사용 방법을 배움

add, commit, push, pull, checkout, merge를 배웠음

github의 첫 수업인 만큼 add, commit, push을 강조
_ _ _
##8일차 (5/4)
**- 자료형** 
* Number
* String > 더할 수도 있고 곱합 수도 있다.
  - {name}.format(name=" ")
* List	> [ ]
	- .append(" ") 추가
	- .pop() 삭제
* Tuple	> 리스트와 같지만 엘리먼트 값이 변경 될 수 없다.
* Dict	> key-value의 쌍을 모아놓은 것
* set	집합은 숫자가 없고, Uniq, 중복제거시 사용 된다.
* Boolean

**- 제어문** 
* if, elif, else, while, for 
  -while문 보다 for문이 자주 사용된다
  -for문으로 별을 찍어보았다.(비슷한 유형의 과제)

**- 입력과 출력** 
* 입력과 출력은 Python 내장 함수를 이용해서 할 수 있다.
	- Python의 버전마다 다르게 동작
	| |Python 2|Python3 |
	|---|-----------|--------|
    |입력|raw_input()|input()|
    |출력| print " "|print (" ")| 
      print " " -> print를 함수가 아니라 출력하는 기능을 가진 것으로만
      
 	print(" ") -> print가 함수
		 
- 입력 - 파일
 * f = open("../animals.txt", "r") 
 	* mode
 		- "w", 쓰기
 		- "r", 읽기
         - "a" (append)  
  * f = open("./animals.txt", "w") close와 함께 세트로 움직여야 한다. 
	* f.write("hello world")
	 
      f.close()

   * 하지만 close를 잊어 버릴 수도 있기 때문에 
		
        with open("./animals.txt", "w") as f(f라고 명명) :
		
        f.write("Hello world")
		
        with open을 쓰면 함께 쓰면 자동으로 close가 된다.
  * 폴더 위치 명령어
   *  ./ => 현재폴더
   * ../ => 상위폴더
   *  ./test.txt => 현재 폴더에 있는 test.txt
   * ../test.txt => 상위 폴더에 있는 test.txt
   * ../../test.txt => 상위 폴더의 상위 폴더에 있는 test.txt

 * 함수의 차이
   * f.read()   -> 결과 값이 전체 데이터가 들어온다.
   * f.readline()
   * f.readlines() - > 라인별로 구분이 되서 리스트 형태로 들어간다.
		
		

**- 함수** 
 - 함수를 사용하는 이유는 작업 자동화를 위해서 입니다.
 - 우리가 반복적으로 사용할 어떤 특정 기능들에 대해서 - > 재사용 가능한 코드 덩어리
 - def funtion () :
	"""  
    
	함수 설명 
    
    """
			   

# wp2
