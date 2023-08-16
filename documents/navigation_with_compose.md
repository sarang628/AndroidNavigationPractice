# [Navigating with Compose](https://developer.android.com/jetpack/compose/navigation)
Jetpack 컴포즈도 내비게이션 컴포넌트를 이용 할 수 있습니다.

## [Setup](https://developer.android.com/jetpack/compose/navigation#setup)
```
dependencies {
    def nav_version = "2.7.0"

    implementation "androidx.navigation:navigation-compose:$nav_version"
}
```

## [Getting started](https://developer.android.com/jetpack/compose/navigation#getting-started)
NavController은 내비게이션 컴포넌트의 중심 API<br>
이 API는 stateful 하며 백스택을 추적.<br>
<br>
컴포즈에서는 rememberNavController() 함수를 호출하여 생성
```
val navController = rememberNavController()
```

## [Creating a NavHost](https://developer.android.com/jetpack/compose/navigation#create-navhost)
NavController은 하나의 NavHost와 반드시 관련되어야 함.
```
NavHost(navController = navController, startDestination = "profile") {
    composable("profile") { Profile(/*...*/) }
    composable("friendslist") { FriendsList(/*...*/) }
    /*...*/
}
```