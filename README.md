# 스프링부트
## IOC/DI 와 관련된 Annotation
```sh
- @Component : 1개의 class 단위로 등록 할 때 사용
- @Bean : 1개의 외부 library 로부터 생성한 객체를 등록 시 사용
- @AutoWired : DI 를 위한 곳에 사용
- @Qualifier : @AutoWired 사용시 bean이 2개 이상 일때 명시적 사용
- @Resource : @AutoWired + @Qualifier 의 개념으로 이해
```

## AOP 와 관련된 Annotation
```sh
- @Aspect : AOP 적용시 사용
- @Before : AOP 메소드 이전 호출 지정
- @After : AOP 메소드 호출 이후 지정 예외 발생 포함
- @Around : AOP 이전/이후 모두 포함 예외 발생 포함
- @AfterReturning : AOP 메소드의 호출이 정상일 때 실행
- @AfterThrowing : AOP 시 해당 메소드가 예외 발생시 지정
```
## 실무에서 자주 쓰는 AOP
- 캐쉬처리, 로깅처리, 함수 실행시간 분석 처리 등등...
