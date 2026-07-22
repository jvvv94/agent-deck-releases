# 🃏 Agent Deck

> **Put Claude to work.** Describe a task, and a team of AI agents splits it up, actually does it, and reports back — you watch progress on a live board, like Jira tickets. Runs on your own Claude subscription, right on your PC.
>
> **Claude에게 일을 시키세요.** 하고 싶은 일을 말하면, AI 에이전트 팀이 일을 나눠 **실제로 처리**하고 결과를 보고합니다. 진행 상황은 Jira 티켓처럼 실시간 작업보드에서 볼 수 있어요. 내 Claude 구독으로, 내 PC에서 돌아갑니다.

<p align="center">
  <a href="https://github.com/jvvv94/agent-deck-releases/releases/latest"><b>⬇️ Download for Windows / 윈도우용 다운로드</b></a>
  &nbsp;·&nbsp;
  <a href="#-english">English</a>
  &nbsp;·&nbsp;
  <a href="#-한국어">한국어</a>
</p>

---

## 🇬🇧 English

Agent Deck is a Windows desktop app. You give it a task in plain language, and it uses **your Claude subscription** to get it done — no coding required.

### What you need (just two things)

1. A **Windows 10 or 11** computer
2. A **Claude subscription** (Pro or Max) — any account you can log into at [claude.ai](https://claude.ai)

> You don't need to install anything technical (like Node.js). It's all inside the installer.

### 1. Download & install

1. Go to the **[latest release](https://github.com/jvvv94/agent-deck-releases/releases/latest)** and download the file named **`Agent Deck_x.y.z_x64-setup.exe`**.
2. Double-click the file.
   - **If a blue "Windows protected your PC" window appears:** this is just because the app isn't code-signed yet — it is *not* a virus. Click **"More info"**, then **"Run anyway"**.
3. It installs automatically — no administrator rights needed. An **Agent Deck** icon appears on your desktop / Start menu.

### 2. First launch & connecting Claude

1. Open **Agent Deck**.
2. On the first screen, click **"Connect subscription"**.
3. A black **command window** opens, then your **web browser** shows the Claude login page.
   - Log in with the same account you use at [claude.ai](https://claude.ai).
   - When you're done, the app **moves on by itself**. (You can leave the command window open or close it.)

> 🔒 Your login is stored **only on your own computer** and is never sent anywhere. No one else can see your information.

### 3. Give it your first task

1. After connecting, a short **3-page tour** appears. Read it and click "Start".
2. A **"My workspace"** is created for you automatically — you don't have to pick a folder.
3. **Click one of the cards** (e.g. "Summarize meeting notes", "Make an intro page"), or just **type what you want** in plain sentences and send it.
4. In the middle **office view**, the agents start dividing up and doing the work.
5. When results are ready, review **"Here's what will change"** and click **Approve**. Nothing is changed until you approve.

### Frequently asked questions

**Where are the files it makes?**
On your PC: `Your user folder → .agent-deck → workspaces → [workspace name]`. Everything the app produces is saved there as real files.

**It says "Git is not installed…"**
Creating or editing files needs a small free program called Git. Download it from [git-scm.com](https://git-scm.com/download/win), install it by clicking **"Next"** with the default settings, then reopen Agent Deck. (Reading, research and summary tasks work fine without Git.)

**Does it cost money?**
It runs on **your own Claude subscription**, so there's **no extra charge** beyond what you already pay for Claude.

**Can other people use it too?**
Yes. Each person installs it on their own computer and connects their own Claude account. Your tasks and information are **never shared** — everything runs privately on each person's own PC.

**Updates?**
The app checks for new versions and lets you know automatically.

---

## 🇰🇷 한국어

Agent Deck은 Windows 데스크탑 앱입니다. 하고 싶은 일을 평범한 말로 적어주면, **내 Claude 구독**을 이용해 대신 처리해 줍니다 — 코딩은 전혀 필요 없어요.

### 준비물 (딱 두 가지)

1. **Windows 10 또는 11** 컴퓨터
2. **Claude 구독** (Pro 또는 Max) — [claude.ai](https://claude.ai)에서 로그인되는 계정이면 됩니다

> Node.js 같은 기술적인 건 따로 설치할 필요 없어요. 설치 파일 안에 다 들어 있습니다.

### 1. 내려받기 & 설치

1. **[최신 릴리스](https://github.com/jvvv94/agent-deck-releases/releases/latest)** 로 가서 **`Agent Deck_x.y.z_x64-setup.exe`** 파일을 다운로드합니다.
2. 내려받은 파일을 더블클릭하세요.
   - **파란색 "Windows의 PC 보호" 창이 뜨면?** 아직 정식 인증서를 등록하기 전이라 뜨는 안내예요(바이러스가 아닙니다). **"추가 정보"** 를 누른 뒤 **"실행"** 버튼을 누르면 됩니다.
3. 설치는 자동으로 진행되고 **관리자 권한도 필요 없어요.** 끝나면 바탕화면·시작 메뉴에 **Agent Deck** 아이콘이 생깁니다.

### 2. 처음 켜기 & Claude 연결

1. **Agent Deck**을 실행합니다.
2. 첫 화면에서 **"구독 연결하기"** 버튼을 누르세요.
3. 검은 **명령창**이 하나 열리고, 이어서 **웹 브라우저**에 Claude 로그인 화면이 나옵니다.
   - 평소 [claude.ai](https://claude.ai)에서 쓰던 계정으로 로그인하세요.
   - 로그인이 끝나면 앱 화면이 **자동으로 넘어갑니다.** (명령창은 그냥 두거나 닫아도 돼요.)

> 🔒 로그인 정보는 **내 컴퓨터에만** 저장되고 외부로 전송되지 않아요. 다른 사람은 내 정보를 볼 수 없습니다.

### 3. 첫 작업 시켜보기

1. 연결되면 **간단한 사용법 안내**가 3장 나와요. 읽고 "시작하기"를 누릅니다.
2. **"내 작업 공간"** 이 자동으로 만들어져 있어요 — 폴더를 직접 고를 필요가 없습니다.
3. 오른쪽에서 **카드 하나를 클릭**하거나(예: "회의록 요약", "소개 페이지 만들기"), 하고 싶은 일을 그냥 문장으로 적어서 보내세요.
4. 가운데 **사무실 화면**에서 에이전트들이 일을 나눠서 처리하기 시작합니다.
5. 결과가 나오면 **"이렇게 바뀌어요"** 를 확인하고 **승인**하세요. **승인하기 전에는 아무것도 바뀌지 않아요.**

### 자주 묻는 질문

**Q. 만든 파일은 어디에 있나요?**
`내 PC → 사용자 폴더 → .agent-deck → workspaces` 안, 작업 공간 이름의 폴더에 있어요. 앱에서 만든 결과물이 그대로 파일로 저장됩니다.

**Q. "Git이 설치되어 있지 않아…"라는 안내가 떠요.**
파일을 만들거나 고치는 작업에는 Git이라는 작은 무료 프로그램이 필요해요. [git-scm.com](https://git-scm.com/download/win)에서 내려받아 **기본 설정 그대로 "다음"만 눌러 설치**한 뒤 Agent Deck을 다시 켜면 됩니다. (읽기·조사·요약 작업은 Git 없이도 돼요.)

**Q. 비용이 드나요?**
내 **Claude 구독**으로 돌아가므로 **추가 요금 없이** 구독 범위 안에서 사용됩니다.

**Q. 다른 사람 컴퓨터에서도 되나요?**
네. 각자 자기 컴퓨터에 설치하고 자기 Claude 계정으로 연결하면 돼요. 서로의 작업이나 정보는 **절대 공유되지 않습니다** (각자 자기 PC에서만 돌아가요).

**Q. 업데이트는요?**
앱이 새 버전을 자동으로 확인하고 알려줍니다.
