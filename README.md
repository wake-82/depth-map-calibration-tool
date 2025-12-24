# Depth Map Calibration Tool

## Overview
Depth Map Calibration Tool is a freeware application developed by an individual,
designed to assist with video processing and depth map calibration tasks.

This software is provided free of charge for **personal and non-commercial use only**.

---

## 개요
Depth Map Calibration Tool은 개인이 제작한 무료 프리웨어로,
영상 처리 및 뎁스맵(Depth Map) 보정 작업을 지원하는 도구입니다.

본 프로그램은 **비상업적 용도에 한해 무료로 사용 가능**합니다.

---

## Key Features
- Depth map video processing and calibration
  - Pre-shrink
  - Brightness / Contrast / Gamma
  - SigmaR / Gaussian Blur
  - FFmpeg-based deflicker
- Preset-based configuration management
- Video input/output using FFmpeg
- Portable execution (no installation required)

---

## 주요 기능
- 뎁스맵 영상 처리 및 보정
  - 사전 수축(Pre-Shrink)
  - 밝기 / 대비 / 감마
  - 시그마R / 가우시안 블러
  - FFmpeg 기반 디플리커(Deflicker)
- 프리셋 기반 설정 관리
- FFmpeg을 이용한 영상 입출력
- 포터블 실행 지원 (설치 불필요)

---

## How to Run
1. Place `Depth Map Calibration Tool.exe` in any folder.
2. Prepare FFmpeg (see below).
3. Run `Depth Map Calibration Tool.exe`.

All required configuration files will be generated automatically on first launch.

---

## 실행 방법
1. `Depth Map Calibration Tool.exe`를 원하는 폴더에 둡니다.
2. FFmpeg을 준비합니다. (아래 안내 참고)
3. `Depth Map Calibration Tool.exe`를 실행합니다.

프로그램 실행 시 필요한 설정 파일은 자동으로 생성됩니다.

---

## FFmpeg Notice (Important)
This software uses FFmpeg.

- FFmpeg is **not included** with this software.
- Users must obtain `ffmpeg.exe` separately.

### FFmpeg Setup
- Place `ffmpeg.exe` in the **same folder** as `Depth Map Calibration Tool.exe`.

This software only detects `ffmpeg.exe` when it is located in the same directory
as the executable.  
Registering FFmpeg in the system PATH environment variable is **not supported**.

FFmpeg official website: https://ffmpeg.org/

FFmpeg is a separate open-source project.
The use of FFmpeg is subject to its own license terms (LGPL/GPL).

---

## FFmpeg 안내 (중요)
본 프로그램은 FFmpeg을 사용합니다.

- FFmpeg은 본 프로그램에 **포함되어 있지 않습니다.**
- 사용자는 별도로 `ffmpeg.exe`를 준비해야 합니다.

### FFmpeg 설치 방법
- `ffmpeg.exe`를 `Depth Map Calibration Tool.exe`와 **같은 폴더에 배치**하세요.

본 프로그램은 `ffmpeg.exe`를 **실행 파일과 같은 폴더에서만 인식**합니다.  
FFmpeg를 환경 변수(PATH)에 등록해도 인식되지 않습니다.

FFmpeg 공식 사이트: https://ffmpeg.org/

FFmpeg는 별도의 오픈소스 소프트웨어이며,  
FFmpeg의 사용은 FFmpeg의 라이선스(LGPL/GPL)를 따릅니다.

---

## Disclaimer
- This software is freeware developed by an individual.
- The author assumes **no responsibility** for any issues, data loss,
  system failures, or damages resulting from the use of this software.
- Commercial use, resale, or paid distribution of this software is prohibited.

---

## 주의사항
- 본 프로그램은 개인이 제작한 무료 프리웨어입니다.
- 프로그램 사용으로 인해 발생하는 문제, 데이터 손실,
  시스템 오류, 기타 손해에 대해 개발자는 **어떠한 책임도 지지 않습니다.**
- 본 프로그램의 **상업적 사용, 재판매, 유료 배포는 금지**되어 있습니다.

---

## License
This software is freeware for personal and non-commercial use only.

Commercial use, resale, rental, sublicensing, or inclusion in any commercial product
or service is strictly prohibited.

This software is provided "AS IS", without warranty of any kind, express or implied.
The author shall not be held liable for any damages arising from the use of this software.

---

## 라이선스
본 소프트웨어는 개인 및 비상업적 용도로만 사용 가능한 프리웨어입니다.

상업적 사용, 재판매, 대여, 재라이선스, 또는 상업적 제품이나
서비스에의 포함은 엄격히 금지됩니다.

본 소프트웨어는 어떠한 보증도 없이 "있는 그대로(AS IS)" 제공되며,
본 소프트웨어의 사용으로 인해 발생하는 어떠한 손해에 대해서도
개발자는 책임을 지지 않습니다.
