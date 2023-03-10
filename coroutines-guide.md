# 코루틴 가이드(Coroutines Guide)

코틀린은 다른 라이브러리에서 코루틴을 활용할 수 있도록 정규 라이브러리에서는 최소한의 API 만 제공합니다. `async` 와 `await` 을 키워드로 가지고 있는 다른 유사한 언어(프로그래밍 언어) 들과 다르게 코틀린에서는 `async` 와 `await` 이 키워드가 아니고, 정규 라이브러리에 포함되어 있지 않습니다. 또한 Kotlin 의 일시 중단 함수 개념은 퓨쳐(Futures) 와 프로마이즈(Promises) 보다 비동기 연산을 더 안전하고 오류 발생가능성이 적은 추상화를 제공합니다.



`kotlinx.coroutines` 는 JetBrains 에 의해 개발된 좀 더 다양한 API 를 제공하는 코루틴 라이브러리 입니다. 이 라이브러리에는 `launch`,`async` 등등 이 가이드에서 다루는 여러 가지 높은 수준의 코루틴을 지원하는 기본적인 요소들이 있습니다.



이 가이드 에서는 다양한 주제로 나뉘어진 일련의 예시들과 함께 `kotlinx.coroutines` 에 핵심 기능에 관해 이야기 할 것입니다.



코틀린 코루틴을 사용하여 이 가이드에 있는 예제들을 따라하려면 프로젝트 [README.md](https://github.com/tmdgusya/translate-intellij-coroutine-guide/) 에서 설명한대로 `kotlinx-coroutines-core` 모듈의 의존성을 추가해야 합니다.

