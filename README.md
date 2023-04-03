# ROS2_control


# 2023 4 03
1. cart pole vs 2 dof inverted pendulum 주제선정 
2. lqr 또는 pid 를 고를 수 있는 모드를 통해 두가지 제어
3. matlab simulink와의 연동을 통해서 확인할 수 있는지 알아 보기
4. code --> mode1, mode2, mode3, mode4 특정모션을 취하는걸 모드로 해놓고, terminal 창에서 mode1 치면 해당 motion 구현
(화살표로 움직임을 만들었으면 좋겠으나, 가능할지는 의문 들어가도 mode1 에서만 (자유 진자운동일때만) 화살표 모드 수락
mode1 --> 자유 운동
mode2 --> inverted pendulum 
mode3 --> right disturbance
mode4 --> left disturbance

각 mode에서 받아오는 angular_velocity, angle, linear_x, 의 값들을 받아와서, matlab 에서 동일한 시뮬레이션을 진행

Matlab 에서는, 그래프 띄우기, 2d motion 구현하기 or simscape로 구현하기
따라서 이번프로젝트에서 구현하고 싶은 것은 

ROS Python code --> gazebo --> matlab --> simulation, 두개의 시뮬레이션에 값을 띄우고 동시에 확인을 해보는 프로젝트이다.

( 강화학습이나 이런쪽으로 나가고 싶은데 대체 어떻게 해야하는지 모르겠음)

이번 보고서 관련내용은 github management, ros python, matlab 을 다루는 방향으로 보고서를 작성해야겠음 
