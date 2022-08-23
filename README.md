# provier를 왜 사용하는가?
- 전역 상태를 관리하기 위해서

# 상태 관리 관점에서 provider
- provider는 상태를 관리할수있는 툴을 제공하지만, 특정한 방법을 강제하지는 않는다.

# State Management
- Dependency Injection
- Synchronizing data and UI

# Provider
- 위젯에 위젯이 아닌 데이터와 메서드를 쉽게 액세스 할 수 있는 방법을 제공하고 데이터가 변경되었을때 데이터가 변경되었다는 사실을
그 데이터를 필요로 하는 위젯에 제공하여 필요할때 위젯이 리빌딩 될 수 있도록 한다. 다른 말로하면 비즈니스 로직을 ui와 분리했다고한다.
- provider의 특이점중 하나는 provider 그 자체가 위젯이라는것이다.
