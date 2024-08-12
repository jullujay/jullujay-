# jullujay-# Google Colab에서 실행될 코드
# 사용자로부터 숫자를 입력받습니다.
number_str = input("숫자를 입력하세요: ")

# 입력된 값을 정수로 변환합니다.
try:
    number = int(number_str)
    
    # 짝수인지 홀수인지 판별합니다.
    if number % 2 == 0:
        print(f"{number}는 짝수입니다.")
    else:
        print(f"{number}는 홀수입니다.")
except ValueError:
    # 숫자로 변환할 수 없는 입력에 대해 에러 메시지를 출력합니다.
    print("유효하지 않은 입력입니다. 숫자를 입력해주세요.")
