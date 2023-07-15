def calculator():
    num1 = float(input("첫 번째 숫자를 입력하세요: "))
    operator = input("연산자를 입력하세요 (+, -, *, /): ")
    num2 = float(input("두 번째 숫자를 입력하세요: "))

    if operator == "+":
        result = num1 + num2
    elif operator == "-":
        result = num1 - num2
    elif operator == "*":
        result = num1 * num2
    elif operator == "/":
        result = num1 / num2
    else:
        print("올바른 연산자를 입력하세요.")
        return

    print("결과:", result)

calculator()
