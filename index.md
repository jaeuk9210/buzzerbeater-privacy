# 버저비터 개인정보처리방침 / Privacy Policy

시행일 / Effective date: 2026-11-16

## 한국어

"버저비터"(이하 "앱")는 KBL(한국프로농구) 경기의 실시간 점수를 알림으로 보여 주는 앱입니다. 앱은 사용자의 이름, 연락처, 위치, 사진, 계정 정보를 수집하지 않으며 회원 가입도 없습니다. 아래는 앱이 동작하면서 다루는 정보와 그 처리 방식입니다.

### 1. 앱이 처리하는 정보

**알림을 위한 기기 식별자 (Firebase Cloud Messaging)**
- 알림을 받으려고 앱은 Google의 Firebase Cloud Messaging(FCM)을 사용합니다. 이때 Firebase가 앱을 설치한 기기마다 설치 ID와 알림 토큰을 만들어 Google 서버에 보관합니다.
- 사용자가 고른 팀과 발급한 경기에 해당하는 알림 주제(topic)가 이 토큰에 묶여 FCM에 등록됩니다. 알림을 정확히 보내기 위한 것이며 다른 목적으로 쓰지 않습니다.
- 주제를 등록하거나 해지할 때 Firebase는 앱 버전도 함께 처리합니다.
- 앱 운영자(개발자)의 서버는 이 토큰을 받지도, 저장하지도 않습니다. 서버는 "특정 주제에 알림을 보낸다"는 요청만 FCM에 보냅니다.
- Google이 이 정보를 처리하는 방식은 [Firebase 개인정보 보호 및 보안](https://firebase.google.com/support/privacy)과 [Google 개인정보처리방침](https://policies.google.com/privacy)을 따릅니다.

**기기 안에만 저장되는 설정**
- 응원팀, 알림을 받는 팀, 발급한 티켓, 알림을 끈 경기, 홈 화면 위젯 설정 정보는 사용자의 기기 안에만 저장되며 앱 운영자의 서버로 보내지 않습니다.

**KBL 서버 접속**
- 경기 일정, 순위, 점수를 가져오려고 앱이 KBL의 서버에 직접 접속합니다. 이때 접속 기록(IP 주소 등)이 KBL 쪽에 남을 수 있으며, 이는 KBL의 정책을 따릅니다.

**TVING 접속**
- 진행 중인 경기 티켓에서 TVING 중계 화면으로 바로 갈 수 있게 하려고, 앱이 TVING(tving.com)의 공개 화면을 받아 그 경기의 중계 주소를 찾아 둡니다. 이때 접속 기록(IP 주소 등)이 TVING 쪽에 남을 수 있으며, 이는 TVING의 정책을 따릅니다. 이 요청에는 사용자를 식별하는 정보를 담지 않습니다.
- 사용자가 TVING 버튼을 누르면 TVING 앱 또는 웹으로 이동하며, 그 뒤의 정보 처리는 TVING의 정책을 따릅니다.

### 2. 앱이 요청하는 권한
- **알림(POST_NOTIFICATIONS)**: 경기 점수 알림을 보여 주기 위해 사용합니다. 허용하지 않아도 앱의 다른 기능은 쓸 수 있습니다.
- **실시간 알림(POST_PROMOTED_NOTIFICATIONS)**: Android의 실시간 업데이트(Live Updates) 형태로 점수를 보여 줍니다.
- **인터넷(INTERNET)**: 일정·순위 조회와 알림 수신에 사용합니다.

### 3. 제3자 제공과 광고
- 앱에는 광고가 없고, 분석·추적 도구를 쓰지 않습니다.
- 사용자 정보를 판매하거나 제3자에게 제공하지 않습니다. 위에서 설명한 Google(Firebase), KBL 서버, TVING 접속 외에는 외부로 나가는 정보가 없습니다.

### 4. 보관과 삭제
- 앱 안에 저장된 설정은 앱을 삭제하면 함께 지워집니다.
- 앱을 삭제하면 기기의 알림 토큰은 더 이상 쓰이지 않으며, Google은 일정 기간이 지나면 사용하지 않는 토큰을 정리합니다.
- 앱 운영자가 보관하는 사용자 정보가 없으므로 별도의 삭제 요청 절차는 없습니다. 문의가 있으면 아래 연락처로 보내 주세요.

### 5. 어린이
- 앱은 만 14세 미만 어린이를 대상으로 하지 않으며, 어린이의 정보를 따로 수집하지 않습니다.

### 6. 방침의 변경
- 이 방침을 바꾸면 이 문서에 변경된 내용과 시행일을 올립니다.

### 7. 문의
- jaeuk@jeuke.com

---

## English

"Buzzer Beater" ("버저비터", the "App") shows live scores of KBL (Korean Basketball League) games as notifications. The App does not collect your name, contact details, location, photos or account information, and there is no sign-up. Below is the information the App handles and how.

### 1. Information the App handles

**Device identifiers for notifications (Firebase Cloud Messaging)**
- To deliver notifications the App uses Google's Firebase Cloud Messaging (FCM). Firebase creates an installation ID and a notification token for each device and stores them on Google's servers.
- Notification topics matching the teams you choose and the games you pick up tickets for are registered with FCM against this token. This is only used to deliver the right notifications.
- When a topic is registered or removed, Firebase also processes the App's version.
- The developer's server never receives or stores this token. It only asks FCM to send a notification to a topic.
- Google processes this data under [Firebase Privacy and Security](https://firebase.google.com/support/privacy) and the [Google Privacy Policy](https://policies.google.com/privacy).

**Settings stored only on your device**
- Your favorite team, the teams you receive alerts for, issued tickets, muted games and home-screen widget settings are stored on your device only and are not sent to the developer's server.

**Connections to KBL servers**
- To fetch schedules, standings and scores, the App connects directly to KBL's servers. KBL may keep connection logs (such as your IP address) under its own policies.

**Connections to TVING**
- To take you straight to the TVING broadcast of a game in progress, the App downloads a public TVING (tving.com) page and looks up that game's broadcast address. TVING may keep connection logs (such as your IP address) under its own policies. The request carries no information that identifies you.
- When you tap the TVING button, you are taken to the TVING app or website, and what happens next is governed by TVING's policies.

### 2. Permissions
- **Notifications (POST_NOTIFICATIONS)**: to show score notifications. The rest of the App works without it.
- **Promoted notifications (POST_PROMOTED_NOTIFICATIONS)**: to show scores as Android Live Updates.
- **Internet (INTERNET)**: to fetch schedules and standings and to receive notifications.

### 3. Sharing and ads
- The App has no ads and uses no analytics or tracking tools.
- We do not sell or share your information. Apart from the Google (Firebase), KBL and TVING connections described above, no information leaves your device.

### 4. Retention and deletion
- Settings stored in the App are removed when you uninstall it.
- After uninstalling, the device's notification token is no longer used, and Google removes unused tokens after a period of time.
- The developer holds no user data, so there is no separate deletion process. Contact us below with any questions.

### 5. Children
- The App is not directed at children under 14 and does not knowingly collect their information.

### 6. Changes
- If this policy changes, the updated text and effective date will be posted in this document.

### 7. Contact
- jaeuk@jeuke.com
