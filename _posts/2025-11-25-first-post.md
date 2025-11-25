---
title: "안드로이드 개발 시작하기"
excerpt: "안드로이드 개발 환경을 구축하고 첫 앱을 만들어봅니다."
date: 2025-11-25 14:30:00 +0900
last_modified_at: 2025-11-25 14:30:00 +0900
categories:
  - Android
tags:
  - Android
  - 입문
  - Android Studio
toc: true
toc_sticky: true
---

# 안드로이드 개발 블로그를 시작합니다

안녕하세요! 안드로이드 개발자를 목표로 공부하는 과정을 기록하려고 합니다.

```kotlin
class MainActivity : ComponentActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
    }
}
```
