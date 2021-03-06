#레이어 기능 소개

>> Layair 엔진은 주로 엔진 라이브러리와 레이어 아이디의 두 핵심 부분을 포함한다.
>>
> LayaCloud LayaNative 엔진의 생태그룹 부분



##Layaiair 2.0 엔진 라이브러리 기능

Layaiair 2.0 엔진은 1.0의 기존 기능을 유지할 뿐만 아니라:

요정, 벡터, 텍스트, 부 텍스트, 비디오, 애니메이션, 뼈, 오디오, 영상, 필터, 이벤트, 시간, 시간, 네트워크, UI 시스템, TiledMap, prtocol 등 API

또 box2d 물리 엔진, 구성 지원, 150여 개의 3D 기능, 예를 들면:

새로 늘고 있는 주요 공식 소재는 PBRStandardmaterial, PBRSpecularmaterial, Unlitmaterial 소재 등을 포함한다.

무늬 면에서는 여러 가지 무늬 인자 설정 (mipmap, format, wrapModeU, wrapModeV, filterModerMode, anisollevel) 을 추가하여 픽셀 인터페이스를 업그레이드, GPU 텍스트 압축합니다.

애니메이션 측은 애니메이터 애니메이션 융합 기능 crossFade, 새롭게 애니메이션 다층 혼합 재생, 애니메이션 업데이트 메세지 조정, 대폭 감소 메모리 및 애니메이션 유창도 표현, 다양한 소재 속성 애니메이션

개발2D, 3D, VR 제품 개발을 지원하며 Canvas 와 WebGL 모드를 지원하며 HTML5, Flash, APP(IOS, 안탁)의 마이크로폰, QQ 를 다양한 버전으로 발표합니다.


##Layair 2.0 IDE 기능

Layair 2.0 IDE 는 주로 포함되어 있습니다.`项目管理`、`代码开发编辑器`、`可视化编辑器`、`第三方工具链支持工具`등

그 중 주요 기능 포함:

##-코드 개발UI 와 장면 편집기
##-장면 관리(2.0 신규)입자 편집기
##-애니메이션 편집기물리 편집기 (2.0 새로 증가)
##-구성 지원 (2.0 증가)3D 지원 (2.0 증가)
##- LayaCloud 프로젝트 지원 (2.0 신규 증가)스크립트 확장
##예약APP 포장
##- JS 혼동 및 압축제3자 도구 체인 변환 도구 (Unity3D, TiledMap, Spine, 용골 …)



Laya2.0 IDE 호환 Layaiaiaia 1.x 버전의 쓰기, 2d 항목에서 크게 변경할 필요는 없을 경우 기존 항목을 2.0 엔진 (업그레이드 전에 백업)

Laya2.0 ID는 마운트 구성 요소 스크립트와 장면 관리를 위한 방식으로 개발하고, ide 에서 편집 장면과 페이지 구성 요소를 추가하여 프로젝트 개발에 더욱 유리하고, 프로그램, 미술, 기획의 협동작업을 통해, 처음 접촉한 레이야의 개발자에게 더욱 우호적이다.



##LayaNative 기능

LayaNative Layaia 엔진은 모바일 원생 App 의 개발, 테스트, 발표된 완전한 개발 해결 방안에 국한되지 않는다.LayaNative LayaPlayer 를 핵심으로 실행할 때의 기초에 반사 메커니즘, 채널 대합 방안을 이용하여 개발자는 원생 App 에서 2차 개방과 채널 대합을 진행하고 테스트 도구, 구축 도구를 제공해 html5 프로젝트 패키지, 원생 Appp을 배포해 편리하게 한다.

####LayaNative2.0 코드 재구성을 거쳐 성능이 1.0버전에 비해 높아졌다.

1, 레이야네이티브 1.0

1244단
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1%%%%%%%%%%
124대 IOS

2, 국내 기타 통용 runtime 엔진 대비

1244단
1------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
124사이드 (Android) 가 85%%%%%%%%%%%%%%%%%%%
240%%%%%%%%%%%%%%

####확장 방면

1, LayaNative 2.0 지원 싱글 라인과 두 패턴, 개발자는 자신의 프로젝트의 실제 테스트 결과에 따라 어떤 모드를 선택하기로 결정했다.

- 단일 라인 모드: JS 와 렌더가 한 라인으로 운행한다.

동작 지연 없음 (예: touch, 버튼)
- 단점: 성능 이선정 패턴.

- 2선 패턴: JS 와 렌더가 각자의 라인을 운영하고 있다.

--장점: 성능은 단선 버전보다 높다.
- 단점: 조작은 반폭, 최대 프레임의 지연(예를 들면: touch, 버튼)이다.

2. 현카드 무늬 압축을 지원해 보카시마 효율을 높일 뿐만 아니라 현존의 점용도 줄일 수 있다.

3, 최적화된 2차 개발은 더 쉽게 이해되고 개발자가 사용하기 편리하다.

####사용성 면에서 더욱 편리한 디버그 기능을 제공한다

**앤드로이드 플랫폼은 자바스크립트 디버깅**

LayaNative1.0 버전에서 디버그 항목의 자바스크립트 코드 코드만 사용할 수 있습니다.layaNative2.0 버전에서 Chrome 브라우저 디버깅 자바스크립트 코드를 본격 지원합니다.Chrome 디버깅에 코드를 단점적으로 첨가하고, 코드 추적 등의 기능을 할 수 있다.

**테스트 App 은 스코드 시작 항목 지원**

개발자가 더 빠른 디버그 개발을 위해 새로운 버전의 테스트 앱은 스코어 시작 App 의 기능을 추가해 디버깅 시 URL 을 입력해야 할 수 있도록 수동적으로 URL을 입력해야 합니다.



##LayaCloud 기능

LayaCloud 는 2.0으로 출시된 구름 서비스 해결 방안으로 개발자 인증(로그인 또는 허가 등), 서버 데이터 액세스 및 읽기, 룸 창건과 관리, 방내방송 동기 등 기초 서비스를 개발합니다.개발자는 서버의 배치와 부하 등에 관심이 없다. LayaCloud 를 통해 제공하는 API 인터페이스를 직접 사용해 빠른 속도로 인터넷 게임을 실현할 수 있다.복잡한 서버 요구를 직면하면 개발자도 클라이언트와 서버 논리 스크립트를 편집하여 LayaCloud 기초 API 에서 제공하지 못한 기능이나 기타 게임 비즈니스 논리를 실현할 수 있다.

LayaCloud 기술 문서 페이지: https://wiki.cloud.layabox.com/





더 자세한 2.0 새 특성 소개는 Layabox 마이크로폰 공중번호를 볼 수 있는 글: htttps://mp.weixin.qqq.com/s/lHI3tCozcfdu 8fZFJ8Xg



개발 과정에서 엔진과 도구가 존재하는 BUG 문제나 동네에 대한 제안: http: ask.layabox.com