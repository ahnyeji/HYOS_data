오픈소스 정의
-------------
The Open Source Definition

Introduction
Open source doesn't just mean access to the source code. The distribution terms of open-source software must comply with the following criteria:

1. Free Redistribution
The license shall not restrict any party from selling or giving away the software as a component of an aggregate software distribution containing programs from several different sources. The license shall not require a royalty or other fee for such sale.

2. Source Code
The program must include source code, and must allow distribution in source code as well as compiled form. Where some form of a product is not distributed with source code, there must be a well-publicized means of obtaining the source code for no more than a reasonable reproduction cost, preferably downloading via the Internet without charge. The source code must be the preferred form in which a programmer would modify the program. Deliberately obfuscated source code is not allowed. Intermediate forms such as the output of a preprocessor or translator are not allowed.

3. Derived Works
The license must allow modifications and derived works, and must allow them to be distributed under the same terms as the license of the original software.

4. Integrity of The Author's Source Code
The license may restrict source-code from being distributed in modified form only if the license allows the distribution of "patch files" with the source code for the purpose of modifying the program at build time. The license must explicitly permit distribution of software built from modified source code. The license may require derived works to carry a different name or version number from the original software.

5. No Discrimination Against Persons or Groups
The license must not discriminate against any person or group of persons.

6. No Discrimination Against Fields of Endeavor
The license must not restrict anyone from making use of the program in a specific field of endeavor. For example, it may not restrict the program from being used in a business, or from being used for genetic research.

7. Distribution of License
The rights attached to the program must apply to all to whom the program is redistributed without the need for execution of an additional license by those parties.

8. License Must Not Be Specific to a Product
The rights attached to the program must not depend on the program's being part of a particular software distribution. If the program is extracted from that distribution and used or distributed within the terms of the program's license, all parties to whom the program is redistributed should have the same rights as those that are granted in conjunction with the original software distribution.

9. License Must Not Restrict Other Software
The license must not place restrictions on other software that is distributed along with the licensed software. For example, the license must not insist that all other programs distributed on the same medium must be open-source software.

10. License Must Be Technology-Neutral
No provision of the license may be predicated on any individual technology or style of interface.

from Open Source Initiative

https://opensource.org/osd



클로즈드 소스 설명
------------------
사유 소프트웨어

“클로즈드 소스”라는 용어는 프로그램의 소스 코드가 공개되지 않는 “비공개 소스”와 혼동될 수 있다. 마이크로소프트의 공유 소스는 소스 코드가 공개되긴 하지만 “오픈 소스”는 아닌 예이다. 다시 말해, “클로즈드 소스”라는 용어를 “오픈 소스”의 반대 개념으로 사용한다면 “공유 소스”는 “클로즈드 소스”의 한 형태에 해당된다.

from Wikipedia
https://ko.wikipedia.org/wiki/%EC%82%AC%EC%9C%A0_%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4

Closed Source

Closed source (or proprietary software) means computer programs whose source code is not published. The source code is not shared with the public for anyone to look at or change. Closed source is the opposite of open source.

from Wikipedia

https://simple.wikipedia.org/wiki/Closed_source

Most companies who sell their software for money make it closed source so people cannot easily change it or copy it for free.

오픈소스 라이센스 소개
----------------------
#오픈소스 SW 개요

오픈소스SW는 소스코드가 공개되어 있는 SW를 말하며, 일반적으로 자유롭게 복제/배포/수정할 수 있다.
오픈소스SW의 대표적인 예로는 Linux 커널 및 아파치 웹서버, FireFox 웹브라우저, MySQL 등이 있다.
전 세계적으로 오픈소스SW는 FSF(Free Software Foundation)의 자유SW(Free Software)를 포함한 넓은 의미로 사용되고 있다.
하지만 자유SW와 오픈소스SW는 역사 및 추구하는 이념 등에서 미묘한 차이가 있다.
1980년대부터 소프트웨어가 거대 부가가치 산업으로 발전하자, 지식재산권 및 라이선스 계약을 통하여 소프트웨어의 복제, 배포, 수정에 제한을 가하려는 움직임이 나타났다.
이런 움직임에 반대하여 리처드 스톨만은 FSF를 설립하고 자유SW(Free Software) 운동을 전개하였다.
그러나 자유SW의 ‘자유(Free)’라는 단어가 일반인들에게 ‘무료’로 인식되고, 엄격한 GPL조항 때문에 상용SW개발에 이용할 수 없어 대다수 기업들이 자유SW운동에 참여하기를 꺼려하자 소스코드 공개에 보다 많은 참여를 이끌어내기 위하여 에릭 레이먼드, 브루스 페런스 등은 '오픈소스 (Open Source)' 라는 새로운 용어를 제안했다.
그리고 이러한 ‘오픈소스’는 1998년 오픈소스SW 활성화 및 오픈소스SW에 대한 인증을 담당하는 OSI (Open Source Initiative)가 결성되면서 널리 사용되기 시작했다. 
OSI는 오픈소스에 해당하는 라이선스의 최소한의 기준을 정의 (Open Source Definition, OSD) 해놓고 이 정의에 따라 인증, 관리 및 촉진시키는 일을 한다.

