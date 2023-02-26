# README

이 Github Repository 는 Intellij 의 \[코루틴 가이드 공식문서]\([https://kotlinlang.org/docs/coroutines-guide.html](https://kotlinlang.org/docs/coroutines-guide.html))를 한글로 번역한 Repository 입니다.

잘못번역된 부분 혹은 오탈자가 있다면 Pull Request 를 통해 제보해주시길 바랍니다.

\---

예시를 잘 따라하기 위해서는 아래 의존성을 추가해주세요.

#### Maven

```
<dependency>
    <groupId>org.jetbrains.kotlinx</groupId>
    <artifactId>kotlinx-coroutines-core</artifactId>
    <version>1.6.4</version>
</dependency>
```

그리고 최신 코틀린 버전을 이용해주세요.

```
<properties>
    <kotlin.version>1.6.21</kotlin.version>
</properties>
```

#### Gradle

아래 의존성을 추가해주세요

```
dependencies {
    implementation("org.jetbrains.kotlinx:kotlinx-coroutines-core:1.6.4")
}
```

그리고 코틀린 최신 버전을 이용해주세요.

```
plugins {
    // For build.gradle.kts (Kotlin DSL)
    kotlin("jvm") version "1.6.21"
    
    // For build.gradle (Groovy DSL)
    id "org.jetbrains.kotlin.jvm" version "1.6.21"
}
```

리포지토리 목록에 `mavenCentral()` 이 있는지 확인해주세요.

```
repositories {
    mavenCentral()
}
```
