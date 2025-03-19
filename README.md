# 코딩셰프의 플러터 맛집 책 정리

## 환경세팅

- 자바 설치하기
- Flutter SDK 내려받기
- 안드로이드 스튜디오 설치하기

## 1. 자바 설치하기

자바 다운로드는 여기에서 가능합니다: [JDK 11 다운로드](https://jdk.java.net/java-se-ri/11-MR2)

windows환경에서의 세팅이기 때문에 windows버전으로 다운받아야 합니다. 

다운을 받으면 C:\dev\jdk-11.0.0.1 해당 경로에 압축을 풀어줍시다. 

이후 환경변수 설정을 위해 시스템 환경 변수 편집 으로 들어갑니다. 

1. 환경번수 클릭하기
2. 시스템 변수 새로 만들기 클릭
- 변수이름 : JAVA_HOME
- 변수 값 : C:\dev\jdk-11.0.0
3. 시스템 변수의 Path 설정하기 
- Path 선택 후 편집 
- 새로만들기 %JAVA_HOME%\bin
4. Cmd(명령 프롬프트) 창에서 자바가 제대로 설치 되었는지 확인해봅니다.

```jsx
java --version
```

## 2. Flutter SDK 내려받기

플러터는 [flutter.dev](https://flutter.dev) 에서 설치 가능합니다.

해당 사이트에서 'Get Started' 버튼을 클릭한 후 Windows 운영체제를 선택하여 SDK를 다운로드 받습니다.

다운로드 받은 SDK를 C:\flutter 경로에 압축을 풀어줍니다.

이후 환경변수 설정을 위해 시스템 환경 변수 편집으로 들어갑니다.

1. 시스템 변수의 Path 설정하기
    - Path 선택 후 편집
    - 새로만들기 C:\flutter\bin

설치가 잘 되었는지 확인하기 위해 CMD 창에서 다음 명령어를 실행합니다:

```jsx
flutter doctor
```

이 명령어를 실행하면 Flutter 개발에 필요한 모든 요소들이 제대로 설치되어 있는지 확인할 수 있습니다.

## 3. 안드로이드 스튜디오 설치하기

안드로이드 스튜디오는 [안드로이드 개발자 사이트](https://developer.android.com/studio?hl=ko)에서 설치가 가능합니다.

운영체제에 맞는 버전을 다운로드 받아 설치를 진행합니다.

1. 설치 프로그램을 실행하고 'Next'를 클릭하여 기본 설정으로 진행합니다.
2. 설치가 완료되면 Android Studio를 실행합니다.
3. 첫 실행 시 Android SDK를 설치할 것인지 묻는 메시지가 나타나면 'Yes'를 선택합니다.

안드로이드 스튜디오 설치가 완료되면, Flutter와 Dart 개발을 위한 플러그인을 설치해야 합니다:

- Android Studio에서 File > Settings > Plugins로 이동
- Marketplace에서 'Flutter' 검색 후 설치
- 같은 방법으로 'Dart' 플러그인도 검색하여 설치
- 두 플러그인 설치가 완료되면 IDE 재시작

이제 Flutter와 Dart를 사용한 개발을 시작할 수 있습니다.
