# Weekpane 개인정보처리방침 / Privacy Policy

최종 수정: 2026-10-22

## 한국어

Weekpane은 내 PC에서만 동작하는 Windows 데스크톱 앱입니다. 개발자가 운영하는 서버는 없으며, 개발자는 사용자의 정보를 수집·저장·열람하지 않습니다.

**Google 계정에서 접근하는 정보**
- 사용자가 구글 로그인을 허용하면 Weekpane은 다음에 접근합니다.
  - 캘린더 일정의 보기·추가·수정·삭제 (`calendar.events` 범위)
  - 캘린더 목록 보기 (`calendar.calendarlist.readonly` 범위)
  - 로그인한 계정의 이메일 주소 (설정 화면에 "로그인됨"으로 표시하는 용도)

**사용 목적**
- 위의 정보는 사용자의 PC에서 일정을 바탕화면 위젯으로 보여 주고, 사용자가 위젯에서 직접 요청한 일정 추가·수정·삭제를 수행하는 데에만 쓰입니다.

**저장과 전송**
- 일정 데이터는 구글 서버와 사용자의 PC 사이에서만 오가며, 개발자나 제3자의 서버로 전송되지 않습니다.
- 로그인 토큰은 사용자 PC의 Windows 암호화 저장소(`safeStorage`)로 암호화되어 `%APPDATA%\Weekpane` 폴더에만 저장됩니다.
- 위젯 설정, ICS 주소(입력한 경우)도 같은 폴더에 저장됩니다.
- 광고, 분석, 사용자 추적, 인공지능 학습에 사용하지 않으며 제3자에게 판매·공유하지 않습니다.

**Google API 서비스 사용자 데이터 정책 준수**
Weekpane이 Google API에서 받은 정보를 사용하고 다른 곳에 전달하는 방식은 제한적 사용(Limited Use) 요건을 포함한 [Google API 서비스 사용자 데이터 정책](https://developers.google.com/terms/api-services-user-data-policy)을 준수합니다.

**삭제와 권한 회수**
- 앱의 설정 → **로그아웃**을 누르면 저장된 로그인 토큰이 삭제됩니다.
- 구글 쪽 권한은 [구글 계정의 타사 앱 액세스](https://myaccount.google.com/permissions)에서 언제든 회수할 수 있습니다.
- 앱을 삭제하고 `%APPDATA%\Weekpane` 폴더를 지우면 PC에 남은 모든 데이터가 사라집니다.

**문의**
개인정보와 관련한 문의는 [GitHub 이슈](https://github.com/SeonYoo-Kim/Weekpane/issues)로 남겨 주세요.

## English

Weekpane is a Windows desktop app that runs entirely on your computer. There is no developer-operated server, and the developer does not collect, store, or access your data.

**Google user data accessed.** When you allow Google sign-in, Weekpane accesses: calendar events (view, create, edit, delete — `calendar.events` scope), your calendar list (`calendar.calendarlist.readonly` scope), and your account email address (shown in Settings as the signed-in account).

**Use.** This data is used only to display your events in a desktop widget and to perform the event changes you explicitly request in the widget.

**Storage and sharing.** Calendar data travels only between Google's servers and your computer. Sign-in tokens are encrypted with the Windows secure storage (`safeStorage`) and stored only in `%APPDATA%\Weekpane`. Weekpane does not send your data to the developer or any third party, and does not use it for advertising, analytics, tracking, or training AI models.

**Limited Use.** Weekpane's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

**Deletion and revocation.** Use *Sign out* in Settings to delete the stored token, revoke access at [Google Account permissions](https://myaccount.google.com/permissions), and delete `%APPDATA%\Weekpane` to remove all local data.

**Contact.** Open an issue at https://github.com/SeonYoo-Kim/Weekpane/issues.
