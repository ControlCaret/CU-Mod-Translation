# Casualties: Unknown 모드 번역 모음집

Casualties: Unknown의 모드 한국어 번역을 모아 둔 저장소입니다.

## 번역된 모드

| 모드 | 버전 | 번역 파일 |
| --- | --- | --- |
| [QoL Unknown](https://github.com/jimmyking9999999/QoL-Unknown) | v1.1.5 | [KR-QoL.Unknown.json](https://github.com/ControlCaret/CU-Mod-Translation/blob/main/KR-QoL.Unknown.json) |
| [Comforts Unknown - Performance](http://www.nexusmods.com/scavprototype/mods/925) | v0.1.5 | [KR-ComfortsUnknown.Performance.json](https://github.com/ControlCaret/CU-Mod-Translation/blob/main/KR-ComfortsUnknown.Performance.json) |

## 적용 방법

1. **BepInEx가 필요합니다.** BepInEx와 한글 가독성 패치가 함께 포함된 [한글 폰트 가독성 패치 배포본](https://github.com/EnineStuxnet/Casualties-Unknown-Korean-Patch/releases)을 설치하는 것을 권장합니다. 배포 페이지의 안내에 따라 설치해 주세요.

2. **[MKL 모드](https://gall.dcinside.com/mgallery/board/view/?id=scav&no=112)를 설치합니다.** 배포처 안내에 따라 설치하며, `BepInEx/plugins` 안에 `MKL.dll`과 `Translations` 폴더가 있으면 됩니다.

   ```text
   Casualties Unknown/
   └─ BepInEx/
      └─ plugins/
         ├─ MKL.dll
         └─ Translations/
   ```

3. **모드 번역 JSON 파일을 다운로드해 `Translations` 폴더에 넣습니다.** 원하는 모드 번역 파일 링크를 열고 **Download raw file**로 다운로드합니다. 여러 모드의 번역을 함께 적용하려면 각 모드의 번역 JSON 파일을 모두 `Translations` 폴더에 넣으면 됩니다. QoL Unknown 번역을 적용하는 경우 아래와 같이 배치합니다.

   ```text
   Casualties Unknown/
   └─ BepInEx/
      └─ plugins/
         ├─ MKL.dll
         └─ Translations/
            └─ KR-QoL.Unknown.json
   ```

## 참고 사항

- Comforts Unknown - Performance 모드의 일부 문구가 영어로 표시될 수 있습니다.

## 피드백

오역이나 미번역 문구는 [Issues](https://github.com/ControlCaret/CU-Mod-Translation/issues)로 알려 주세요.
