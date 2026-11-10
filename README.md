# skills

AI 코딩 에이전트용 개인 스킬 모음입니다. 각 스킬은 `skills/<스킬이름>/SKILL.md`로 구성되어 있으며, 아래 명령으로 바로 설치할 수 있습니다. SKILL.md 포맷을 지원하는 도구(Claude Code, Cursor 등)에서 사용할 수 있습니다.

## 설치

전체 스킬 설치:

```bash
npx skills add kwon-yongdae/skills
```

스킬을 하나만 설치:

```bash
npx skills add kwon-yongdae/skills@<스킬이름>
```

## 스킬 목록

### git-commit-message

변경 사항(git diff, staged 파일)을 분석해 Conventional Commits 형식의 커밋 메시지를 작성합니다. "커밋 메시지 써줘", "커밋해줘" 같은 요청에 사용합니다.

```bash
npx skills add kwon-yongdae/skills@git-commit-message
```

### kr-business-mail-writer

직장인이 본인 명의로 보내는 업무 메일 초안을 작성합니다. 고정 인사말·맺음말, 호칭 규칙, 날짜 형식, 두괄식 문체를 적용해 바로 발송 가능한 한국어 메일을 만듭니다.

```bash
npx skills add kwon-yongdae/skills@kr-business-mail-writer
```

## 라이선스

MIT License
