# kislov.github.io

[Представление модели](https://github.com/mkisslov/kislov.github.io/blob/master/6_%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D0%BE%D0%B2.png)

[Диаграмма классов](https://github.com/mkisslov/kislov.github.io/blob/master/%D0%BA%D0%BE%D1%80%D1%82%D0%B8%D0%BD%D0%BA%D0%B0.png)

[Диаграмма прецедентов]
(https://github.com/mkisslov/kislov.github.io/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0_%D0%BF%D1%80%D0%B5%D1%82.png)
@startuml
skinparam class {
	BackgroundColor White
	ArrowColor Black
	BorderColor Black
}
class "P?" as P {
 M?
O? A? (I?, C?)
}
hide circle
@enduml