#오픈소스 SW의 지식재산권과 라이센스
## 1. SW 지식재산권
현재 SW는 다음과 같이 저작권, 특허권, 상표권, 영업비밀 등의 지식재산권에 의해 보호받고 있다.

###저작권
저작권(copyright)은 창작물에 대하여 창작자(저작자)가 취득하는 권리로서 창작의 결과물을 보호 하며, 창작과 동시에 권리가 발생한다. 
따라서 어떤 프로그래머가 특정 SW를 개발하면 컴퓨터 프로그램 저작권이 자동 발생하며, 그 권리는 프로그래머 또는 그가 속한 회사에 부여된다. 
저작권이 있는 저작물의 경우 누구도 저작권자의 허락 없이는 해당 저작물을 쓸 수 없다.
###특허권
특허권(patent)은 발명에 관하여 발생하는 독점적/배타적 지배권으로 법에 정해진 절차에 의해 출원을 하여야 하며, 심사를 통해 부여되는 권리이다. 
특허기술을 사용하기 위해서는 반드시 특허권자의 허락을 얻어야만 한다. 
특허 받은 방식을 구현하는 SW라면 프로그래밍 언어나 소스 코드와 상관없이 특허권자의 명시적인 허락을 받아야 한다.
###상표권
상표권(trademark right)이란 상표권자가 지정상품에 관하여 그 등록상표를 사용할 독점적인 권리로서 일정한 절차에 따라 등록하여야 효력이 발생한다. 
이러한 상표를 사용하기 위해서는 반드시 상표권자의 허락을 얻어야 하며 허락받지 않고 상표를 사용할 경우 처벌을 받게 된다.
상표권을 취득한 SW의 경우 상표를 사용하려면 상표권자의 명시적인 허락을 받아야 한다.
###영업비밀
공개되지 않은 SW의 경우 영업비밀로서 보호를 받을 수 있으며, 공개된 SW라 하더라도 아이디어에 대한 부분은 영업비밀로 보호를 받을 수 있는 가능성이 있다.
단, 영업비밀로서의 SW보호는 널리 공개되어 유통되는 경우에는 보호받기 어렵고, 이를 알지 못하고 사용한 제3자에게 법적으로 문제를 삼을 수 없다.

## 2. 라이센스와 오픈소스 SW
###라이센스의 의의
앞서 언급한 3가지에 의해 보호받으며 저작권자만이 쓸 수 있지만, 권리자가 다른 사람에게 일정한 조건으로 특정 행위를 할 수 있는 권한을 부여할 수 있다. 
이와 같은 권한을 보통 '라이선스(license, 이용허락)' 라고 한다. 
예를 들면 우리가 윈도우즈를 구입하면, SW권리자인 마이크로소프트로부터 윈도우즈XP를 한 대의 컴퓨터에 설치하여 이용할 수 있는 라이선스 (권리)를 받은 것에 불과하다. 
그러므로 윈도우즈 정품을 구입했다고 해서 다른 사람에게 빌려주거나 복제하여 팔 수 없다.

###오픈소스 SW 라이센스
오픈소스SW 라이선스란 오픈소스SW 개발자와 이용자 간에 이용 방법 및 조건의 범위를 명시한 계약이다. 
따라서 오픈소스SW를 이용하기 위해서는 개발자가 규정한 라이선스를 지켜야 하며, 이를 위반할 경우에는 라이선스 위반 및 저작권 침해가 발생하고, 이에 대한 책임을 지게 된다.

이런 오픈소스SW 라이선스는 기본적으로 이용자의 자유로운 사용을 보장하고 있다. 
오픈소스SW가 이와 같은 라이선스를 만들어서 운영하는 이유는 오픈소스SW를 이용하여 개발한 SW에 대해서도 법의 테두리 안에서 소스코드를 공개하도록 하기 위한 것이다.

