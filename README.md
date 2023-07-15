# WWDC23-iOS17

### WWDC23 내용을 기반으로 iOS 17에 변경된 사항 정리

<br>

- 지원 기기
  - SE 2세대 이상
  - XR, XS, XS Max
  - 11~14 시리즈
 
<br>

- StoreKit
  - StoreKit SwiftUI Views
    - SwiftUI에서 인앱구매 UI를 편리하게 구현 가능
    - https://developer.apple.com/documentation/storekit/in-app_purchase/storekit_views
  - AppStore Server API
    - get transaction info endpoint 추가로 transaction 관리에 용이해짐
    - https://developer.apple.com/documentation/appstoreserverapi/app_store_server_api_changelog
  - Testing
    - TestFlight
      - 배포 옵션에 TestFlight Internal Only 추가
    - Sandbox
      - Family Sharing(https://www.apple.com/family-sharing/) 테스트 추가
  - AppStore
    - Pre-Order
      - 지역별 Pre-Order 설정 가능
      - https://developer.apple.com/app-store/pre-orders/
      - https://developer.apple.com/videos/play/wwdc2023/10015
    - 앱 소개 A/B Testing 가능
 
<br>

- TipKit
  - 개요
    - https://developer.apple.com/videos/play/wwdc2023/10229/
    - educational moments에 사용하도록 소개됨
    - popover, inline view 두 가지 형태로 표현 가능
  - rules
    - 언제 Tip을 보여줄지에 대한 규칙
    - parameter-based
      - state or boolean
      - bool 값, event counts, date 등을 이용해 Rule 설정 가능
    - event-based
      - user actions
      - button action, view onAppear 등에 추가

<br>

- SwiftData
  - CoreData 프레임워크의 기능들을 SwiftUI, Combine에 적합하게 개선한 프레임워크로 생각됨
    - Compatible with Core Data
      - SwiftData uses the proven storage architecture of Core Data, so you can use both in the same app with the same underlying storage. When you’re ready, Xcode can convert your Core Data models into classes for use with SwiftData.(애플 소개 문구에서 발췌)
  - https://developer.apple.com/videos/play/wwdc2023/10187/
  - https://developer.apple.com/documentation/SwiftData
 
<br>

- 그 외 주요 내용
  - SharePlay
    - AirDrop 방식 추가
    - https://developer.apple.com/videos/play/wwdc2023/10239/
  - Safari
    - Extensions
      - https://developer.apple.com/videos/play/wwdc2023/10119
  - Apple Pay
    - Apple Pay Later
      - 애플페이 무이자 할부 기능
  - Widgets
    - 아이폰 StandBy mode 추가 → 잠금화면(StandBy mode)에 위젯 추가 가능
  - ShortCuts
    - https://developer.apple.com/videos/all-videos/?q=shortcuts
  - PassKeys
    - https://developer.apple.com/videos/all-videos/?q=passkeys
  - Accessibility
    - Assistive Access
      - https://developer.apple.com/videos/play/wwdc2023/10032/
  - MapKit
    - for SwiftUI
      - https://developer.apple.com/videos/play/wwdc2023/10043/
  - ML & Vision
    - https://developer.apple.com/videos/ml-vision/
   
<br>
<br>
    
