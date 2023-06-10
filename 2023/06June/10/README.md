# 10/06

## Update
- It has been a while since [last time](https://github.com/pllee4/devel-record/tree/master/2022/09September/25) when I felt the rotation of robot model in scene view is abit weird.
- After drawing axis of world, it could be seen that the rotation was based on the world origin, that's why the rotation looks unnatural.
- We can see the difference before and after the fixing. It took me quite a while to figure out on how to translate the origin and ensure the model rotates at its origin.
- The axis of rotation is now changed to the axis across the center of the wheels. The movement becomes more natural. Nevertheless, there is still some imperfections when the wheels and the body of the robot are treated as a whole body. In real scenario, they are considered as two different bodies where the body could rotate without rotation of wheel (if we hold the wheels and allow a free falling action)

## Before
https://github.com/pllee4/devel-record/assets/42335542/a9440de7-88e1-40f2-a2c9-342dafb7ac9d

## After
https://github.com/pllee4/devel-record/assets/42335542/6a6bce45-d4c2-42dd-b72c-3704e865e0e7