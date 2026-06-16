# Chap. 03. 결제 카드 삭제하기

```{admonition} 지금 무엇을 하나요?
:class: important
OpenAI에 등록해 둔 **신용카드를 빼냅니다.**
카드를 삭제하면 "내 카드가 OpenAI에 등록돼 있다"는 상태가 완전히 사라져서 안심할 수 있습니다.
```

---

## ① "Billing(결제)" 화면으로 가기

**`Billing`**(결제) 화면으로 들어가는 길은 두 가지입니다. **방법 1**을 먼저 해보고, 화면이 다르거나 그 단추가 안 보이면 **방법 2**로 하세요. 둘 중 **아무 방법이나** 결제 화면에 도착하면 됩니다.

### 방법 1. 설정(톱니바퀴)에서 들어가기

오른쪽 위 **설정(톱니바퀴 모양)** 을 누른 뒤, 메뉴에서 **`Billing`**(결제) 을 찾아 누릅니다.

```{figure} ../images/session3_openAI/08_1.checkBillings.png
:width: 100%
:align: center
:name: s3-fig-billing1

방법 1 — 설정(톱니바퀴) 안에서 **Billing**(결제) 을 찾아 들어갑니다.
```

### 방법 2. 화면에서 "Billing"이 안 보일 때

방법 1의 화면이 보이지 않거나 단추를 못 찾겠다면, 아래 사진처럼 **다른 위치의 `Billing`(결제) 글자**를 눌러도 같은 결제 화면으로 들어갑니다.

```{figure} ../images/session3_openAI/08_2.checkBillings.png
:width: 100%
:align: center
:name: s3-fig-billing2

방법 2 — 방법 1로 안 될 때, 여기 보이는 **Billing**(결제) 을 눌러 들어갑니다.
```

```{admonition} 두 방법은 같은 곳으로 이어집니다
:class: tip
방법 1과 방법 2는 **들어가는 입구만 다를 뿐, 도착하는 결제(Billing) 화면은 똑같습니다.** 본인 화면에 보이는 쪽으로 누르면 됩니다.
```

```{admonition} 금액이 $0 으로 보여도 정상입니다
:class: note
지금까지 사용한 적이 없다면 **$0.00** 으로 보일 수 있습니다. 나갈 돈이 없다는 뜻이니 안심하세요.
```

---

## ② "Payment methods(결제 수단)" 열기

결제(Billing) 화면에서 **`Payment methods`**(결제 수단) 를 누르면, 등록된 카드가 나타납니다.

```{figure} ../images/session3_openAI/09.billing.png
:width: 100%
:align: center
:name: s3-fig-billing3

결제 화면에서 **Payment methods**(결제 수단)로 들어갑니다.
```

```{figure} ../images/session3_openAI/10.paymentMethods.png
:width: 100%
:align: center
:name: s3-fig-paymethods

등록된 카드 목록이 보입니다.
```

---

## ③ 카드의 "점 세 개(⋯)" → "Delete(삭제)" 누르기

지울 카드 줄의 오른쪽 **점 세 개(⋯)** 를 누르면 작은 메뉴가 나옵니다.
그중 **`Delete`**(삭제) 를 누르고, 확인 창이 뜨면 한 번 더 **삭제**를 눌러 확정합니다.

```{figure} ../images/session3_openAI/11.deleteCard.png
:width: 100%
:align: center
:name: s3-fig-delcard

카드 오른쪽 **점 세 개(⋯)** → **Delete**(삭제) 를 눌러 카드를 뺍니다.
```

```{admonition} 카드 삭제가 안 될 때
:class: tip
아직 **정산되지 않은 금액**이 남아 있으면 카드 삭제가 막힐 수 있습니다. 이럴 때는 며칠 뒤(정산 후) 다시 시도하거나, 화면 안내에 따라 남은 금액을 먼저 처리하면 됩니다.
```

---

## 🎉 세션 3 완료!

축하합니다. OpenAI 정리를 모두 마쳤습니다.

- ✅ API 키 삭제 — 비밀 열쇠로 나가던 요금을 멈춤
- ✅ 카드 삭제 — 등록된 카드를 완전히 빼냄

```{admonition} 끝까지 따라오시느라 수고하셨습니다
:class: tip
세 개 세션(① GCP 가상 컴퓨터 삭제 · ② GCP 결제계정·카드 삭제 · ③ OpenAI 정리)을 모두 마치면, 클라우드와 AI 서비스에서 **더 이상 새 요금이 나가지 않고 카드도 모두 빠진 상태**가 됩니다.
막히는 부분이 있으면 강사(정한결-hkjeong@solteti.site) 혹은 매니저(이경재-power080900@gmail.com)에게 문의 부탁드립니다.
```
