# 100doo

## English

### Overview

100doo is a macOS menu-bar (tray) app. It is the companion to the 100doo VS Code extension: it keeps supervising tasks from the tray and continues scheduled runs even when VS Code is closed. The product page is https://100doo.com. The VS Code extension is https://marketplace.visualstudio.com/items?itemName=experlab.100doo.

### Install

Download the latest disk image for your Mac:

- Apple Silicon (arm64): https://github.com/100doo/desktop-releases/releases/latest/download/100doo-arm64.dmg
- Intel (x64): https://github.com/100doo/desktop-releases/releases/latest/download/100doo-x64.dmg

Open the DMG and drag 100doo to the Applications folder.

### Requirements

- macOS 13 or later
- Claude Code CLI (`claude` installed and logged in)

### Release assets

| File | What to do |
| --- | --- |
| `100doo-arm64.dmg`, `100doo-x64.dmg` | Download the DMG for your Mac. These are the only files you need. |
| zip, blockmap, `latest-mac.yml` | Used for automatic updates. You do not need to download them. |

### Automatic updates

The app downloads a new version and installs it when you quit. It does not restart itself. To turn this off, put `{ "autoUpdate": false }` in `~/.agent-orchestrator/app-config.json` (create the file if it does not exist) and restart the app.

### Source

The source code is private.

## 한국어

### 개요

100doo는 macOS 메뉴 바(트레이) 앱입니다. VS Code 확장 100doo의 동반 앱으로, 트레이에서 상시 관제하고 VS Code가 꺼져 있어도 예약 실행을 이어 갑니다. 소개 페이지는 https://100doo.com 입니다. VS Code 확장은 https://marketplace.visualstudio.com/items?itemName=experlab.100doo 입니다.

### 설치

사용 중인 Mac에 맞는 최신 DMG를 받습니다.

- Apple Silicon (arm64): https://github.com/100doo/desktop-releases/releases/latest/download/100doo-arm64.dmg
- Intel (x64): https://github.com/100doo/desktop-releases/releases/latest/download/100doo-x64.dmg

DMG를 열어 100doo를 응용 프로그램 폴더로 끌어 놓습니다.

### 요구 사항

- macOS 13 이상
- Claude Code CLI(`claude` 설치·로그인)

### 릴리스 자산

| 파일 | 설명 |
| --- | --- |
| `100doo-arm64.dmg`, `100doo-x64.dmg` | 사람은 이 DMG만 받으면 됩니다. |
| zip, blockmap, `latest-mac.yml` | 자동 업데이트용이라 직접 받을 필요가 없습니다. |

### 자동 업데이트

새 버전을 받아 두었다가 앱을 종료할 때 설치합니다. 스스로 재시작하지 않습니다. 끄려면 `~/.agent-orchestrator/app-config.json`(없으면 새로 만듭니다)에 `{ "autoUpdate": false }`를 넣고 앱을 다시 실행합니다.

### 소스

소스 코드는 비공개입니다.
