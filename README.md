# CustomWidget
View:화면에 보이는 모든 요소의 최상위 클래스입니다. 화면에 무엇인가를 그리기 위해서는 View클래스가 상속받아져 있어야 합니다
onDraw()메서드:View클래스가 화면에 텍스트를 출력하거나 그림을 그릴 때 호출하는 메서드입니다.
Canvas:onDraw()메서드를 통해 전달되는 그리기 도구입니다. drawText(),drawCircle()등의 메서드를 사용하여 화면에 그릴 수 있습니다
Paint:화면에 그려지는 요소들의 색상,스타일,굵기 정보 등을 정의하는 클래스입니다.
attrs.xml:내가 만든 위젯에 새로운 속성을 정의할 때 사용되는 리소스 파일입니다.
custom:attrs.xml에 정의한 새로운 속성을 custom이라는 Prefix로 레이아웃에서 사용할 수 있습니다
출처:이것이 안드로이드다 with 코틀린,고돈호 지음,한빛미디어
