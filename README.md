# Reinforcement learning 
#### 파이썬과 케라스로 배우는 강화학습 : 내 손으로 직접 구현하는 게임 인공지능  

> MDP (Markov Decision Process) : 순차적 행동 결정 문제를 수학적으로 정의하는 방법  
: 순차적 행동을 수학적으로 잘 정의하는거 자체가 제일 중요함  

## Q learning & Q update & epsilon greedy action & discount factor  
> decaying epsilon greedy  
: 에피소드별로 epsilon[0~1]을 점점 줄여줌  
> discount factor(gamma, [0,1])  
: 효율적인 path를 찾게 해줌  
: 현재 vs 미래 reward, 이자 같은거지 지금의 100원의 가치는 미래에는 100원 이하가 될거야 이 현상을 반영하기 위해 만들어낸 지표
