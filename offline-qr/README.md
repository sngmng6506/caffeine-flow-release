# 영업용 QR 배포 대장

매장에 나눠 주는 영업용 QR 안내판의 코드·이미지·배포 기록이다. 서비스 쪽 동작(고정 연결, 코드 등록 방법, DB 기준)은 [caffeine-flow의 docs/OFFLINE_QR.md](https://github.com/sngmng6506/caffeine-flow/blob/main/docs/OFFLINE_QR.md)가 기준이다.

> 이 저장소는 공개다. `배포 매장`·`비고` 칸에 적은 내용은 누구나 볼 수 있다.

- 인쇄 주소: `https://caffeine-flow-production.up.railway.app/<코드>`
- 흰색 여백 4모듈, 오류 정정 M. PNG 10개 모두 생성 후 주소 디코딩을 검증했다.
- 서버 배포·DB 등록 확인 전에는 현장에 배포하지 않는다.
- 이미 연결된 코드는 다른 매장에 배포하지 않는다. 매장 삭제 후에도 코드는 재사용하지 않는다.
- 아래 표는 오프라인 배포 기록이다. 실제 등록·배정 여부는 서비스 DB `offline_qr_codes`가 기준이며 빈 칸이 미배정을 보증하지 않는다.

안내판 디자인 시안은 [brand/table-signs](../brand/table-signs/)에 있다.

## 1차 10개

코드는 서비스 저장소의 [1차 발급 목록](https://github.com/sngmng6506/caffeine-flow/blob/main/server/src/constants/offline-qr-batch-001.json)과 대응한다.

| 번호 | 영업용 QR 코드 | QR 이미지 | 배포 매장 | 배포일 | 비고 |
| --- | --- | --- | --- | --- | --- |
| 01 | `flow-zsy2e48u` | <img src="images/flow-zsy2e48u.svg" width="96" alt="flow-zsy2e48u QR"> · [PNG](images/flow-zsy2e48u.png) · [SVG](images/flow-zsy2e48u.svg) | — | — | — |
| 02 | `flow-6p4ens3j` | <img src="images/flow-6p4ens3j.svg" width="96" alt="flow-6p4ens3j QR"> · [PNG](images/flow-6p4ens3j.png) · [SVG](images/flow-6p4ens3j.svg) | — | — | — |
| 03 | `flow-t56vkbxu` | <img src="images/flow-t56vkbxu.svg" width="96" alt="flow-t56vkbxu QR"> · [PNG](images/flow-t56vkbxu.png) · [SVG](images/flow-t56vkbxu.svg) | — | — | — |
| 04 | `flow-3rjns36a` | <img src="images/flow-3rjns36a.svg" width="96" alt="flow-3rjns36a QR"> · [PNG](images/flow-3rjns36a.png) · [SVG](images/flow-3rjns36a.svg) | — | — | — |
| 05 | `flow-w7xwmt5w` | <img src="images/flow-w7xwmt5w.svg" width="96" alt="flow-w7xwmt5w QR"> · [PNG](images/flow-w7xwmt5w.png) · [SVG](images/flow-w7xwmt5w.svg) | — | — | — |
| 06 | `flow-uknyhc4c` | <img src="images/flow-uknyhc4c.svg" width="96" alt="flow-uknyhc4c QR"> · [PNG](images/flow-uknyhc4c.png) · [SVG](images/flow-uknyhc4c.svg) | — | — | — |
| 07 | `flow-e78974jj` | <img src="images/flow-e78974jj.svg" width="96" alt="flow-e78974jj QR"> · [PNG](images/flow-e78974jj.png) · [SVG](images/flow-e78974jj.svg) | — | — | — |
| 08 | `flow-vqs72z62` | <img src="images/flow-vqs72z62.svg" width="96" alt="flow-vqs72z62 QR"> · [PNG](images/flow-vqs72z62.png) · [SVG](images/flow-vqs72z62.svg) | — | — | — |
| 09 | `flow-vgpuv98z` | <img src="images/flow-vgpuv98z.svg" width="96" alt="flow-vgpuv98z QR"> · [PNG](images/flow-vgpuv98z.png) · [SVG](images/flow-vgpuv98z.svg) | — | — | — |
| 10 | `flow-j3e663jn` | <img src="images/flow-j3e663jn.svg" width="96" alt="flow-j3e663jn QR"> · [PNG](images/flow-j3e663jn.png) · [SVG](images/flow-j3e663jn.svg) | — | — | — |

안내판을 배포하면 해당 줄의 매장·날짜를 기록한다.
