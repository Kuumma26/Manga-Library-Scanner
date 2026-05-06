<div align="center">
  <h1>📚 Manga Library Scanner</h1>
  <p><b>로컬 만화 라이브러리를 초고속으로 스캔하고 정밀하게 관리하는 강력한 Windows 전용 유틸리티</b></p>
  
  [![Latest Release](https://img.shields.io/badge/release-v8.10.1-blue)](https://github.com/Kuumma26/Manga-Library-Scanner/releases)
  [![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)]()
  [![Python](https://img.shields.io/badge/python-3.13-blue.svg)]()
  [![PyQt6](https://img.shields.io/badge/UI-PyQt6%20%7C%20Tkinter-brightgreen.svg)]()
</div>

<br>

Manga Library Scanner는 PC나 NAS에 저장된 방대한 양의 만화 압축 파일(ZIP, RAR, 7Z, CBZ, CBR)을 빠르게 스캔하여 목록화하고, 내부 화질을 분석하며, 손쉽게 검색 및 대조할 수 있는 도구입니다.

## ✨ 주요 기능 (Key Features)

* ⚡ **초고속 스마트 스캔 및 캐싱**
  * 압축 파일들을 순식간에 읽어 들이고 `scan_cache.json`을 통해 다음 로딩 시간을 획기적으로 단축합니다.
* 🔍 **정밀 압축 파일 내부 분석**
  * 압축을 풀지 않고도 내부 이미지의 화질(가로/세로 해상도), 페이지 수, 용량 등을 정밀하게 분석합니다.
* 🎨 **모던 UI 및 커스텀 테마**
  * 세련된 PyQt6 기반 화면을 제공하며, 취향에 맞는 다양한 테마(Midnight Neon, Liquid Glass 등)를 지원합니다.
* 📊 **강력한 목록 대조 및 관리**
  * '목록 검사', '통합 비교' 기능을 통해 내가 보유한 목록과 외부 목록(클립보드 등)을 한눈에 비교하고 빈 곳을 채울 수 있습니다.
* 🔄 **원클릭 자동 업데이트 시스템**
  * GitHub 저장소와 연동된 내장 오토 업데이터로, 프로그램 내에서 알림을 받고 클릭 한 번으로 이전 버전 찌꺼기 없이 최신 버전을 유지합니다.

## 🚀 설치 및 사용 방법

1. [GitHub Releases](https://github.com/Kuumma26/Manga-Library-Scanner/releases) 페이지로 이동합니다.
2. 가장 최신 버전의 `Manga.Library.Scanner.vX.X.X.exe` 파일을 다운로드합니다.
3. 별도의 설치 과정 없이, 원하시는 폴더에 넣고 바로 실행하시면 됩니다! (포터블 앱)
4. **환경설정(⚙️)** 메뉴에서 만화가 저장된 폴더 경로를 추가하고 스캔을 시작해 보세요.

## 💡 팁 및 단축키

* **클립보드 검색**: 외부 브라우저 등에서 텍스트를 복사한 뒤 미리 설정된 글로벌 단축키를 누르면 즉시 앱이 활성화되며 검색 및 대조가 진행됩니다.
* 메인 목록에서 항목을 더블클릭 하거나 우클릭하여 개별 파일 분석 및 파일 열기가 가능합니다.

## 🛠 시스템 요구사항

* Windows 10 또는 Windows 11 (64-bit)
* 압축 파일 분석을 위해 로컬 디스크 및 SMB/NAS 네트워크 드라이브 환경 지원

---
<div align="center">
  <sub>만들어진 버그는 잡고, 편의성은 끝없이 올립니다. 🚀</sub>
</div>
