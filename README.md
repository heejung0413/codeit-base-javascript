<h1> 프로그래밍 시작하기 in Javascript </h1>
- javascipt언어의 기본 용어인 parameter, return, function 을 주제로 학습하였습니다. </br>
- <a href="https://www.codeit.kr/topics/intro-to-web-publishing">코드잇 교육컨텐츠</a> 를 보고 제작하였습니다. </br> 

## 수료증 ✨

<p align="center">
<img src="/main/certificates.jpg" style="width:300px">
</p> 

## 요약정리 🔍

<h3> parameter(매개변수) </h3>
- console.log(값)으로 결과값 호출하기

</br>
    
    // 함수 선언
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

<h3>여러 파라메타 호출하기 </h3>

</br>

    //예제1
    function prinSum(num1, num2){
        console.log(num1, num2);
    }

    printSum(10,5);

    //예제 2
    function getTwice(number){
        return number*2;
    }   

    console.log(getTwice(5));

    //심화 예제 3
    function getTwice(number){
        return number*2;
    };

    let x = getTwice(5);
    let y = getTwice(2);

    console.log(x*y);

- 너무 많은 파라메타를 사용하지는 말 것!
</br>

<h3>실습</h3>

- BMI 지수 구하기

</br>

    function bmiCalculator(name, weight, height){
    console.log(name + '님의 체질량지수는 ' +weight/(height*height/10000)+ '입니다.');
    }

    // 테스트 코드
    bmiCalculator('홀쭉이', 43.52, 160);
    bmiCalculator('코린이', 61.25, 175);
    bmiCalculator('통통이', 77.76, 180);


<h3> 함수(function) </h3>

- 파라미터라는 인풋을 넣어, return이라는 아웃풋으로 반환한다.
- 여기서 return이란?

</br>

    function getTwo(){
        return 2;
    }

    console.log(getTwo());

</br>

<h3>내 컴퓨터 용량 확인하기 </h3>
</br>

     // 여기에 코드를 작성하세요
    function teraToGiga(volume) {
    console.log(volume + 'TB는');
    console.log(volume * 1024 + 'GB 입니다.');
    }

    function teraToMega(volume) {
    console.log(volume + 'TB는');
    console.log(volume * 1024 * 1024 + 'MB 입니다.');
    }

    // TB -> GB 테스트
    teraToGiga(2);
    // TB -> MB 테스트
    teraToMega(2);
 
