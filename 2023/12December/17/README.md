# 17/12

## Update
- Spent quite some time on dynamics equation to check why the motion of robot seemed weird when there was no control input (free falling)

https://github.com/pllee4/devel-record/assets/42335542/7ae034a5-fde1-46e9-bf0d-93322fbf0ea5

- In the end, it was normal as from the equation there was no damping factor being considered.
- Cross-checked with previous inverted pendulum on cart, this is how it looks like when there is no damping. There could be acceleration which could explain the behaviour in two wheeled inverted pendulum (twip)

https://github.com/pllee4/devel-record/assets/42335542/684e9644-9b17-4987-93ef-234c57adee80

- After consider damping factor in twip, now it is having similar behaviour as inverted pendulum on cart.

https://github.com/pllee4/devel-record/assets/42335542/3d1bb528-b081-4193-823a-420b58ec7d7c
