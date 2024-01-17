```python
unsorted_list = ['하', '교', '캅', '의', '지', '가']
sorted(unsorted_list)
print(unsorted_list)

li = ['하', '교', '캅', '의', '지', '가']
li.sort()
print(li)
```
---
sorted 는 원본이 아닌 새로운 객체를 생성
sort 는 원본자체를 변화. 즉 return이 필요 없다

```python
li= ['하', '교', '캅', '의', '지', '가']
print(li.sort())
# none 이 출력. 왜냐하면 sort 는 return 값이 없기 때문이다.
```