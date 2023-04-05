# Big-Data-Study
## 2023-04-01 데이터 거버넌스
데이터 관리가 가장 잘 되고 있는 장소 : 은행
이유 돈과 관련되어 있기 때문에

lake - 빅데이터라고 보면 된다

lake에 데이터를 모은다 (막대한 비용이 든다)
그렇다면 왜 빅데이터에 데이터를 모을까?
이유는 이를 분서거하고 새로운 가치를 창출하기 위해서


은행에서 데이터를 구분하는 방법
계정 시스템, DW(정보 시스템), Mart(분석)

은행 단말 시스템, 무신 ATM에서 channel을 통해서 접근하여 계정시스템을 다룬다
분석을 위해서 DW와 같은 정보 시스템을 구축하여 계정시스템에서 정보를 감시한다.

왜 DW를 구축하는가? 그냥 계정 시스템에서 정보를 분석하면 되는거 아닌가?
이유는 계정 시스템은 항상 안정적이여야 한다.
시스템 부하가 걸리면 안되고 시스템 구축 자체가 분석보다는 운영에 초점이 맞춰 제작되었기 때문

DW : 데이터를 모으고 분석을 가기 위한 존재
Mart : 정보를 가공하고 목적별로 분석을 한다

이렇게 DW, Mart를 이용해서 분석을 하다가 BigData System이 생기게 되고 추가가 되었다.

### 메타 데이터란?
정의 - 데이터를 설명하는 데이터, 데이터의 데이터

예를 들어 도서관에서 책을 검색할때 나오는 라벨들도 다 메타데이터에 속한다
최근 NFT를 본다면 Opensea에 메타데이터 항목이 존재
기본적인 항목들도 있지만 상세 항목(attribute)이 존재

RDB -> TABLE -> COLUMN

Class : Table
Attribute : Column

프로그래밍 관점에서 봤을 때 클래스와 Attribute가 메타데이터에 해당한다.

이런 메타 데이터는 관리와 활용의 목적으로 사용된다.

관리적인 측면으로 A라는 용어에 대하여 데이터 타입, 길이 등을 정해두고 설명 데이터를 작성

이런 데이터를 설계 하기 위해서는 전체적인 시스템을 파악하고 있어야 가능하다
통일된 형태를 만들기 위해서 규칙을 정하고 생성하여 관리하는것이 중요하다.

데이터 카탈로그라는 이름으로 구축을 하고
데이터를 보관하고 이를 빠르게 검색하기 위한 시스템

데이터가 전부 다 맞을거 갖기만 관리를 하다보면 생각과 다르게 안맞는 경우가 생각보다 많다


데이터 거버넌스를 하는 이유는 고품질의 데이터를 만들고 유지해서 활용하기 위함으로
최종적인 목표는 이를 통해 돈을 벌기 위해서이다