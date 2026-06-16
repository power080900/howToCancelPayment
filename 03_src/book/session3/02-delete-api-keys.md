# Chap. 02. API 키 삭제하기

```{admonition} 지금 무엇을 하나요?
:class: important
OpenAI에 만들어 둔 **API 키(비밀 열쇠)** 를 삭제합니다.
열쇠를 지우면, 그 열쇠를 쓰던 프로그램이 더 이상 작동하지 않으므로 **그쪽으로 나가던 요금이 멈춥니다.**
```

---

## ① 왼쪽 메뉴에서 "API keys" 누르기

관리 페이지 **왼쪽 메뉴**에서 **`API keys`**(API 키) 를 찾아 누릅니다.
그러면 내가 만든 열쇠들의 목록이 나옵니다.

```{figure} ../images/session3_openAI/05.selectAPIKeys.png
:width: 100%
:align: center
:name: s3-fig-apikeys

왼쪽 메뉴에서 **API keys** 를 누르면 만들어 둔 열쇠 목록이 보입니다.
```

```{admonition} 메뉴가 영어로만 보여요
:class: tip
OpenAI 관리 페이지는 영어로 되어 있습니다. **`API keys`** 라는 **글자 모양**만 기억해서 같은 글자를 찾아 누르면 됩니다. 보통 왼쪽 메뉴 목록에 있습니다.
```

---

## ② 지울 열쇠의 "휴지통(🗑)" 누르기

목록에서 삭제할 열쇠 줄의 **오른쪽 끝**에 있는 **휴지통 모양(🗑)** 을 누릅니다.

```{figure} ../images/session3_openAI/06.deleteAPIKeys_01.png
:width: 100%
:align: center
:name: s3-fig-delapi1

지울 열쇠 줄 오른쪽의 **휴지통 모양**을 누릅니다.
```

```{admonition} 열쇠가 여러 개라면
:class: note
목록에 열쇠가 여러 줄 있다면, **각 줄마다 휴지통을 눌러** 하나씩 삭제하면 됩니다. 모두 지워야 완전히 정리됩니다.
```

---

## ③ 확인 창에서 "Delete(삭제)" 누르기

"Delete API key?"(API 키를 삭제할까요?) 라는 확인 창이 뜹니다.
빨간색 **`Delete`(삭제)** 또는 **`Revoke`(해지)** 단추를 눌러 확정합니다.

```{figure} ../images/session3_openAI/07.deleteAPIKeys_02.png
:width: 70%
:align: center
:name: s3-fig-delapi2

확인 창에서 빨간색 **Delete**(삭제) 단추를 누릅니다.
```

```{admonition} 삭제한 열쇠는 되살릴 수 없어요
:class: warning
한 번 삭제한 API 키는 **다시 복구할 수 없습니다.** 하지만 우리가 원하는 것은 "완전히 정리"이므로, 더 이상 쓰지 않는 열쇠라면 그대로 삭제하면 됩니다.
```

---

열쇠를 모두 지웠다면, 마지막으로 다음 페이지에서 **등록된 카드까지 삭제**해 봅시다.
