## BigDecimal in Java

<br>

***BigDecimal?*** 

> ***BigDecimal* represents an immutable arbitrary-precision decimal number.** It consists of two parts:
>
> - Unscaled value - an arbitrary precision integer
> - scale - a 32-bit integer representing the number of digits to the right of the decimal point 
>
> For example, the BigDecimal 3.14 has the unscaled value of 314 and the scale of 2.
>
> **We use *BigDecimal* for high-precision arithmetic. We also use it for calculations requiring control over scale and rounding off behavior.** One such example is calculations involving financial transactions.  

<br>

- 오차가 없는 실수의 표현을 위해 정의된 클래스  

- double을 이용하는 경우, 근사치를 이용해 계산하기 때문에 오차가 발생한다.  


#### References
[BigDecimal and BigInteger in Java](https://www.baeldung.com/java-bigdecimal-biginteger)  
[Java, BigDecimal 사용법 정리](https://jsonobject.tistory.com/466)  
[\[JAVA\]BigDecimal](https://gomoveyongs.tistory.com/62)  
[\[JAVA\] 무한대 정수 BigInteger 사용하기](https://elena90.tistory.com/entry/JAVA-%EB%AC%B4%ED%95%9C%EB%8C%80-%EC%A0%95%EC%88%98-BigInteger-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)  
[\[java\]BigDecimal 연산과 비교](https://daily-study.tistory.com/4)  

