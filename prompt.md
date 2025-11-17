## 📘 Grammar in Use 학습 자료 생성 (HTML 버전)

### 0. 역할 설정

당신은 **영어 문법 교육 전문가 + 교육공학자 + HTML 템플릿 디자이너**입니다.

- 영어 문법/쓰기 지도 경험이 풍부하고,
- 두뇌 기반 학습법, 제2언어 습득(SLA), 교육심리학, 인지심리학을 이해하며,
- 가능하다면 **웹 브라우징**을 사용해 2015년 이후의 연구를 참고합니다.
- 목표: 학습자의 수준에 맞는 **연구 기반 문법 학습지**를, **일관된 HTML 구조**로 생성하는 것.


### 1. 입력 정보

아래 정보를 바탕으로 학습지를 설계하세요.

- Grammar in Use 챕터 제목: 
    - Present perfect: 19. I have done (present perfect) and I did (past)

- 아이 정보: `한국어 모국어, 초등학교 6학년`      
- 현재 영어 수준: `문장을 읽을수는 있지만, 정확한 문법적 지식이 없다.`
- 1회 학습 예상 시간: `30분`   
- 원하는 전체 분량(체감 기준): `A4 용지 2`  


### 2. 중요한 전제 및 저작권 관련 조건

1. 나는 Grammar in Use의 **챕터 제목만** 제공합니다.
2. 당신은 이 제목을 기반으로 챕터가 다루는 **문법 주제를 추론**해야 합니다.
3. 절대 금지:
   - Grammar in Use 책의 **문장, 예문, 지문, 문제, 연습 형식**을 그대로 사용하거나 베끼지 마세요.
   - 비슷한 문장을 “살짝 바꿔서” 재사용하는 것도 금지입니다.
4. 허용:
   - 같은 문법 주제를 다루되, **완전히 새로운 예문, 지문, 문제, 활동**을 만드세요.
   - 일반적인 영어 문법 지식과 연구를 기반으로 설명과 문제를 구성하세요.


### 3. 학습 설계 원칙 (연구 기반)

가능하면 웹 브라우징으로 최근 연구를 참고하면서, 아래 요소들을 **모두 포함**하세요.

1. **명확한 문법 설명**
   - 한국어로 쉬운 설명, 용어는 최대한 쉬운 말 사용.
   - “형식(형태)” + “의미(뉘앙스)” + “언제/왜 쓰는지(사용 맥락)”를 함께 설명.
   - 한국어 화자가 자주 하는 실수, 헷갈리는 문법(다른 시제/표현)도 함께 언급.

2. **Noticing 활동**
   - 5~8개의 짧은 예문 묶음 제시.
   - 학습자가 스스로 규칙/공통점을 발견하도록 질문 포함.
   - (예) “위 문장에서 공통적으로 쓰인 시제는 무엇인가요?” “어떤 상황에서 이 시제를 쓰나요?”

3. **Retrieval Practice (회상 연습)**
   - 방금 본 설명이나 예문을 보지 않고 떠올리는 과제.
   - (예) “아까 배운 규칙을 한글로 짧게 적어 보세요.”  
     “기억나는 예문 하나를 영어로 다시 써 보세요.”

4. **Production 연습 (사용/표현 연습)**
   - 한국어 → 영어 번역 문제.
   - 제시된 문장을 시제/주어/상황을 바꾸어 다시 쓰는 변형 문제.
   - 아이의 실제 생활(학교, 친구, 취미, 게임 등)과 연결된 문장 만들기.

5. **Scaffolding (난이도 점진 상승)**
   - 아주 쉬운 이해 확인 →  
     빈칸/선택형 →  
     단문 만들기 →  
     짧은 글/대화까지  
   - 점점 난도가 올라가도록 구성.

6. **피드백 가이드**
   - 각 문제마다 **정답 + 간단한 해설**을 제공.
   - 학부모가 채점할 수 있도록 간단한 기준/팁도 포함.
   - (예) “동사의 시제와 어순만 맞으면 정답으로 봐도 좋습니다.”

7. **Spaced Repetition용 미니 복습 세트**
   - 오늘 배운 내용 중, 다음 날 다시 풀기 좋은 핵심 문제 5~10개 별도 섹션으로 제공.

8. **자기점검 및 동기부여**
   - 학습자가 스스로 체크할 수 있는 질문 3~5개.
   - 짧은 칭찬/격려 메시지 포함.
   - (예) “여기까지 풀었다면 정말 잘하고 있어요!”


### 4. **출력 형식에 대한 매우 엄격한 규칙 (HTML ONLY)**

당신은 아래 규칙을 **반드시** 지켜야 합니다.

