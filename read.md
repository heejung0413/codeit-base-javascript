<h2>변수 정하기 </h2>

- 변수: 값을 정하는 것

</br>

    let espressoPrice = 3000;
    let latterPrice=4300;
    let machPrice = 4800;

    console.log(espressoPrise * 2);

<h3> 규칙 </h3>

- 대문자, 소문자 구별하기
- 예약어 사용 X ex) if, for, let 같은 변수는 안됨
- 의미 없는 이름 좋지 않음 

</br> 

    let a, b, c;

- 너무 추상적인 이름도 X

</br>

    let name;

</br>

    let bad_variable_name; //비추천 방식
    let goodVariablename;

<h3> 실습을 해보자</h3>

</br>

    // 코드를 작성해 주세요.
    let espresso = 10;
    let milk = 170;
    let chocolateSyrup = 50;
    let whippedCream = 60;

    // 메뉴별 칼로리
    console.log(espresso); // 에스프레소 칼로리
    console.log(espresso + milk); // 라떼 칼로리
    console.log(espresso + chocolateSyrup + milk); // 모카 칼로리
    console.log(espresso + chocolateSyrup + milk + whippedCream); // 모카 (휘핑 추가) 칼로리

    실습 결과
    10
    180
    230
    290

<h2>함수 </h2>

</br> 

    function 함수 이름() {
        명령;
        명령;
    }

 <h3> 예시
 </br>

    함수 선언
    function greetings() {
    console.log('Hi');
    console.log('안녕');
    console.log('こんにちは');
    console.log('你好');
    console.log('Guten Tag');
    console.log('Bonjour');
    console.log('Buongiorno');
    };

    //함수 호출
    greetings();
