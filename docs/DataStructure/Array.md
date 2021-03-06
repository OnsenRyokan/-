# 배열 (Array)
*written by sohyeon, hyemin 💡*

<br>

## 1. 배열이란?  

같은 자료형의 구성요소가 직선모양으로 연속하여 줄지어 있는 단순한 자료구조 이다.  

### ex) 사용 예시

```Java
// 두가지 선언 방법이 있음
int[] a;
int a[];

// 배열 생성
a = new int[5];

a[1] = 37;
a[2] = 20;
a[3] = 11;
a[4] = 1;

for(int i=0; i<a.length; i++)
    System.out.println("a["+i+"]="+a[i]);
```

### 출력 결과
```
a[0] = 0 
a[1] = 37
a[2] = 20
a[3] = 11
a[4] = 1
```
`new int[5]`로 배열 본체를 생성하고 변수 a가 배열 본체를 참조한다.

출력 결과를 보면 a[0]에 값을 대입하지 않았지만 자동으로 0 값이 대입되어 있는 것을 볼 수있다.  
배열이 생성되면 자동으로 각 요소들이 0으로 초기화 된다.  

또한 배열 a의 자료형과 a[i] (i는 요소의 index값)의 자료형은 다르다는 것을 알아두자.
배열 a는 int[5]형 자료형, 총 5개의 int형 저장공간을 차지하는 것이고
a[i]는 int형 자료형을 갖는다.

## 2. 메소드

* 배열 변수 이름.length : 길이를 구한다.

* 배열 이름.clone() : 배열을 복제한다.

* maxOf(배열 이름) : 배열 구성요소 중 최대 값을 구한다.


