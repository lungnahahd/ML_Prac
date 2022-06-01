# Tensorflow_Prac
----------------

## Google Colab 세션 유지하기
* F12를 눌러서 개발자 모드로 이동
* 이동 후에 Console 탭에 아래의 JS 코드 입력
```
function ClickConnect(){
    console.log("코랩 연결 끊김 방지"); 
    document.querySelector("colab-toolbar-button#connect").click() 
}
setInterval(ClickConnect, 60 * 1000)
```
