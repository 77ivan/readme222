# IAMGithub

RxSwift와 MVVM를 사용한 Github Repository Star 검색 클라이언트 애플리케이션

<br>

## Configuration

- OAuth
- User Infomation
- User Repository
- User Starred Repository
- Search Repository

<br>

## Reference

- [Github API](https://docs.github.com/en/rest)

<br>

## Library

- [RxSwift, RxCocoa](https://github.com/ReactiveX/RxSwift)
- [RxDataSources](https://github.com/RxSwiftCommunity/RxDataSources)
- [SnapKit](https://github.com/SnapKit/SnapKit)
- [Kingfisher](https://github.com/onevcat/Kingfisher)
- [Moya](https://github.com/Moya/Moya)
- [Then](https://github.com/devxoul/Then)
- [Toast](https://github.com/scalessec/Toast-Swift)
- [KeychainSwift](https://github.com/kishikawakatsumi/KeychainAccess)

<br>

## Commit Message Rule

- feature: 새로운 기능 추가
- fix: 버그 수정
- docs: 문서 관련
- refactor: 코드 리팩토링
- test: 테스트 코드
- chore: 빌드 업무 수정, 파일 수정 등..
- add: 추가
- edit: 수정
- delete: 삭제
- rename: 이름 변경
- correct: 문법 오류, 타입 변경, 오타 등..

<br>

## Style Guide


- 빈 줄
   
   - 빈 줄에는 공백이 포함되지 않도록
    
   - 모든 파일은 빈 줄로 끝나도록


- 네이밍
    
    - Action 함수의 네이밍은 '주어 + 동사 + 목적어' 형태
        
        - Tap(눌렀다 뗌)은 `UIControlEvents`의 `.touchUpInside`에 대응
        
        - Press(누름)는 `.touchDown`에 대응
        
        - *will~*은 특정 행위가 일어나기 직전이고, *did~*는 특정 행위가 일어난 직후
       
        - *should~*는 일반적으로 `Bool`을 반환하는 함수에 사용

- 줄바꿈

    - 함수 정의가 최대 길이를 초과하는 경우에는 줄바꿈
     ```swift
    func collectionView(
      _ collectionView: UICollectionView,
      cellForItemAt indexPath: IndexPath
    ) -> UICollectionViewCell {
      // doSomething()
    }
    ```
    
    - 함수를 호출하는 코드가 최대 길이를 초과하는 경우에는 파라미터 이름을 기준으로 줄바꿈
    ```swift
    let actionSheet = UIActionSheet(
      title: "정말 계정을 삭제하실 건가요?",
      delegate: self,
      cancelButtonTitle: "취소",
      destructiveButtonTitle: "삭제해주세요"
    )
    ```







