## Stream in Java

<br>

##### 's'가 포함된 문자열 카운트
```java
List<String> names = Arrays.asList("summer", "spring", "autumn", "winter");

// 기존 코드
long count = 0;
for (String name : names) {
    if (name.contains("o")) {
        count++;
    } 
}

// stream
count = 0;
count = names.stream().filter(x ->x.contains("o")).count();
```

##### Stream 사용법과 주의사항
- Stream 구조
    1. Stream 생성
    2. 중개 연산
    3. 최종 연산  
> Collection과 같은 객체 집합.스트림생성().중개연산().최종연산();


##### Stream 생성
- Stream은 주로 Collection, Arrays에서 사용  
```java
List<String> names = Arrays.asList("summer", "spring");
names.stream() //Collection에서 스트림 생성

Double[] dArray = {3.1, 3.2, 3.3};
Arrays.stream(dArray); // 배열로 스트림 생성

Stream<Integer> str = Stream.of(1,2); // 직접 생성
```





