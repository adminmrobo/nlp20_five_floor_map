# 표지 지시문 — 01 말을 숫자로 바꾸는 20가지 방법

| 항목 | 내용 |
|---|---|
| 키 · 판 | cover_nlp20 · L (16:9, 1920 이상) |
| 그림체 | 16비트 RPG 픽셀아트 (굵은 어두운 외곽선, 2~3단 명암) — 일러스트풍 금지 |
| 장소 (앵커 D) | 낮의 연구실 안뜰. 흰 벽, 큰 창, 가운데에 5층짜리 작은 연구동 모형 |
| 주제 은유 | 층마다 다른 색 창문이 켜진 5층 건물(아래층 종이 쪽지 → 위층 빛나는 말풍선 모양 무늬, 글자 없음) |
| 네 캐릭터 포즈 | 박사: 건물 옆에서 지휘봉으로 맨 위층을 가리킴 / 조수 하루: 클립보드를 안고 1층 창을 들여다봄 / 초파리: 왼쪽에서 오른쪽을 보며 돋보기로 2층 창을 의심스럽게 살핌 / 주판봇: 오른쪽에서 왼쪽을 보며 주판을 들고 맨 위층을 올려다봄 |
| 대체 글 (alt) | 낮의 연구실 안뜰, 층마다 색이 다른 5층 건물 모형 앞에 박사·조수 하루·초파리 연구원·주판봇이 모여 있는 픽셀아트 표지 |
| 앞 표지와 다른 점 | 이 프로젝트 첫 NLP 편. 건물(층) 은유로 다른 편의 실험대·대전 구도와 겹치지 않음 |

**참고 이미지 (함께 올리기):** 네 캐릭터 기본 그림 4장 — GitHub `adminmrobo/fruitfly-lab-expressions`의 `images/doctor/E13`, `images/haru/E13`, `images/fruitfly/E13`, `images/jupanbot/E13` (주판봇은 v2 gpt2판).

**Genspark에 붙여 넣기 ↓**
```
웹페이지 맨 위에 거는 표지 그림 1장을 만들어 줘.
- 비율 16:9, 가로 1920px 이상
- 그림체는 반드시 16비트 RPG 픽셀아트 (매끈한 일러스트·3D 렌더 금지)
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, 주판봇)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 배경은 밝은 낮의 연구실 (밤·어둠·네온 금지)
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 떨어진 가운데 영역에, 왼쪽 아래 구석은 밝고 단순하게
아래 영어 프롬프트를 그대로 써 줘.

Website top cover illustration, wide 16:9.
16-bit RPG style pixel art, crisp visible pixels, bold dark outline (#1d1a22), 2–3 tone shading, small highlights. Match the attached reference characters exactly.
Scene: a bright daytime research-lab courtyard, white walls, large windows with natural sunlight, lavender, mint and pink props; in the center a small five-story lab building model, each floor's windows glowing a different soft color (lavender, mint, sky blue, peach, pink), bottom floor showing tiny paper slips, top floor showing glowing speech-bubble shapes (no letters).
All four characters together:
  chibi scientist, thin teal rectangular glasses, spiky black hair with one white streak, small ponytail at the back, white lab coat over black vest and tie, pointing a baton at the top floor;
  girl researcher, long pink hair with two round buns and a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, hugging a clipboard and peeking into the first-floor window;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat over a black vest, black gloves, transparent wings, on the left facing right, inspecting the second floor with a magnifying glass, skeptical;
  boxy beige retro CRT-monitor robot, dark green screen face with mint pixel eyes and mouth, short antenna topped with a red-brown abacus bead, gray segmented arms, two small tank treads, holding a wooden abacus, on the right facing left, looking up at the top floor with excitement.
Visual metaphor of the topic: words climbing a five-floor building, from plain paper slips to glowing speech bubbles.
Composition: keep every face and hand inside the central safe area (12% margin left and right, 10% top, 18% bottom); keep the bottom-left corner plain, bright and simple; the light falls on the five-story building.
Mood: curious, friendly rivalry, the moment before the result.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same four characters, same 16-bit pixel art style and composition. Change only: {고칠 점}. Still no text.`

**받은 뒤:** 1600×900 WebP(220 KB 이하)로 줄여 `cover_nlp20.webp`로 저장 → 페이지 `data-img="cover_nlp20"` 자리의 대체 표지를 `<img class="coverimg">`로 바꿈. 목차 썸네일·공유 미리보기는 같은 그림에서 잘라 씀.
