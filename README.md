# nstyle-skills

Skills from **NStyle** for Claude Code. Checklists pulled out of real production work, not theory.

## Install

```
/plugin marketplace add nstyleos/nstyle-skills
/plugin install shorts-composition@nstyle-skills
```

Then just work as usual — the skill loads itself when you are about to shoot or generate something vertical.

## Skills

### `shorts-composition` — Vertical 9:16 composition check

Most framing checklists mix two things that must not be mixed.

|  | Real camera | AI-generated |
|---|---|---|
| Where does the subject go? | **Dead center** | **On a thirds line, not center** |
| Why | A phone's main lens is ~24mm wide. Only the center cell is undistorted — faces near the edge stretch. | There is no lens, so nothing distorts. Composition is free, so use the better one. |

Apply the camera rule to a generated image and you throw away the freedom you have. Apply the generated rule to a phone shot and you hand someone a bulging face.

**The skill asks which branch you are in first**, then gives you the checklist for that branch, plus a pre-publish gate that catches the failures that actually ship: cropped heads, cut joints, a horizon line behind someone's neck, and anything important sitting in the lower fifth where the Shorts/Reels UI covers it.

Also included: why *"cropping 16:9 down to 9:16"* is the wrong fix, and why a face reference alone does not stop a generated subject from changing size between shots.

---

## 한국어

**세로(9:16) 구도 점검 스킬.** 숏폼·릴스·틱톡용 이미지나 영상을 **찍거나 생성하기 전에** 돌립니다.

핵심은 하나입니다 — **실사 촬영과 AI 생성은 구도 규칙이 서로 반대입니다.**

- **실사**: 얼굴을 **정중앙**에. 폰 메인 렌즈가 24mm 광각이라 가장자리에 놓인 얼굴은 늘어납니다. 이건 렌즈의 제약이라 구도보다 우선합니다.
- **AI 생성**: 주제를 **삼분할선**에. 렌즈가 없으니 왜곡도 없고, 그래서 더 나은 구도를 쓸 수 있습니다.

이 둘을 섞어 쓰는 것이 가장 흔한 실수입니다. 스킬은 **어느 쪽인지 먼저 묻고** 그에 맞는 체크리스트를 줍니다.

발행 전 게이트도 포함됩니다 — 잘린 머리, 무릎·발목·허리에서 끊긴 관절, **목 뒤를 지나가는 수평선**, 그리고 숏폼 UI가 덮어버리는 **하단 1/5**에 중요한 게 들어간 경우.

> 세로 생성 규칙은 실제 사고에서 나왔습니다. 16:9 원본을 크롭해 쇼츠를 만들다가 얼굴이 계속 잘렸고,
> 해답은 더 나은 크롭이 아니라 **처음부터 9:16으로 생성하는 것**이었습니다.
> **짤림은 증상이고, 병은 구도의 부재였습니다.**

사례와 그림으로 풀어 쓴 글: [쇼츠 만들면 얼굴이 잘리는 이유 — 세로 영상 구도, 실사와 AI는 규칙이 반대입니다](https://www.nstyleos.kr/blog/shorts-composition)

---

## License

MIT — see [LICENSE](LICENSE).

## About

[NStyle](https://www.nstyleos.kr) builds AI operating tools. This repository holds the parts that are useful on their own.
