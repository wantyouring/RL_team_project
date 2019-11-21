# RL_team_project
RL 팀프로젝트

## ram 환경  
1. state : [똥 x좌표, 똥 y좌표, player x좌표, player y 좌표]  
2. action :  
+ 0 - 그대로  
+ 1 - 왼쪽 이동  
+ 2 - 오른쪽 이동  
3. reward :  
+ 똥 하나 바닥에 떨어질 때마다 +1  
+ 똥 맞으면 -100  

## pixel 환경
1. state : [PAD_HEIGHT][PAD_WEIGHT].  
2. action :  
+ 0 - 그대로  
+ 1 - 왼쪽 이동  
+ 2 - 오른쪽 이동  
3. reward :  
+ 똥 하나 바닥에 떨어질 때마다 +1  
+ 똥 맞으면 -1  

