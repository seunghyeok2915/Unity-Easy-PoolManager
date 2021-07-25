# Unity Easy PoolManager
매우 쉬운 풀매니저
## 사용법
### 생성
```c#
PoolManager.CreatePool<타입>(이름, 부모 오브젝트 트랜즈폼, 생성 개수); // 풀 생성
```
### 가져오기
```c#
PoolManager.GetItem<타입>(이름);
```
