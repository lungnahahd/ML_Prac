# Tensorflow_Prac
----------------

## Google Colab 세션 유지하기
* F12를 눌러서 개발자 모드로 이동
* 이동 후에 Console 탭에 아래의 JS 코드 입력
```
    var buttons = document.querySelectorAll("colab-dialog.yes-no-dialog paper-button#cancel"); 
    buttons.forEach(function(btn) { 
        btn.click(); 
    }); 
    console.log("1분마다 자동 재연결"); 
    document.querySelector("colab-toolbar-button#connect").click(); 
} 
setInterval(ClickConnect,1000*60);
```
