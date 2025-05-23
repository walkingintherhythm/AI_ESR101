[Computer Science]

ver.1.0  1986  SPC-1000(Z80A, CP/M OS), IQ-2000(MSX2), Abacus
ver.2.0  1988  IBM-PC(8086, MS-DOS) BASIC / snakebyte
ver.3.0  1993  Game of Life
ver.4.0  1994  C.N.U. (Computer & Us)
ver.5.0  1996  『MALIS(Mind And Life In Silico)』(B.A)

life /laif/ n (pl lives /laivz/) 1 [U] [in general,] ability to function and grow that distinguishes living animals and plants from dead ones and from rocks, metals, etc. [But from a information-processing point of view, includes rolling-rocks, melting-metals, etc: An autonomous solar-powered LEGO robot is also a life form, but not the same measure as an amoeba or algae. A cellular automata configuration that self-organizes reduces the entropy within its local neighborhood (an abstract space-time) but increases the entropy in the universe (same abstract space-time). It also is a life form. ▸cf. artificial life]  2 [U] living things: Is there life on Mars?  3 ...... 
이 논문은 크게 다섯 부분으로 이루어져 있다.
첫째, 서론 - 인공생명의 정의(Definition of Artificial Life)는 ‘생명이란 무엇인가’라는 질문을 통해 새로운 정보처리적 관점에서 생명의 본질과 핵심적인 특성에 대해 설명한다.
둘째, 인공생명의 간략한 역사(Brief History of Artificial Life)에서는 고대 그리스 신화에서부터 1987년 ‘제1회 인공생명 워크샵’에 이르는 인공생명의 역사에 대해 간략히 정리한다.
셋째, 인공생명 형태의 구현(Realization of Artificial Life Forms)은 주로 소프트웨어의 측면에서 논의되고 있는 연구들에 대해 살펴보고, 웨트웨어(wetware)와 하드웨어에 관한 최근의 연구들에 대해서 소개한다. 그리고 기본적인 인공생명의 형태로서 몇몇 간단한 세포 자동자 모델들을 실제로 구현해 본다.
넷째, 토론사항(Discussion)으로는 ‘마음은 기계인가’에 대한 일련의 논쟁에 대해 살펴본다.
다섯째, 결론 및 앞으로의 연구 방향(Conclusion & Future Directions)에서는 이 논문의 의의에 대해 되짚어보고 이후 인공생명의 연구 전망 및 개인적인 연구 방향에 대해 언급한다.
“본 논문의 목적은 새로운 인공생명의 ‘창조’에 있지 않다. 단지, 생명현상에 대한 하나의 과학적인 ‘접근방식’으로서 의미가 있을 뿐이다.”

ver.6.0  1998  『진동과 안정 사이의 딜레마를 해결하기 위한 강화학습 기반 지능형 에이전트』(M.S)

1950년 튜링(Alan M. Turing)은 ‘계산하는 기계와 지능(Computing Machinery and Intelligence)’이라는 논문을 발표하였다. 그는 논문의 첫장을 ‘기계는 생각할 수 있는가?’라는 질문으로 시작하면서, 모방게임이라는 흥미로운 아이디어를 제안하였다. 이에 대한 화답으로 인공지능 분야가 탄생하였다.
그로부터 40여년 후, 인터넷과 웹을 중심으로한 컴퓨터 환경의 재편에 따라 인공지능에 대한 논의는 ‘지능형 에이전트를 어떻게 구현할 것이냐’의 문제로 옮아갔다. 그러나 그동안 인공지능 분야에서 연구되어왔던 로직을 이용한 추론방법이나 신경망, 유전자 알고리즘 등의 학습방법은 환경의 변화에 적절히 적응하고 스스로 행동을 결정하며, 사회성을 지닌 에이전트의 특성을 제대로 구현할 수 없다. 왜냐하면 이러한 방법들은 동적 환경에서의 에이전트의 경험이나 학습과정 보다는 사용자의 의도나 학습결과에 더 주목하기 때문이다.
이에 따라, 최근에는 에이전트를 지능적으로 만들기 위하여, 시행착오를 통한 탐색과 지연되고 누적되는 보상값을 이용하는 강화학습(reinforcement learning)에 대한 연구가 널리 이루어지고 있다. 동적 프로그래밍(dynamic programming)과 마코프 결정 과정(Markov decision process)에 이론적 기반을 두고 있는 강화학습은 에이전트 스스로 환경과의 상호작용을 통해 최적의 정책을 학습하는 것을 보장한다. 그러나 이를 위해서는 강화학습의 행동 선택에 관한 문제인 진동과 안정 사이의 딜레마(exploration-exploitation dilemma)를 해결할 수 있는 탐색 전략(exploration strategy)이 전제되어야 한다. 이 딜레마를 해결하기 위해 그동안 많은 방법들이 제안되었지만, 이들 모두 두가지 특성 중 한가지 측면만을 강조함으로써 일정한 한계를 지니고 있었다.
이 문제를 해결하기 위해 본 논문에서는 강화학습 알고리즘의 수렴에 필요한 행동 선택의 임의성(exploration)과 경험을 통해 축적된 지식의 활용(exploitation)을 동시에 고려한 새로운 탐색 전략을 제안한다. 이를 통해 에이전트는 자율성과 적응성을 획득할 수 있다. 그리고 나서 마지막으로 에이전트의 사회적인 특성을 만족시키기 위해 에이전트들 간의 지각 정보와 정책의 공유를 통한 협력에 대해 논의한다. 실험을 위해 본 논문에서는 실시간 온라인 학습에 적합한 Q-learning 알고리즘과 에이전트 시스템 연구에 있어 전통적인 문제인 추적문제(pursuit problem)를 사용한다.

ver.7.0  2010  『인디 공간의 문화정치학』(M.A)


[Researcher & Engineer]



[Materials update]

ver.1.0  Oct, 2017  Rocommendation System   @ HP
ver.2.0  Jun, 2018  Robo Advisor Proj.      @ SH Bank
ver.3.0  summer, 2021  AICC Proj.           @ SH Security
ver.4.0  Nov, 2021  AC.34                   @ KC
ver.5.0  Dec, 2022  AI/ML for Poet          @ HIT
ver.6.0  Jul, 2023  인공지능을 여행하는 인문사회 연구자를 위한 안내서          @ Catslab
ver.7.0  Jul, 2023  AI/ML 101               @ TI Cloud
ver.8.0  Feb, 2025  AI/ML 101 with Pencil   @ KIH

