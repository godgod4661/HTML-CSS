# # 페이지 번호

![스크린샷(188)](https://user-images.githubusercontent.com/79892837/141976959-91c792f8-1c8d-4f99-802d-2119110b77f3.png)

- .page-link.page-link--current : 클래스가 두개면 Selector Specificity(0,2,0) 처럼 가운데 숫자가 커진다. 커질수록 css 속성이 적용됨. 만약 어떤 클래스가 (0,1,0)이면 (0,2,0)보다 작아서 css속성이 적용 안됨. 하지만 만약 둘다 (0,2,0)으로 같다면 밑에 적어준 속성이 적용된다.

- .btn:hover .btn-icon {
  stroke: white;
  }  
   -> svg태그에 사용되는 css속성(stroke:선 색상/값)</br>
  -> 버튼안에있는 아이콘의 색상을 바꿀때 .btn-icon:hover로 하면 버튼말고 아이콘을 정확히 hover해야지 색이 바뀌므로 .btn:hover .btn-icon으로 설정해준다.