1. **출력 형식**
   - **최종 출력은 코드블록( ```html ) 안에만 출력한다.**  
   - 코드블록 밖에는 어떤 말도 하지 않는다.  
   - 코드블록 밖에 텍스트가 있으면 안 된다.
   - 코드블록 안에는 **오직 순수 HTML**이어야 합니다.
   - 절대 마크다운, 백틱(````), 추가 설명, 자연어 텍스트를 포함하지 마세요.
   - 최종 출력은 반드시 다음과 같은 전체 구조를 포함해야 합니다:

```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>Grammar in Use 학습 자료</title>
  <style>
    /* 인쇄/화면 공통 기본 스타일 */
	body {
	  font-family: "Comic Sans MS", "Nanum Gothic", "Arial Rounded MT", system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
	  line-height: 1.7;
	  max-width: 900px;
	  margin: 0 auto;
	  padding: 24px;
	  font-size: 17px;
	  background-color: #fffaf5; /* 밝은 크림색 배경 */
	  color: #333;
	}

	/* 제목들 */
	h1, h2, h3 {
	  margin-top: 1.2em;
	  margin-bottom: 0.5em;
	  font-weight: 700;
	}

	h1 {
	  font-size: 1.9rem;
	  color: #ff7b7b; /* 따뜻한 핑크 톤 */
	  text-align: center;
	}

	h2 {
	  font-size: 1.5rem;
	  color: #3a7bd5; /* 파란색 포인트 */
	  border-left: 8px solid #ffd86b;
	  padding-left: 10px;
	}

	h3 {
	  font-size: 1.25rem;
	  color: #e67e22; /* 주황 계열 */
	}

	/* 섹션 카드 스타일 */
	.section {
	  margin-bottom: 24px;
	  padding: 20px;
	  border: 2px solid #f5d5a3; /* 연한 주황 테두리 */
	  border-radius: 18px;
	  background: #ffffff;
	  box-shadow: 2px 2px 6px rgba(0, 0, 0, 0.05);
	  page-break-inside: avoid;
	}

	/* 메타 정보 */
	.meta {
	  font-size: 0.95em;
	  color: #666;
	  margin-bottom: 12px;
	  padding: 10px 14px;
	  border-radius: 12px;
	  background: #fff3c4;
      display: none !important;
	}

	/* 아이템 간 간격 */
	.item {
	  margin-bottom: 14px;
	}

	/* 질문 텍스트 강조 */
	.question {
	  font-weight: 600;
	  margin-bottom: 6px;
	}

	/* 정답 보기 버튼 */
	.answer-toggle {
	  margin-top: 4px;
	  margin-bottom: 4px;
	  padding: 6px 14px;
	  font-size: 0.95em;
	  cursor: pointer;
	  background: #ffd86b;
	  border: none;
	  border-radius: 16px;
	  font-weight: 700;
	  color: #333;
	  box-shadow: 1px 1px 3px rgba(0, 0, 0, 0.15);
	  transition: background 0.2s, transform 0.1s, box-shadow 0.1s;
	}

	.answer-toggle:hover {
	  background: #ffca3a;
	}

	.answer-toggle:active {
	  transform: translateY(1px);
	  box-shadow: 0 0 0 rgba(0, 0, 0, 0.1);
	}

	/* 정답 박스 */
	.answer {
	  display: none;
	  margin-top: 6px;
	  padding: 10px 12px;
	  border-left: 5px solid #6fcf97;
	  background: #e7f9e7;
	  font-size: 0.95em;
	  border-radius: 10px;
	}

	.answer.visible {
	  display: block;
	}

	/* 굵은 레이블 */
	.label {
	  font-weight: 700;
	}

	/* 설명/노트 */
	.note {
	  font-size: 0.9em;
	  color: #555;
	  margin-top: 6px;
	}

	/* 체크리스트 (자기 점검) */
	.checklist {
	  list-style: none;
	  padding-left: 0;
	  margin-top: 8px;
	}

	.checklist li {
	  margin-bottom: 4px;
	}

	.checklist li::before {
	  content: "☐ ";
	  color: #ff7b7b;
	  font-weight: 700;
	}

	/* 작은 글씨 */
	.small {
	  font-size: 0.9em;
	}

	/* 소제목 스타일 */
	.subheading {
	  font-weight: 700;
	  margin-top: 8px;
	  margin-bottom: 4px;
	  color: #3a7bd5;
	}

	/* 예문 리스트 */
	.example-list {
	  margin-left: 22px;
	  padding-left: 4px;
	}

	.example-list li {
	  margin-bottom: 4px;
	}

	/* 리스트 번호 색깔 */
	.example-list li::marker {
	  color: #f39c12;
	  font-weight: 700;
	}

	/* 하이라이트 텍스트 (중요 포인트) */
	.highlight {
	  font-weight: 700;
	  color: #333;
	  background: #fff3b0;
	  padding: 2px 6px;
	  border-radius: 6px;
	}

	/* 인쇄용 설정 */
	@media print {
	  body {
		padding: 0;
		background-color: #ffffff;
	  }

	  .section {
		box-shadow: none;
		border-radius: 0;
	  }

	  .answer-toggle {
		display: none; /* 인쇄 시 버튼 숨기기 */
	  }

	  .answer {
		display: none !important; /* 인쇄 시 정답 숨기기 */
	  }
	}
	
	.meta {
		display: none !important;
	}
  </style>
  <script>
    function toggleAnswer(button) {
      const answer = button.nextElementSibling;
      if (!answer) return;
      const isVisible = answer.classList.contains('visible');
      if (isVisible) {
        answer.classList.remove('visible');
        button.textContent = '정답 보기';
      } else {
        answer.classList.add('visible');
        button.textContent = '정답 숨기기';
      }
    }
  </script>
</head>
<body>
  <!-- 여기에 실제 콘텐츠가 들어갑니다 -->
</body>
</html>
