---
title: 여행경로 개인정보 처리방침
permalink: /privacy/
---

# 여행경로 개인정보 처리방침

시행일: 2026년 10월 28일

여행경로(이하 "앱")는 이용자의 개인정보를 소중히 다루며, 이 방침은 앱이 어떤 정보를 어떻게 처리하는지 설명합니다.

## 1. 처리하는 정보와 목적

| 정보 | 목적 | 저장 위치 |
|---|---|---|
| 위치 정보(정확한 위치) | 여행 동선 기록(고른 기준(100m · 300m · 1km · 행정구역)만큼 이동할 때 장소 기록, 행정구역 기준이면 지역 이름 확인을 위해 Apple 지도 서비스에 위치를 보냄) | 이용자 기기(iPhone·iPad·Apple Watch), iCloud 동기화를 켜면 이용자 본인의 iCloud |
| 여행 이름·장소·메모 | 여행 보기·편집·공유 | 이용자 기기, iCloud 동기화를 켜면 이용자 본인의 iCloud |
| 구매 내역 | 광고 제거 이용권 확인 | Apple(App Store)이 처리, 앱은 기기에서 확인만 함 |
| 광고 식별자(IDFA) 등 광고 관련 정보 | 광고 표시(공유 시) | Google AdMob이 수집·처리 |

앱 개발자는 별도의 서버를 운영하지 않으며, 위치 정보와 여행 기록을 개발자에게 전송하거나 수집하지 않습니다.
iPhone과 Apple Watch 사이의 여행 기록 동기화는 Apple의 기기 간 통신(WatchConnectivity)으로만 이루어집니다.
설정에서 iCloud 동기화를 켜 두면(기본값: 켬) 여행 기록이 이용자 본인 Apple ID의 iCloud 개인 데이터베이스(CloudKit)에 저장되어 같은 Apple ID의 기기 사이에서 동기화됩니다. 이 데이터는 Apple이 보관하며 개발자는 열람할 수 없습니다. 설정에서 언제든 끌 수 있습니다.
기록을 시작하기 전에 같은 개발자의 여행 앱(여행 계획 · 여행 사진 정리)의 여행 계획에 연결하면, 같은 개발자의 여행 앱끼리 이용자 기기(App Group)와 이용자 본인의 iCloud 개인 데이터베이스 안에서만 여행 계획과 방문 기록(방문한 계획 장소 · 도착 · 떠난 시각)을 주고받습니다. 개발자나 다른 사람에게 전송되지 않으며, 여행을 지우면 공유한 방문 기록도 지워짐으로 표시됩니다.

## 2. 위치 정보

- 이용자가 "경로 기록 시작"을 누른 때부터 "기록 종료"를 누를 때까지만 위치를 사용합니다.
- 앱을 닫거나 화면이 꺼져도 기록이 이어지도록 "항상 허용" 권한을 요청할 수 있습니다.
- 위치 권한은 기기의 설정 > 개인정보 보호 및 보안 > 위치 서비스에서 언제든 변경할 수 있습니다.

## 3. 광고와 추적

- 광고 제거 이용권이 없는 경우 지도 파일을 공유할 때 Google AdMob 광고가 표시됩니다(설치 후 3개월은 표시되지 않음).
- 앱은 맞춤형 광고를 위해 App Tracking Transparency로 추적 허용 여부를 묻습니다. 허용하지 않아도 모든 기능을 사용할 수 있으며, 이때는 비개인화 광고가 표시됩니다.
- Google의 정보 처리 방식: https://policies.google.com/technologies/partner-sites

## 4. 제3자 제공

앱은 위 3항의 광고 SDK(Google AdMob)를 제외하고 이용자 정보를 제3자에게 제공하지 않습니다.
이용자가 직접 공유한 KML·KMZ·GPX 파일은 이용자가 선택한 앱·대상에게 전달됩니다.

## 5. 보관과 삭제

여행 기록은 이용자가 앱에서 삭제하면 기기와 (동기화 중이면) iCloud에서 지워집니다. 앱만 삭제하면 iCloud 사본은 남으며, 설정 > Apple ID > iCloud > 저장 공간 관리에서 지울 수 있습니다.

## 6. 아동

앱은 만 14세 미만 아동의 개인정보를 의도적으로 수집하지 않습니다.

## 7. 문의

개인정보 관련 문의: https://github.com/yjinchoi/trip-route-site/issues (GitHub 이슈)

## 8. 변경

이 방침이 바뀌면 앱 업데이트 또는 이 페이지를 통해 알립니다.

---

# TripRoute (여행 경로) Privacy Policy

Effective: October 28, 2026

## Information we handle

- **Precise location** — used only between "Start recording" and "Stop" to record a place each time you move the distance you chose (100 m, 300 m or 1 km) or enter another district. With the district rule, locations are sent to Apple's map service to look up the district name. Stored on your devices and, with iCloud Sync on, in your own iCloud.
- **Trips, places and notes** — stored on your devices and, with iCloud Sync on, in your own iCloud.
- **Purchases** — processed by Apple; the app only checks your entitlement on the device.
- **Advertising identifier and ad data** — collected and processed by Google AdMob to show ads when you share a file.

We run no servers and never receive your location or trips. iPhone–Watch sync uses Apple's WatchConnectivity only.
With iCloud Sync on (the default; turn it off in Settings), trips are stored in your Apple ID's private iCloud database (CloudKit) to sync between your devices. Apple holds this data; the developer cannot access it.
If you link a trip to a plan from the developer's other travel apps (FlexTrip, TripPhoto) before recording, these travel apps exchange trip plans and visit records (planned places visited, arrival and departure times) only on your device (App Group) and in your own private iCloud database. Nothing is sent to the developer or anyone else; deleting the trip marks the shared visit record as deleted.

## Ads and tracking

Without an ad-removal purchase, an AdMob ad is shown when you share a map file (not during the first 3 months).
The app asks for tracking permission via App Tracking Transparency; if you decline, all features still work and ads are not personalised.
See https://policies.google.com/technologies/partner-sites.

## Sharing, retention, children

We share nothing with third parties other than the ad SDK above. Files you share go only where you send them.
Deleting a trip removes it from your devices and, while syncing, from iCloud. Deleting only the app leaves the iCloud copy, which you can remove in Settings > Apple ID > iCloud > Manage Storage. The app is not directed at children.

## Contact

Questions: https://github.com/yjinchoi/trip-route-site/issues (GitHub issues)
