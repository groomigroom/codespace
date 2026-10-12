맥(macOS)에서 Visual Studio Code(VS Code)를 앱뿐만 아니라 설정, 캐시, 확장 프로그램 등의 잔여 파일까지 완전히 삭제하려면, 앱을 지운 뒤 관련 라이브러리 및 숨김 폴더를 함께 삭제해야 합니다. [1, 2] 
------------------------------
## 1단계: VS Code 앱 삭제

   1. Finder를 열고 응용 프로그램(Applications) 폴더로 이동합니다.
   2. Visual Studio Code.app 파일을 찾아 휴지통으로 이동시킵니다.
   3. 휴지통을 비웁니다. [1, 3, 4] 

------------------------------
## 2단계: 관련 잔여 파일 및 폴더 삭제 (터미널 이용)
터미널(Terminal)을 열고 아래 명령어들을 복사해서 실행하면 설정, 확장 프로그램, 캐시 파일이 모두 지워집니다. [1, 5] 

* 설정 및 애플리케이션 데이터 삭제

rm -rf ~/Library/Application\ Support/Code

* 확장 프로그램(Extensions) 폴더 삭제

rm -rf ~/.vscode

* 캐시 파일 삭제

rm -rf ~/Library/Caches/com.microsoft.VSCode
rm -rf ~/Library/Caches/com.microsoft.VSCode.ShipIt

* 환경설정(.plist) 파일 삭제

rm -rf ~/Library/Preferences/com.microsoft.VSCode.helper.plist
rm -rf ~/Library/Preferences/com.microsoft.VSCode.plist

* 저장된 앱 상태 삭제

rm -rf ~/Library/Saved\ Application\ State/com.microsoft.VSCode.savedState


------------------------------
VS Code를 완전히 삭제한 후 새로 다운로드하여 재설치하는 과정이나, Homebrew를 이용한 설치 방법이 필요하시면 말씀해 주세요. [6] 

[1] [https://dataengineerstudy.tistory.com](https://dataengineerstudy.tistory.com/272)
[2] [https://velog.io](https://velog.io/@biigpiie/%EB%A7%A5%EC%97%90%EC%84%9C-Visual-Studio-Code-%EC%99%84%EC%A0%84-%EC%82%AD%EC%A0%9C-%ED%9B%84-%EC%84%A4%EC%B9%98%ED%95%98%EA%B8%B0)
[3] [https://ds31x.tistory.com](https://ds31x.tistory.com/670)
[4] [https://www.youtube.com](https://www.youtube.com/watch?v=osJXMfD7wm8)
[5] [https://mulkkog.tistory.com](https://mulkkog.tistory.com/86)
[6] [https://www.youtube.com](https://www.youtube.com/watch?v=Hf4kcNN91-k&t=251)
