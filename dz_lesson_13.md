//Домашнее задание переменные и типы
let count: UInt = 1
let apples = count % 10 == 1 ? "яблоко" : count % 10 < 5 ? "яблока" : "яблок"


let result = "В корзине \(count) \(apples)"
print(result)