2017년 05월 현재 오픈소스SW 라이선스의 인증을 관장하고 있는 OSI에 따르면 78개가 있다. 
하지만 실제로 많이 사용되는 라이선스의 개수는 한정되어 있다. 
오픈소스 프로젝트 개발 포털사이트인 Freshmeat (http://freshmeat.net)에 등록된 프로젝트 약 43,722개 중 약 72%가 GPL과 LGPL 라이선스이다.

## 3. 오픈소스 라이센스의 이해와 활용
오픈소스SW는 독점SW(proprietary software)와 동일하게 저작권 등에 의한 법적 보호를 받고 있으며, 이와 같은 권리에 기반하여 오픈소스SW 저작권자는 오픈소스SW 이용자에게 라이선스를 부여한다. 
그러나 오픈소스SW 라이선스는 일반적인 독점SW 라이선스와는 많은 점에서 차이가 있다. 
이를 살펴보면 아래와 같다. 
여기서 라이선시(Licensee)는 라이선스를 받는 자이고, 라이선서 (Licenser)는 라이선스를 부여하는 자이다.

*라이선시는 해당 오픈소스SW를 자유롭게 이용할 수 있다.
*라이선시는 해당 오픈소스SW를 자유롭게 복제할 수 있으며, 일정한 조건하에 재배포할 수 있다.
*라이선시는 해당 오픈소스SW를 자유롭게 수정하여 이용할 수 있으며, 일정한 조건하에 수정된 내용을 재배포할 수 있다.
*라이선시는 해당 오픈소스SW의 소스코드를 자유롭게 획득하고 접근할 수 있다.

오픈소스SW 라이선스는 또한 SW 이용자에게 일정한 의무를 부과한다. 
자세한 내용은 오픈소스SW와 함께 배포되는 라이선스를 통해 알 수 있다. 
해당 오픈소스SW에 대한 라이선스는 주로 소스코드 내부나 홈페이지 등에 명시되어 있다.
이용자가 오픈소스SW 라이선스에서 요구하는 준수사항을 이행하지 않으면 권리자로부터 저작권법 위반(또는 계약 위반)으로 소송을 제기당할 수 있다. 
패소할 경우, SW 배포는 불가능하며 손해 배상을 포함한 책임을 부담할 수 있다. 따라서 라이선스의 의무사항을 명확히 이해하여 이런 상황을 예방해야 한다.
그러나 독점SW 라이선스에서 규정된 의무사항과 비교하면 오픈소스SW 라이선스가 요구하는 내용은 결코 어렵지 않으며, 이를 잘 이해하고 준수하면 독점SW보다 훨씬 비용을 절감할 수 있다. 
또한 몇몇 라이선스만이 독자 개발한 소스코드의 공개를 요구하고 있기 때문에 이를 잘 분석한 후 이용한다면 문제의 발생 소지는 거의 없다고 봐야할 것이다.
따라서 오픈소스SW를 다운로드받아 개발에 적용할 때는 반드시 라이선스의 요구 사항을 확인하여야 한다. 
자체 판단이 불가능할 경우에는 외부 전문가에게 조언을 의뢰하여 개발 시작 전 해당 라이 선스의 요구 사항과 오픈소스SW의 이용목적을 확실히 분석하여야 한다. 
이렇게 하는 것만으로도 충분히 올바르게 오픈소스SW를 최대한 활용할 수 있으며, 나중에 발생할 수 있는 문제들을 사전에 차단할 수 있다.

#오픈소스 라이센스의 구체적 내용

오픈소스SW 라이선스의 의무사항은 각각의 라이선스마다 조금씩 차이가 있지만 크게 나누어 보면 공통적으로 '저작권 관련 문구 유지', '제품명 중복 방지', '서로 다른 라이선스의 SW 조합 시 조합 가능 여부 확인' 등이 있고, 선택적으로는 '소스코드 공개', '특허관련 사항 준수' 등이 있다.

## 1. 공통적 준수사항

###저작권 관련 문구 유지

저작권이란 표현된 결과물에 대해 발생하는 권리이며 저작물의 창작과 함께 자동적으로 부여된다. 
SW의 경우는 소스코드에 프로그램의 이름과 개발자, 버전, 연락처 등을 포함하고 있는 경우가 많으며 이러한 것들은 저작인격권으로 보호받는다.
오픈소스SW는 거의 대부분 소스코드 상단에 개발자 정보와 연락처 등이 기록되어 있으며 개발자 정보를 임의로 수정하거나 삭제하여서는 안된다. 
특히 GPL 등 수정된 결과물을 다시 공개하도록 규정하고 있는 '상호주의(reciprocal)' 라이선스들의 경우 저작인격권으로 보호받기 때문에 소스코드상의 개발자 정보가 수정, 삭제된 채로 외부에 공개되면 저작권 침해문제가 발생할 수 있으므로 주의해야 한다. 
저작권 관련 문구 유지는 쉽게 판단이 가능한 사항이므로 항상 준수하여야 한다.

###제품명 중복 방지

SW의 제품명은 상표권으로 보호받는다. 
따라서 오픈소스SW의 경우에 이와 동일한 이름을 제품명이나 서비스명으로 사용하면 상표권 침해의 문제가 생기게 된다. 
특히 유명한 오픈소스SW일수록 해당 오픈 소스SW의 이름이 상표로 등록되어 있는 경우가 많기 때문에(예: 리눅스) 더욱 조심해야 한다.

###서로 다른 라이선스의 조합

SW를 작성하고자 할 경우 기존에 만들어진 코드를 재사용하거나 결합하는 경우가 많은데, 이러한 때 결합되는 각 코드의 라이선스가 서로 상충되는 경우가 있다. 
이러한 문제를 라이선스의 양립성 (Compatibility) 문제라고 한다. 
서로 다른 라이선스로 배포된 오픈소스SW를 결합하는 경우 반드시 두 개의 라이선스가 서로 호환되는지를 확인하여야 한다.

## 2. 선택적 준수사항

선택적 준수사항은 라이선스에 따라 다르다. 
자세한 사항은 오픈소스 라이선스 가이드의 라이선스별 준수사항 부분(3.2)를 참고하기 바란다.

라이선스
-------------
오픈소스 SW 라이선스 분포도에 나온 라이선스에 대한 설명
 
*GNU General Public License (GPL ; version 2.0과 3.0존재)
(https://opensource.org/licenses/gpl-license)

version 2.0
자유 소프트웨어 재단(OSF)에서 만든 자유 소프트웨어 라이선스다. 
미국의 리처드 스톨만(Richard Stallman)이 GNU-프로젝트로 배포된 프로그램의 라이선스로 사용하기 위해 작성했다.
 
'① 컴퓨터 프로그램을 어떤 목적으로든지 사용할 수 있다. 
② 컴퓨터 프로그램의 복사를 언제나 프로그램의 코드와 함께 판매 또는 무료로 배포할 수 있다. 
③ 컴퓨터 프로그램의 코드를 용도에 따라 결정할 수 있다. 
④ 변경된 컴퓨터 프로그램 역시 프로그램의 코드와 함께 자유로이 배포할 수 있다'라는 네 가지 조항을 명시하고 있다.

대부분의 소프트웨어에 대한 라이선스는 소프트웨어를 공유하거나 수정할 수 있는 자유를 금지하기 위 고안되었다. 
반면에 GNU 일반 공중 라이선스는 자유 소프트웨어를 공유하고 수정할 수 있는 자유를 보장하기 위해 의도되었다. 
즉, 소프트웨어가 사용자 모두에게 자유롭게 이용될 수 있도록 하는 것이다. 
이 일반 공중 라이선스는 자유 소프트웨어 재단의 소프트웨어 대부분을 비롯하여, 저작자가 이 라이선스의 사용을 지정한 기타 모든 프로그램에 적용된다. 
(자유 소프트웨어 재단의 소프트웨어 중 일부는 이 라이선스 대신 GNU 라이브러리 일반 공중 라이선스가 적용된다.) 
누구나 자신의 프로그램에 이 라이선스를 적용시킬 수 있다.
(https://olis.or.kr/license/Detailselect.do?lId=1004&mapCode=010004)
(https://opensource.org/licenses/GPL-2.0)

version 3.0
자유 소프트웨어 재단(FSF)과 이 재단의 GNU 프로젝트에 의해 배포되며 GNU 소프트웨어에 적용되는 공개 소프트웨어의 대표적인 라이선스 체계이다. 
GNU GPL이라고도 하며, 저작권(copyright)의 반대라는 의미로 카피레프트(copyleft)라고도 한다. 
라이선스 사용료나 사용상의 제약 조건을 자유롭게 하여 소프트웨어 유통을 활성화하기 위한 의도에서 출발한 것으로 GNU 소프트웨어로 공개되는 원시 부호는 누구나 변경 또는 일반 공중 라이선스(GPL)로 재배포하고, 이를 이용하여 상업적 웹 사이트를 구축할 수도 있다. 
그렇다고 저작권의 완전한 포기를 의미하는 것은 아니어서 GPL의 기본 원칙과 공개하는 측이 정의한 바를 충실하게 따르도록 되어 있다. 
1990년대에 마련된 GPL V2.0에 이어 2005년에 V3.0이 발표되었다.
GPL 버전 3은 2007년 6월 29일에 발표되었다.
2005년 후반에 자유 소프트웨어 재단에서 GPL의 세번째 판을 개발할 것이라고 발표했다.
바뀐 점 중에서 가장 중요한 4가지를 말하자면, 소프트웨어 특허에 대처하는 것, 다른 라이선스와의 호환성, 어떤 부분의 원시 코드와 무엇이 GPL이 포함되어야 하는 원시 코드를 구성하는지와 디지털 제한 관리(Digital Restrictions Management)에 신경을 썼다.
(https://olis.or.kr/license/Detailselect.do?lId=1072&mapCode=010072)
(https://opensource.org/licenses/gpl-3.0.html)


*GNU Library or Lesser General Public License (LGPL ; version 2.0과 2.1, 3.0 존재)
(https://opensource.org/licenses/lgpl-license)

version 2.1
라이브러리는 공유하되 개발된 제품에 대해서는 소스를 공개하지 않고 상용 SW 판매가 가능한 GPL 보다 완화된 라이선스를 말한다.
GNU 약소 일반 공중 라이선스의 이름으로 공표된 최초의 버전이다. 
본 라이선스는 GNU 라이브러리 일반 공중 라이선스 버전2의 후속판으로 간주되기 때문에 버전 번호를 2.1로 붙인 것이다.
(https://olis.or.kr/license/Detailselect.do?lId=1005&mapCode=010005)
(https://opensource.org/licenses/LGPL-2.1)

version 3.0
라이브러리는 공유하되 개발된 제품에 대해서는 소스를 공개하지 않고 상용 SW 판매가 가능한 GPL 보다 완화된 라이선스를 말한다.
이 라이선스는 GNU 일반 공중 라이선스 버전 3에 추가된 추가 허용 사항들로 구성된다.
GNU 약소 일반 공중 라이선스의 버전 3를 의미하며 GNU GPL은 GNU 일반 공중 라이선스의 버전3을 의미한다.
(https://olis.or.kr/license/Detailselect.do?lId=1073&mapCode=010073)
(https://opensource.org/licenses/LGPL-3.0)

*BSD licenses

New and Simplified BSD licenses (2013년 이후 OSI 라이선스 제외)
캘리포니아 대학이 관장하고 있는 공개 라이선스 및 라이선스 문장. 
유닉스(Unix) 의 양대 뿌리 중 하나인 버클리의 캘리포니아 대학에서 배포하는 공개 소프트웨어의 라이선스이다. 
GNU 자유 소프트웨어 재단의 일반 공중 라이선스(GPL)보다 훨씬 개방적인 4개항의 간단한 문구로 되어 있다. 
그동안 sendmail을 비롯하여 수 많은 인터넷 관련 소프트웨어의 소스나 바이너리가 BSD 라이선스로 공개되어 소프트웨어 및 인터넷 발전에 기여한 바 크다. 
이러한 정신은 FreeBSD, NetBSD, OpenBSD, BSDi 등 파생된 라이선스에서도 그대로 이어지고 있다.
(https://olis.or.kr/license/Detailselect.do?lId=1003)

BSD 3-Clause
원본 라이선스가 종종"BSD-old" 로 참고되어지고 있는만큼, 여기서 파생된3-조항 버전은"BSD-new" 로 불리기도 한다. 
다른 이름으로는"New BSD", "revised BSD", "BSD-3" 혹은"3-조항BSD" 이 있다.
참고로 "New BSD"라는 말을 쓰고는 있지만, BSD 라이선스의 가장 최신 버전은 아니다. 
이 버전 이후 "Simplified BSD 라이선스"라고 알려진 BSD-2-Clause 버전이 나왔다. 
2008년1월9일, OSI 이사회는 FreeBSD 등에 사용되며, 마지막의 "홍보 불가(no-endorsement)" 조항을 삭제하여 결과적으로MIT 라이선스와 거의 동등해진 "Simplified BSD 라이선스"를 승인했다.
(https://olis.or.kr/license/Detailselect.do?lId=1092)
(https://opensource.org/licenses/BSD-3-Clause)

BSD 2-Clause
좀 더 단순화된 버전의BSD 라이선스가 사용되게 되었는데 주로 알려진 이름은"FreeBSD" 이다. 
New BSD(3-조항) 라이선스와의 주된 차이점은 비보증 구문을 삭제하였다는 것이다.
(https://olis.or.kr/license/Detailselect.do?lId=1093)
(https://opensource.org/licenses/BSD-2-Clause)

[오픈소스 SW 라이선스 종합정보시스템 (OLIS)]

https://olis.or.kr/olis/olisMain.do
(>>라이선스의 종류들과 다른 자료들 추가적으로 참고)


