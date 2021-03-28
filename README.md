# Python GUI - Shortcut Launcher

## 목표 및 목적

자주 사용하는 프로그램에 접근하는 시간을 줄이기 위한 GUI 기반의 단축키 실행 프로그램을 개발한다.

### 문제 분석
  
* 최종 목적 : 단축키 실행 프로그램인 Shortcut Launcher를 완성한다.

    * 상위 목적 : GUI에 버튼을 구현한다.
    
      * 하위목적 : 크기를 조정하여 메인 윈도우 창을 만든다.
      * 하위목적 : 2행 4열의 그리드 버튼을 만든다.  
      
    * 상위 목적 : GUI에 버튼을 눌렀을 때, 응용프로그램을 실행시킨다.
    
      * 하위목적 : 단축키로 실행 시킬 프로그램을 설정한다.
      * 하위목적 : 실행시킬 프로그램의 명령어를 설정한다.
      * 하위목적 : 버튼에 실행시킬 프로그램의 UI 이미지를 삽입한다.
      * 하위목적 : 마우스로 UI 이미지를 클릭했을 때 특정 명령어를 실행하도록 한다.
       
## 개발 사양

### 하드웨어
* CPU : 2 GHz 쿼드 코어 Intel Core i5
* RAM : 32GB 3733 MHz LPDDR4X
* HDD/SSD : 1TB
* GPU : Intel Iris Plus Graphics 1536 MB

### 소프트웨어
* OS : macOS Big Sur v11.2.3(20D91)
* 개발 스택 : Tkinter 
* 개발 프로그램 : Visual Studio Code
* 개발 언어 : Python v3.8.5

### 코드룰

```
    # 변수명
    
    test_variable = 13

    # 클래스명
    
    class Test_class:
    
        def __init__(self):
        
            # 프로퍼티명
            
            self.test_property = 41

        # 메소드명
        
        def test_method(self):
            print(self.test_property)
    
    if __name__ == "__main__":
        test_variable = Test_class(43)
        test_variable.test_method()
```

* 개발 스택 선정이유: Tkinter는 GUI에 대한 표준 Python 인터페이스이기 때문이다.
