# VirtualMac support · VirtualMac 지원

VirtualMac runs a separate macOS workspace on an Apple silicon Mac, using Apple Virtualization. The app supports English and Korean.

VirtualMac은 Apple Silicon Mac에서 Apple Virtualization으로 별도의 macOS 작업 공간을 실행합니다. 한국어와 영어를 지원합니다.

The Mac App Store release is being prepared. The app is not yet available for purchase. · Mac App Store 출시를 준비 중이며, 아직 구매할 수 없습니다.

## Contact · 문의

Developer · 개발자: **Eun Chan Kim**

Email · 이메일: **[eunchan0817@gmail.com](mailto:eunchan0817@gmail.com)**

For installation problems, bug reports, or privacy requests, include your VirtualMac version, main Mac's macOS version, and the step where the problem occurred. Do not send passwords, API keys, your virtual disk, or private clipboard and task contents. Remove personal information from any screenshot you choose to send.

설치 문제, 오류, 개인정보 관련 요청은 이메일로 보내 주세요. VirtualMac 버전, 메인 Mac의 macOS 버전, 문제가 생긴 단계를 함께 알려 주세요. 암호·API 키·가상 디스크·비공개 클립보드나 작업 내용은 보내지 마세요. 스크린샷을 보내려면 먼저 개인정보를 지워 주세요.

## Getting started · 처음 시작하기

1. Use an Apple silicon Mac with macOS 14 or later. Allow at least 65GiB free space for downloading and installing macOS. The default virtual Mac uses 8GiB memory and a 64GiB virtual disk.
2. Open VirtualMac and follow **Get started**. Download and install macOS, then start the virtual Mac.
3. Finish macOS Setup Assistant inside the virtual Mac and create a local account. An Apple Account is not required for basic VM use.
4. In the virtual Mac's Finder, open **My Shared Files > AgentSetup > VirtualMacGuest.app** and choose **Install connection helper**. If the share is missing, use Finder's **Go > Go to Folder** and enter `/Volumes/My Shared Files/AgentSetup`.
5. In the installed helper, allow Accessibility and Screen Recording inside the virtual Mac. Use the virtual Mac account password if macOS asks. Choose **Quit & Reopen** when prompted. Enable **Start at login**, approving it in Login Items if required.
6. Check the main app's guide for a live connection and both permissions. Optional external tools, accounts, and fees are separate.

1. Apple Silicon과 macOS 14 이상이 필요합니다. macOS 다운로드와 설치에 최소 65GiB의 여유 공간을 준비하세요. 기본 가상 Mac은 메모리 8GiB와 가상 디스크 64GiB를 사용합니다.
2. VirtualMac의 **처음 시작하기** 안내를 따라 macOS를 내려받아 설치하고 가상 Mac을 시작하세요.
3. 가상 Mac 안에서 macOS 초기 설정을 마치고 로컬 계정을 만드세요. 기본 VM 사용에는 Apple 계정이 필요하지 않습니다.
4. 가상 Mac의 Finder에서 **My Shared Files > AgentSetup > VirtualMacGuest.app**을 열고 **연결 도우미 설치**를 누르세요. 공유 폴더가 보이지 않으면 **이동 > 폴더로 이동**에 `/Volumes/My Shared Files/AgentSetup`을 입력하세요.
5. 설치된 도우미에서 접근성과 화면 기록을 허용하세요. macOS가 요청하면 가상 Mac 계정 암호를 사용하고 **종료 및 다시 열기**를 선택하세요. **로그인 시 자동 실행**도 켜고, 승인 대기라면 로그인 항목 설정에서 허용하세요.
6. 메인 앱의 안내에서 실제 연결과 두 권한을 확인하세요. 외부 도구의 설치·계정·요금은 별도입니다.

These instructions describe the current build; final store installation instructions will be updated after release validation. · 현재 빌드 기준 안내이며, 최종 스토어 설치 안내는 출시 검증 후 갱신합니다.

## Common questions · 자주 묻는 질문

**The guest is disconnected.** Log in to the virtual Mac and open VirtualMacGuest. Closing the VM window does not necessarily shut down the virtual Mac. A paused VM cannot process requests.

**게스트가 연결되지 않아요.** 가상 Mac에 로그인하고 VirtualMacGuest를 여세요. VM 창을 닫는 것만으로 가상 Mac이 종료되지는 않습니다. 일시 정지한 VM은 요청을 처리할 수 없습니다.

**Permissions do not update.** Grant them inside the virtual Mac, then quit and reopen the guest helper if macOS requests it. An updated helper may need permission approval again.

**권한이 반영되지 않아요.** 가상 Mac 안에서 권한을 허용하고 macOS 안내에 따라 도우미를 종료한 뒤 다시 여세요. 도우미 업데이트 후에는 다시 승인해야 할 수 있습니다.

**Shutdown is waiting.** Check the guest screen for a confirmation or unsaved work. Force stop can lose unsaved work.

**종료가 끝나지 않아요.** 게스트 화면에서 종료 확인이나 저장 창을 확인하세요. 강제 중지하면 저장하지 않은 작업을 잃을 수 있습니다.

## Privacy · 개인정보

Read the [VirtualMac privacy policy · 개인정보처리방침](PRIVACY.md).
