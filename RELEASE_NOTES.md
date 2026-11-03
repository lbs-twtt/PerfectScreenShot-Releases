# Release notes / 릴리스 노트

[English guide](README.md) · [한국어 안내](README.ko.md) · [Downloads](https://github.com/lbs-twtt/PerfectScreenShot-Releases/releases)

## v2.2.0 — Braces and number sizing / 영역 괄호·번호 크기 — 2026-11-03

### English

- Added Brace (G) to group items horizontally or vertically. Set its color, width, span/depth and Down/Up/Left/Right direction; use Select (V) to move/resize it.
- Repeat G/Shift+G to increase/decrease brace width. Edits support undo/redo.
- Fixed font-size changes not resizing an existing numbered badge. Numbers and badges now scale together around the same center. New numbers use the chosen size.
- N/Shift+N adjusts number font size. Font family and Bold apply; the ineffective line-width control is disabled for numbers.
- Recent captures and Korean/English support are retained. Scrolling capture remains experimental, with the complete Chrome/NAVER workflow still unverified.

### 한국어

- 여러 요소를 가로·세로로 묶어 표시하는 영역 괄호(G)를 추가했습니다. 색상·굵기·길이·깊이와 아래·위·왼쪽·오른쪽 방향을 조절하고 선택(V)으로 이동·크기 조절합니다.
- G/Shift+G로 괄호 굵기를 늘리거나 줄입니다. 변경은 실행 취소·다시 실행할 수 있습니다.
- 글자 크기를 바꿔도 기존 번호 배지 크기가 그대로였던 문제를 수정했습니다. 숫자와 배지가 중심을 유지하며 함께 확대·축소되고 새 번호에도 지정한 크기를 적용합니다.
- N/Shift+N으로 번호 글자 크기를 조절하고 글꼴·굵게 설정을 적용합니다. 번호에서는 효과가 없는 선 굵기 입력을 비활성화했습니다.
- 최근 캡처와 한·영 지원을 유지합니다. 스크롤 캡처는 시험 기능이며 실제 Chrome/NAVER 전체 흐름 검증은 남아 있습니다.

[Download / 다운로드](https://github.com/lbs-twtt/PerfectScreenShot-Releases/releases/download/v2.2.0/PerfectScreenShot-v2.2.0-Windows-x64.zip)

## v2.1.0 — Recent captures / 최근 캡처 개선

### English

- Delete the selected recent capture, or confirm deletion of the entire list.
- Edit a recent capture at its original resolution. Finish editing adds the edited result to history while keeping the original under the 10-image limit. Copy/save/pin continue to work.
- Larger preview with Fit/100%/Ctrl+wheel zoom and scrolling for long images. Only the selected image is decoded for preview.
- History stays in your PC's memory and clears on exit or when history is disabled. Deletion does not remove saved files or clear the clipboard.
- Korean and English interfaces are included. Existing experimental scrolling capture remains unchanged; its complete Chrome/NAVER workflow is still unverified.

### 한국어

- 최근 캡처에서 선택한 한 장을 삭제하거나 확인 후 전체 목록을 삭제할 수 있습니다.
- 선택한 캡처를 원본 해상도로 편집합니다. 편집 완료 시 결과를 최근 캡처에 추가하고, 원본에도 최대 10장 보관 규칙을 적용합니다. 복사·파일 저장·화면 고정도 사용할 수 있습니다.
- 큰 미리보기에서 화면 맞춤·100%·Ctrl+휠 확대/축소와 긴 이미지 스크롤을 지원합니다. 선택한 한 장만 원본 이미지로 불러옵니다.
- 기록은 사용자 PC의 메모리에만 보관하며 종료하거나 보관 기능을 끄면 지워집니다. 목록 삭제는 저장 파일이나 클립보드 내용에 영향을 주지 않습니다.
- 한·영 화면을 지원합니다. 기존 스크롤 캡처 시험 기능은 그대로이며 Chrome/NAVER 전체 경로 검증은 남아 있습니다.

[Download / 다운로드](https://github.com/lbs-twtt/PerfectScreenShot-Releases/releases/download/v2.1.0/PerfectScreenShot-v2.1.0-Windows-x64.zip)

## v2.0.1 — First public preview / 첫 공개 시험판

### English

This is the first application release in this public download repository, for Windows 10/11 x64.

- Added Korean and English interfaces. Auto follows the Windows display language; an explicit language can be selected in Settings. Save, fully exit and reopen the app to apply changes.
- Added English versions of the built-in specification and release notes. English mode uses the English wordmark. Annotations, filenames and shortcuts are unchanged by language selection.
- Added offline open-source information in Settings → About, with original license/copyright notices for bundled .NET components. The application ZIP includes the same notices in `licenses`.
- Includes area selection, annotation tools, text backgrounds and formatting, a movable editing toolbar, clipboard/file output, pinning, mouse-button role switching and optional history of 10 captures in PC memory.
- Retains experimental scrolling capture: choose how many screens to keep, collect up to one additional screen and discard it, then select top/bottom boundaries for output. There is no manual join-confirmation stage.

**Preview limitation:** automatic stitching may leave duplicated or misaligned content. Discarding the extra final screen does not fix earlier overlaps. The complete automatic-collection-to-save workflow in Chrome/NAVER remains unverified. Review scrolling-capture output before use.

Download **`PerfectScreenShot-v2.0.1-bilingual-preview-Windows-x64.zip`** from [the v2.0.1 release](https://github.com/lbs-twtt/PerfectScreenShot-Releases/releases/tag/v2.0.1). GitHub's automatic Source code archives contain repository documents, not the executable.

### 한국어

이 공개 다운로드 저장소의 첫 실행용 배포이며 Windows 10/11 x64용입니다.

- 한국어·영어 화면을 추가했습니다. 자동 모드는 Windows 표시 언어를 따르며 설정에서 언어를 직접 선택할 수도 있습니다. 변경한 설정을 저장하고 프로그램을 완전히 종료한 뒤 다시 실행하면 적용됩니다.
- 내장 사양서와 릴리스 노트의 영어판을 추가했습니다. 영어 화면에는 영문 워드마크를 사용합니다. 언어를 바꿔도 입력한 주석·파일명·단축키는 그대로 유지합니다.
- 설정 → 프로그램 정보에 오프라인 오픈소스 정보를 추가했습니다. 포함된 .NET 구성 요소의 라이선스·저작권 원문을 제공하며 실행용 ZIP의 `licenses`에도 같은 원문을 넣었습니다.
- 영역 선택, 편집 도구, 텍스트 배경과 서식, 메뉴 이동, 클립보드 복사·파일 저장, 화면 고정, 좌·우 마우스 역할 전환과 선택적인 PC 메모리 최근 캡처 10장 보관 기능을 제공합니다.
- 스크롤 캡처 시험 기능을 유지합니다. 보관할 화면 수보다 최대 1장을 더 수집해 추가한 마지막 장을 제외하고, 상한선·하한선 사이를 출력합니다. 수동 연결 확인 단계는 없습니다.

**시험판 제한:** 자동 연결 결과에 내용 중복이나 어긋남이 남을 수 있습니다. 추가한 마지막 화면을 제외해도 앞쪽의 겹침까지 수정되지는 않습니다. Chrome/NAVER에서 자동 수집부터 저장까지 전체 과정은 아직 미검증입니다. 스크롤 캡처 결과를 확인한 뒤 사용해 주세요.

[v2.0.1 릴리스](https://github.com/lbs-twtt/PerfectScreenShot-Releases/releases/tag/v2.0.1)에서 **`PerfectScreenShot-v2.0.1-bilingual-preview-Windows-x64.zip`**을 내려받으세요. GitHub의 자동 Source code 압축 파일은 저장소 안내 문서이며 실행 파일이 아닙니다.
