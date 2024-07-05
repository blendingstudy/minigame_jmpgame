# Mini Game - Jump Game

This repository contains a simple mini game called Jump Game.

## Installation

Clone the repository:

```bash
git clone https://github.com/blendingstudy/minigame_jumpgame.git
cd minigame_jumpgame


This repository contains the code for a simple "Jump Game" implemented in HTML, CSS, and JavaScript.

## How to Play

1. Clone or download the repository.
2. Open `jumpgame.html` in a web browser.
3. Use arrow keys to move the player left or right.
4. Press spacebar to jump over obstacles.
5. Avoid colliding with obstacles to stay alive and progress through stages.

# 점프 게임

이 저장소는 HTML, CSS, JavaScript로 구현된 간단한 "점프 게임" 코드를 포함하고 있습니다.

## 게임 실행 방법

1. 저장소를 클론하거나 다운로드합니다.
2. 웹 브라우저에서 `index.html` 파일을 엽니다.
3. 화살표 키를 사용하여 플레이어를 좌우로 이동합니다.
4. 스페이스바를 눌러 장애물을 점프하여 피하세요.
5. 장애물과 충돌을 피하고, 스테이지를 진행하세요!

## 개요

점프 게임은 플레이어가 장애물을 피해가며 점프하여 진행하는 간단한 대화형 게임입니다. 다음과 같은 기능을 포함하고 있습니다:

- **플레이어**: 파란색 원 형태로 표시되는 플레이어 캐릭터입니다.
- **장애물**: 화면 오른쪽에서 왼쪽으로 이동하는 사각형과 삼각형 장애물입니다.
- **게임 종료 팝업**: 플레이어가 장애물과 충돌하면 나타나는 모달 팝업입니다.
- **스테이지 및 타이머**: 현재 스테이지 번호와 게임 진행 시간을 표시합니다.

## 기능

### 플레이어 이동

화살표 키를 사용하여 게임 컨테이너 내에서 좌우로 플레이어를 이동할 수 있습니다.

### 점프 메커니즘

스페이스바를 누르면 플레이어가 점프합니다. 점프 높이는 시간이 지남에 따라 감소하며, 플레이어가 다시 땅에 착지할 때까지 반복됩니다.

### 장애물 생성

장애물은 게임 컨테이너 오른쪽에서 랜덤하게 나타나며, 서로 다른 속도로 좌측으로 이동합니다.

### 스테이지 진행

게임은 시간이 지남에 따라 스테이지가 진행됩니다. 각 스테이지에서 장애물의 속도가 증가하고, 장애물 간 시간 간격이 감소합니다.

### 게임 종료

플레이어가 장애물과 충돌하면 게임이 종료됩니다. 게임 오버 팝업에서 "재시작" 버튼을 클릭하여 게임을 다시 시작할 수 있습니다.
