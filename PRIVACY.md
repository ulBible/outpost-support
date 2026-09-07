# Outpost 개인정보 처리방침 · Privacy Policy

시행일 / Effective: 2026-09-05 · Chakchak Works

## 한국어

**Outpost는 어떤 개인정보도 수집하지 않습니다.** Chakchak Works가 운영하는 서버, 분석 도구, 계정, 광고가 없습니다.

Outpost가 네트워크에 연결하는 경우는 세 가지뿐이며, 모두 사용자가 직접 시작합니다:

- **SSH 연결** — 사용자가 등록한 서버로만 접속합니다. 통신 내용은 그 서버와 사용자 사이에서만 오가며 Chakchak Works를 거치지 않습니다.
- **iCloud 동기화(선택)** — 설정에서 켠 경우에만, Apple의 CloudKit을 통해 **사용자 본인의 iCloud 계정 비공개 데이터베이스**에 저장됩니다. 동기화되는 것은 연결 정보(이름·호스트·포트·사용자 이름·인증 방식·점프 호스트·공개키 지문·테마), 워크스페이스, 스니펫, 가져온 테마뿐입니다. **개인키와 비밀번호는 절대 동기화되지 않습니다.** Chakchak Works는 이 데이터에 접근할 수 없습니다.
- **App Store 구매** — 체험판과 구매는 Apple의 StoreKit이 처리하며 Outpost는 결제 정보를 다루지 않습니다.

이 맥에 저장되는 것:

| 데이터 | 위치 | 비고 |
|---|---|---|
| 개인키·비밀번호 | macOS Keychain (이 기기 전용) | iCloud Keychain으로 동기화되지 않음. 앱 파일·로그에 기록되지 않음 |
| 연결·워크스페이스·스니펫·테마·설정 | 앱 컨테이너 | iCloud 동기화를 켜면 위 항목 중 일부가 사용자의 iCloud로 |
| 알려진 호스트(호스트 키 지문) | 앱 컨테이너 | 동기화되지 않음 |

접속 후 명령과 스니펫은 입력한 그대로 저장·동기화되므로 거기에 비밀번호나 토큰을 적지 않기를 권합니다.

앱이 요청하는 권한과 용도:

| 권한 | 용도 |
|---|---|
| 네트워크(클라이언트) | SSH 접속, iCloud 동기화 |
| 네트워크(서버) | 워크스페이스 포트 포워딩의 127.0.0.1 리스너. 외부에서 접속할 수 없습니다 |
| 파일 열기(사용자가 선택한 파일) | 개인키·~/.ssh/config·iTerm2 테마 파일 가져오기. 선택한 파일만 읽습니다 |
| iCloud(CloudKit)·푸시 알림 | 동기화를 켠 경우 변경 사항을 받기 위한 무음 알림. 사용자에게 보이는 알림은 없습니다 |

문의: https://github.com/ulBible/outpost-support/issues

## English

**Outpost does not collect any personal data.** There are no Chakchak Works servers, no analytics, no accounts and no ads.

Outpost connects to the network in only three cases, each started by you:

- **SSH connections** — only to servers you add. Traffic flows between you and that server and never passes through Chakchak Works.
- **iCloud sync (optional)** — only when you turn it on in Settings, using Apple's CloudKit and **your own iCloud account's private database**. Synced items are connections (name, host, port, user name, authentication method, jump host, public-key fingerprint, theme), workspaces, snippets and imported themes. **Private keys and passwords are never synced.** Chakchak Works cannot access this data.
- **App Store purchases** — the trial and the unlock are handled by Apple's StoreKit; Outpost never sees payment details.

What is stored on your Mac:

| Data | Where | Notes |
|---|---|---|
| Private keys and passwords | macOS Keychain, this device only | Not synced by iCloud Keychain; never written to app files or logs |
| Connections, workspaces, snippets, themes, settings | App container | Some of these go to your iCloud if you turn sync on |
| Known hosts (host-key fingerprints) | App container | Never synced |

Post-connect commands and snippets are stored and synced as you typed them, so keep passwords and tokens out of them.

Permissions the app asks for, and why:

| Permission | Purpose |
|---|---|
| Network (client) | SSH connections and iCloud sync |
| Network (server) | The 127.0.0.1 listener for workspace port forwards. It never accepts connections from outside this Mac |
| Open files you choose | Importing private keys, ~/.ssh/config and iTerm2 theme files. Only the files you pick are read |
| iCloud (CloudKit) and push notifications | Silent notifications that deliver sync changes when sync is on. There are no user-visible notifications |

Contact: https://github.com/ulBible/outpost-support/issues
