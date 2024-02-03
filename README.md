기존의 pytorch cartpole example에서 cartpole의 state를 display로 볼 수 있도록 수정했다.
---
env=gym.make("CartPole-v1",render_mode='human')
...
env.render()

