## 즉시 실행 함수
 (function 함수명 () {})();  
 (function 함수명 () {} ());  


 ## DOM

 documaent 객체 

 html 문서 탐색


  한개씩밖에 찾아준다.

  css는 알아서 다 적용되었지만 스크립트에서는 아니다.
  lists.forEach(element => {
      
    });

   ['list','list','list','list'].foreEach(element => {

      실행문
   })

    첫번째 list를 함수로 집어넣어서 실행문 실행
    그다음 list를 함수로 집어넣어서 실행문 실행 ....
  element는 내가 지은 이름이지만 보통 제어하고자하는 태그의 이름과 같은 이름으로 쓴다?

   const imgs = [
        ' https://placehold.co/200x200/9B7EBD/fff?text=PJ4',
        ' https://placehold.co/200x200/9B7EBD/fff?text=PJ4',
        ' https://placehold.co/200x200/9B7EBD/fff?text=PJ4',
        ' https://placehold.co/200x200/9B7EBD/fff?text=PJ4'

      ];
  imgs[idx];  imgs 객체의 인덱스번호의 내용을 가져올 때 이렇게 쓴다.