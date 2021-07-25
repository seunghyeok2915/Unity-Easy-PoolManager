# Unity Easy PoolManager
매우 쉬운 풀매니저
## 사용법
### 설명
IPoolable 은 풀매니저로 가져온후 함수를 호출하고싶을때 사용합니다.
예제 - 
```c#
    public void OnPool()
    {
        transform.position = new Vector3(0, 5, 0); // 0,5,0 좌표로 이동
    }
```
### 생성
```c#
PoolManager.CreatePool<타입>(이름, 부모 오브젝트 트랜즈폼, 생성 개수); // 풀 생성
```
### 가져오기
```c#
PoolManager.GetItem<타입>(이름);
```
