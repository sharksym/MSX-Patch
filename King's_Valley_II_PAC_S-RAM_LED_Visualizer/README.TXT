----------------------------------------------------------------
King's Valley II - PAC S-RAM & LED Visualizer patch (2026-05-31)
  By Yeongman Seo <sharksym@hitel.net>
----------------------------------------------------------------


@ 원본 롬파일

King's Valley II - The Seal of El Giza (1988)(Konami)(JP)[RC-761].rom
SHA1 = 5ec8811254dc762c6852289a08acf22954404f0d
MD5  = dfcaf859e699f8995d054622c5a561ba


@ PAC S-RAM 패치

파일명: VALLEY2_PAC_S-RAM.ips

유저 입력(패스워드) 방식의 세이브/로드를 PAC S-RAM 세이브/로드로 변경해줍니다.

로드   -> 바뀐 시작메뉴의 'PAC LOAD'로 데이터를 로드합니다.
세이브 -> 스테이지 클리어 시 진행상태, HI-SCORE 및 SCORE가 자동으로 세이브됩니다.

참고)
본체에 PAC S-RAM이 존재하지 않으면, 메인램을 이용하며 세이브/로드가 가능합니다.
이 경우, 전원을 끄면 데이터가 사라집니다.


@ LED Visualizer 패치

파일명: VALLEY2_LED_Visualizer.ips

PAC-V 또는 XII-V를 위한 비주얼라이어를 추가합니다.
PSG 3채널 + SCC 5채널을 표시합니다.


@ 사용법

Luna IPS 등의 패치 툴을 이용하여, 원본 롬파일에 *.ips 파일을 적용합니다.
두 패치를 모두 적용할 수 있습니다. (순서 상관없음)

패치 적용 후, 롬 파일의 사이즈가 변하지 않습니다.
