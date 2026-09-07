# Outpost — Support

**SSH workspaces for macOS.** 서버는 연결로, 작업 화면은 워크스페이스로 저장해 두고 바로 여세요.
*A Chakchak Works app — small tools that snap right in.*

- 개인정보 처리방침 / Privacy Policy: [PRIVACY.md](PRIVACY.md)
- 문의·버그 신고 / Support: [Issues](https://github.com/ulBible/outpost-support/issues)
- Mac App Store: (출시 후 링크 추가 / link coming soon)

## 요구사항 / Requirements
macOS 15 or later (Apple silicon and Intel). English UI.

## 자주 묻는 질문 / FAQ

**내 개인키와 비밀번호는 어디에 저장되나요?** — 이 맥의 Keychain에만 저장되며 iCloud로 나가지 않습니다. Outpost의 파일·로그·iCloud 레코드에는 키와 비밀번호가 들어가지 않습니다.
*Where are my private keys and passwords stored?* — Only in this Mac's Keychain, never synced. They are never written to Outpost's files, logs or iCloud records.

**iCloud 동기화를 켰는데 다른 맥에서 연결 옆에 열쇠/자물쇠 배지가 보여요.** — 의도된 동작입니다. 연결 정보는 동기화되지만 키와 비밀번호는 맥마다 한 번씩 직접 가져오거나 입력해야 합니다. 연결을 Edit…으로 열어 같은 키를 가져오거나 비밀번호를 입력하면 배지가 사라집니다.
*After turning on iCloud sync, a key or lock badge appears next to a connection on my other Mac.* — By design: connections sync, keys and passwords do not. Open the connection with Edit… and import the same key or enter the password once on that Mac.

**암호구(passphrase)가 걸린 키를 가져올 수 있나요?** — 네. 가져올 때 암호구를 한 번 묻고, 복호화한 키를 이 맥의 Keychain에 저장합니다. 암호구 자체는 저장하지 않습니다.
*Can I import a passphrase-protected key?* — Yes. Outpost asks for the passphrase once on import and stores the decrypted key in this Mac's Keychain. The passphrase itself is not kept.

**한동안 가만히 두면 세션이 끊겨요.** — 설정 ▸ General의 Keep-alive가 켜져 있는지 확인하세요(기본 30초). 값을 바꾸면 다음 접속부터 적용됩니다.
*Sessions drop after a while idle.* — Check Keep-alive in Settings ▸ General (30 s by default). Changes apply to the next connection.

**체험 기간이 끝나면 무엇이 막히나요?** — 새 SSH 세션 열기만 막힙니다. 연결·워크스페이스·스니펫 편집, 설정, iCloud 동기화, 키 가져오기는 계속 됩니다. 설정 ▸ License에서 일회 구매로 해제하거나 Restore Purchases로 이전 구매를 복원하세요.
*What stops when the trial ends?* — Only opening new SSH sessions. Editing connections, workspaces, snippets, settings, iCloud sync and key import keep working. Unlock once in Settings ▸ License, or use Restore Purchases.

**환불은 어떻게 하나요?** — 구매는 Apple이 처리합니다: https://reportaproblem.apple.com
*How do I get a refund?* — Purchases are handled by Apple: https://reportaproblem.apple.com

## 버그 신고 / Reporting a bug
[Issues](https://github.com/ulBible/outpost-support/issues)에 macOS 버전, 앱 버전(Outpost 정보에서 확인), 무엇을 했고 무엇이 보였는지를 적어주세요. 호스트 이름, 키, 비밀번호는 적지 마세요.
Please include your macOS version, the app version (About Outpost), what you did, and what you saw. Leave out host names, keys and passwords.
