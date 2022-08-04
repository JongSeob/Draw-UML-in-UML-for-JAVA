# Repository 개요

UML 실전에서는 이것만 쓴다 (영제: UML for Java Programmers)의 예제들 중\
Good Case에 해당하는 예시들을 _PlantUML_ 코드로 작성하고, Preview Image를 업로드

# PlantUML

UML Diagram들을 Code로 그릴 수 있도록 하는 오픈소스 프로젝트.

**[PlantUML official website](https://plantuml.com/ko/)**

## PlantUML 예시 - Class Diagram

### Code

---

```
@startuml
class a {
}
class b {
}
a <|- b
@enduml
```

### Preview

---

1. With PlantUML Extension\
![ISA](https://user-images.githubusercontent.com/12408453/182765742-d56c6643-6027-4a3d-8e92-59410b5236ca.png)

2. With PlantUML Previewer Extension\
![image](https://user-images.githubusercontent.com/12408453/182754815-88dddc94-46b5-4e65-bbd8-e3452705b2c0.png)


## VSCode Extensions for PlantUML

위 Code와 Preview는 VSCode에서 작성 및 테스트 되었다.

1. [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) : Code Formatting 등 문법 관련 기능, **Alt+D** 입력 시 Preview 기능 제공\
2. [Yog PlantUML Highlight](https://marketplace.visualstudio.com/items?itemName=Yog.yog-plantuml-highlight) : PlantUML 문법을 Highlight 해주는 Extension
3. [PlantUML Previewer (optional)](https://marketplace.visualstudio.com/items?itemName=Mebrahtom.plantumlpreviewer) : **Ctrl+P** 입력 시 우측에 분할 화면으로 Preview Image 생성

### PlantUML vs PlantUML Previewer

| 비교 항목          | PlantUML                                                                                  | PlantUML Previewer |
| ------------------ | ----------------------------------------------------------------------------------------- | ------------------ |
| requirement        | [Java](https://www.java.com/en/download/), [graphviz](https://www.graphviz.org/download/) | X                  |
| Zoom & Scroll      | O                                                                                         | X                  |
| Auto Update        | O                                                                                         | O                  |
| Multi Page Diagram | O                                                                                         | X                  |
| Diagram Download   | O                                                                                         | X                  |

추가 install 없이 바로 Preview를 보고 싶다면 _PlatUML Previewer_ 를,\
고해상도에 interaction 되는 Preview를 이용하고 싶다면 _PlantUML_ 을 사용을 사용.

_PlantUML_ 은 추가적인 설정 없이 Java, graphviz만 PC에 설치하면 바로 동작.
