---
title: BroadcastChannel.close
short-title: close()
slug: Web/API/BroadcastChannel/close
l10n:
sourceCommit: 1f216a70d94c3901c5767e6108a29daa48edc070
---

{{APIRef("BroadCastChannel API")}}

**`BroadcastChannel.close()`** 는 기본 채널에 대한 연결을 종료하여 객체가 가비지로 수집되도록 합니다. 브라우저가 이 채널이 더 이상 필요하지 않다는 것을 알 수 있는 다른 방법이 없으므로 이를 수행하는 데 필요한 단계입니다.

{{AvailableInWorkers}}

## Syntax

```js-nolint
channel.close()
```

## Example

```js
// 채널 연결
const bc = new BroadcastChannel("test_channel");

// postMessage와 같은 추가작업

// 완료되면 채널 연결을 끊음
bc.close();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("BroadcastChannel")}}, the interface it belongs to.
