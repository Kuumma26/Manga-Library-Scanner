<div align="center">
  <h1>Manga Library Scanner</h1>
  <p><b>PC와 NAS에 보관한 만화 압축 파일을 빠르게 스캔하고 정리하는 Windows용 라이브러리 관리 도구</b></p>

  [![Latest Release](https://img.shields.io/github/v/release/Kuumma26/Manga-Library-Scanner?label=release)](https://github.com/Kuumma26/Manga-Library-Scanner/releases/latest)
  ![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)
  ![Runtime](https://img.shields.io/badge/runtime-Python%203.13-blue.svg)
  ![UI](https://img.shields.io/badge/UI-Qt%20%7C%20Tkinter-brightgreen.svg)
</div>

<br>

Manga Library Scanner는 ZIP, RAR, 7Z, CBZ, CBR, PDF 등으로 보관한 만화 파일을 스캔해 시리즈별 목록으로 정리하고, 해상도 분석, 중복/누락 확인, 목록 비교를 도와주는 도구입니다.

## 주요 기능

* **빠른 폴더 스캔과 저장된 목록**
  * 한 번 스캔한 목록은 다음 실행 때 빠르게 다시 불러올 수 있습니다.
  * 설정한 확장자와 최소 파일 크기 기준에 따라 필요한 파일만 목록에 포함합니다.
* **해상도와 압축 파일 검사**
  * 압축 파일 내부 이미지의 해상도, 파일 수, 용량을 분석합니다.
  * 선택 시 Ungas 포함 항목, ZIP/CBZ 손상, 중첩 압축 여부도 함께 확인할 수 있습니다.
* **목록 검색과 비교**
  * 메인 목록에서 빠르게 검색하고, 중복/누락 의심 항목만 따로 볼 수 있습니다.
  * 게시글이나 보유 목록을 붙여넣어 실제 보유 여부를 비교할 수 있습니다.
* **개별 분석과 통합 비교**
  * 특정 파일이나 폴더만 따로 분석하거나, 좌우 목록을 비교해 차이를 확인할 수 있습니다.
* **자동 업데이트**
  * GitHub 릴리즈를 기준으로 새 버전을 확인하고, 프로그램 안에서 업데이트를 진행할 수 있습니다.
  * 자동 업데이트 후 설치 위치에서는 `MangaLibraryScanner.exe` 고정명으로 실행됩니다.
* **피드백 보내기**
  * 프로그램 안에서 버그나 개선 의견을 바로 보낼 수 있고, 전송이 어려우면 작성한 내용만 복사해 둘 수 있습니다.

## 설치 및 사용

1. [최신 릴리즈](https://github.com/Kuumma26/Manga-Library-Scanner/releases/latest) 페이지를 엽니다.
2. `Manga.Library.Scanner.vX.Y.Z.exe` 형식의 최신 실행 파일을 내려받습니다.
3. 원하는 폴더에 넣고 실행합니다. 별도 설치 과정은 필요 없습니다.
4. 환경 설정에서 스캔할 폴더와 확장자, 검사 옵션을 확인한 뒤 폴더 스캔을 시작합니다.

## 사용 팁

* 통합 검색에 제목 일부를 입력하면 메인 목록이 바로 필터링됩니다.
* 메인 목록에서 더블클릭하면 파일 위치를 열 수 있고, 우클릭으로 개별 분석을 실행할 수 있습니다.
* 목록 검사는 게시글 원문을 그대로 붙여넣어도 제목 줄 위주로 정리해 비교합니다.
* 검사/분석 캐시는 해상도, Ungas, ZIP/CBZ 손상 같은 반복 검사를 줄이는 데 사용됩니다.

## 시스템 요구사항

* Windows 10 또는 Windows 11 64-bit
* 로컬 드라이브 또는 SMB/NAS 공유 폴더 접근 권한

---

<div align="center">
  <sub>최신 버전과 변경 내역은 GitHub Releases에서 확인할 수 있습니다.</sub>
</div>
