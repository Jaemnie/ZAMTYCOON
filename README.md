# ZAMTYCOON

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 소개
**ZAMTYCOON**은 Electron과 Node.js로 작성된 모드된 마인크래프트를 위한 커스텀 런처입니다. 이 런처를 통해 Java, Forge 또는 다른 모드를 설치하는 번거로움 없이 모드 서버에 접속할 수 있습니다.

## 기능
- 계정 관리: 여러 계정을 추가하고 쉽게 전환 가능
- 자산 관리: 클라이언트 업데이트 자동 수신 및 파일 검증
- Java 검증 및 설치: 호환되지 않는 Java 버전이 설치된 경우 자동으로 올바른 버전 설치
- 뉴스 피드 및 직관적인 설정 관리
- 서버 구성 전환 및 플레이어 수 확인
- 자동 업데이트

## 스크린샷
![스크린샷](screenshot.png)  <!-- 여기에 스크린샷 이미지 경로를 추가하세요 -->

## 설치 방법
1. 이 저장소를 클론합니다.
    ```bash
    git clone https://github.com/Jaemnie/ZAMTYCOON.git
    ```
2. 프로젝트 디렉터리로 이동합니다.
    ```bash
    cd ZAMTYCOON
    ```
3. 필요한 종속성을 설치합니다.
    ```bash
    npm install
    ```
4. 애플리케이션을 시작합니다.
    ```bash
    npm start
    ```

## 사용된 라이브러리
- [Electron](https://www.electronjs.org/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## 코드 구조
- `index.js`: 메인 파일
- `app/`: 애플리케이션 파일
- `build/`: 빌드 구성 파일
- `docs/`: 문서 파일
- `libraries/`: 라이브러리 파일
- 기타 설정 및 구성 파일

## 기여 방법
1. 이 저장소를 포크합니다.
2. 새로운 브랜치를 만듭니다.
    ```bash
    git checkout -b feature/새로운기능
    ```
3. 기능을 추가하거나 버그를 수정합니다.
4. 변경 사항을 커밋합니다.
    ```bash
    git commit -am '새 기능 추가'
    ```
5. 브랜치에 푸시합니다.
    ```bash
    git push origin feature/새로운기능
    ```
6. 풀 리퀘스트를 생성합니다.

## 라이선스
이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참고하세요.

## 작성자
- [Jaemnie](https://github.com/Jaemnie)

## 문의
질문이나 문의 사항이 있으면, [issues](https://github.com/Jaemnie/ZAMTYCOON/issues) 섹션에 남겨주세요.
