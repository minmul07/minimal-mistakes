```python
def sectotime(s2t):
    if (int(s2t >= 86400) != 0):
        print(f"{int(s2t/86400)}일", end = " ")
    if (int(s2t/3600) != 0):
        print(f"{int(s2t%86400/3600)}시간", end = " ")
    if (int(s2t%3600/60) != 0):
        print(f"{int(s2t%3600/60)}분", end = " ")
    if (int(s2t%60) != 0):
        print(f"{int(s2t%60)}초", end = " ")

sectotime(int(input("입력: ")))
```

    입력: 92400
    1일 1시간 40분 
