# Repository 개요

UML 실전에서는 이것만 쓴다 (영제: UML for Java Programmers)의 예제들 중\
Good Case에 해당하는 예시들을 _PlantUML_ 코드로 작성하고, Preview Image를 업로드

# PlantUML

UML Diagram들을 Code로 그릴 수 있도록 하는 오픈소스 프로젝트.

**[PlantUML official website](https://plantuml.com/ko/)**

## PlantUML 예시 - Class Diagram

---

### Code

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

![image](https://user-images.githubusercontent.com/12408453/182754815-88dddc94-46b5-4e65-bbd8-e3452705b2c0.png)

## VSCode Extensions for PlantUML

---

위 Code와 Preview는 VSCode에서 작성 및 테스트 되었다.

1. [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) : Code Formatting 등 문법 관련 기능 및 Preview 기능 제공\
   TODO: PlantUML Extension 자체 Preview 기능 활성화 시키기
2. [PlantUML Previewer](https://marketplace.visualstudio.com/items?itemName=Mebrahtom.plantumlpreviewer) : **Ctrl+P** 입력 시 우측에 분할 화면으로 Preview Image 생성
3. [Yog PlantUML Highlight](https://marketplace.visualstudio.com/items?itemName=Yog.yog-plantuml-highlight) : PlantUML 문법을 Highlight 해주는 Extension
