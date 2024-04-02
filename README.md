import random

random_list = [random.randint(0,100) for a in range(20)]

first_half = random_list[:10]
second_half = random_list[10:]
first_half.sort()
second_half.sort(reverse=True)
result_list = first_half + second_half
print("隨機列表:\n", random_list)
print("排序後的列表:\n", result_list)

