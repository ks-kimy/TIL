```python


number_of_people = 0

def increase_user():
    global number_of_people
    number_of_people += 1



def create_user(name,age,address):
    increase_user()
    user_info = {
        'name': name,
        'age': age,
        'address': address
    }
    print(f'{user_info["name"]}님 환영합니다!')
    return user_info # return 까먹지 말자

name = ['김시습', '허균', '남영로', '임제', '박지원']
age = [20, 16, 52, 36, 60]
address = ['서울', '강릉', '조선', '나주', '한성부']

result = list(map(create_user, name, age, address))

'''
map 함수는 map(함수, 인자)
이때 함수는 ()표현 없이 대입.
이 때 map은 기능적으로 sequence 형태의 iterable 인자들을 하나씩 대입
이 때 create_user 는 3개의 매개변수가 필요했기 때문에 3개의 sequence data 를 넣은 것
'''
print(result)
```