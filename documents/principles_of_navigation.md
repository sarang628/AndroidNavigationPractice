# [Principles of navigation](https://developer.android.com/guide/navigation/principles)
내비게이션은 다른 화면에 경로를 찾아가는 앱에 주요한 기능<br>
기본적은 이론을 학습하여 직관적은 앱 경험을 제공하는 방법을 배우기<br>
네비게이션 컴포넌트는 이러한 기본적은 이론들을 고려하여 만들어짐

## [Fixed start destination](https://developer.android.com/guide/navigation/principles#fixed_start_destination)
모든앱은 고정된 시작점이 있음.<br>
이 시작점은 사용자가 앱을 빠져나가기전에 마지막 화면이기도 함.

## [Navigation state is represented as a stack of destinations](https://developer.android.com/guide/navigation/principles#navigation_state_is_represented_as_a_stack_of_destinations)
앱을 시작 했을 때 새로운 테스크가 생성 됨<br>
화면 내비게이션은 스택 개념을 사용하면 유용함<br>
화면에 진입 할 떄마다 스택에 쌓이게 됨.<br>
앱의 시작지점음 스택의 바닥에 놓이기 됨.<br>
<br>


