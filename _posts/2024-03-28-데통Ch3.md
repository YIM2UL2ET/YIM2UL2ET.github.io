---
published: false
title: ch1. 개요
layout: post
date: 2024-03-28 00:00:00 +09:00
categories: [Data Communication, PartⅡ 물리층]
tags: [CS, 데이터 통신]
---

## **1. 데이터 및 신호**
- data를 signal로 보냄.

### **1-1. analog data와 digital data**
- analog data: 연속적인 값을 갖는 자료
- digital data: 이산적인 값을 갖는 자료

### **1-2 analog signal과 digital signal**
- analog signal: 전체 시간동안 부드럽게 변화하는 연속적 파형
- digital signal: 0과 1의 값을 갖는 이산적인 신호
- analog signal은 sampling 되어 digital signal로 변환됨.<br>
![신호](https://media.licdn.com/dms/image/C5612AQE8GHh4P3sRUQ/article-cover_image-shrink_600_2000/0/1577661520230?e=2147483647&v=beta&t=iAbs3mG1aBfkj_u9QuZtXHkq32fRmWStvJxpvXcgyQY)

### **1-3. periodic signal와 nonperiodic signal**
- periodic signal: 주기 내에 특정 패턴이 만들어지고, 주기당 패턴이 반복되는 signal
- nonperiodic signal: 반복되는 패턴이나 cycle 없이 항상 변화하는 signal

## **2. 주기 아날로그 신호**

### **2-1. 정현파**

- periodic analog signal의 가장 기본적 형태
- 최대진폭, 주파수, 위상. 3가지 특성으로 나타낼 수 있음.

#### 최대 진폭 (peak amplitude)
- 정의: 평균값이나 0을 기준으로 진폭과 해당 기준과의 최대 절대값.
- 전기 신호의 경우 흔히 전압으로 측정됨.<br>
<img src="https://ars.els-cdn.com/content/image/3-s2.0-B9780750671736500031-f02-02-9780750671736.gif">

#### 주파수 (fre-quency)
- 정의: 1초 동안 생성되는 신호 주기의 수. Hz로 나타냄.
- 주기(period): signal이 한 cycle을 완성하는 데 필요한 시간의 양 (sec 단위)
- Hertz(Hz): 매초당 사이클 수
- period와 fre-quency는 서로 역의 관계<br><img src="https://img1.daumcdn.net/thumb/R800x0/?scode=mtistory2&fname=https%3A%2F%2Ft1.daumcdn.net%2Fcfile%2Ftistory%2F2407704051A98A572C" width="150"><br>
- 주기와 주파수 단위<br>
![단위](https://i.imgur.com/0Atm9iz.png)

// 미완

### **2-2. 위상(phase)**
주의* wave 한정에서 위상을 말하는 것

- 정의: 시각 0시에 대한 파형의 상대적인 위치

--------------

### **2-6.대역폭(bandwidth)**
신호처리(signal processing)에서의 정의: 연속적인 주파수(fre-quency)에 포함된 최고 주파수와 최저 주파수의 차이. 단위는 보통 Hz로 나타냄.
