# 基于DeepCubeA的魔方复原网站
本程序基于[DeepCubeA](https://codeocean.com/capsule/5723040/tree/v1)<br>
具体内容详见[实验报告report.pdf](https://github.com/JakeMustangLi/Cube/blob/master/report.pdf)<br>
本系统因基于DeepCubeA，所以使用Python Web开发，这里选择了Flask+uWSGI+Nginx作为服务端，前端使用HTML+CSS+JavaScript开发。<br>

--------------------------------
下文是DeepCubeA的原README.md
# deepcube-full

> A full stack project realized by flask for deploying the DeepCubeA algorithm in own server and visualize.

## Usage
1. download the trained model from references follows, put in right file path(/code/savedModels/...).
2. run `python server.py` in /interface/, to deploy website in current device.
3. open web page with url [127.0.0.1:5000](127.0.0.1:5000), port can be edited in /interface/server.py bottom line.

## References
[1] Agostinelli, Forest, et al. "Solving the Rubik’s cube with deep reinforcement learning and search." Nature Machine Intelligence 1.8 (2019): 356-363.[[link]](https://www.nature.com/articles/s42256-019-0070-z.epdf?shared_access_token=-pCSsZa_J9bM8VyXLZLRctRgN0jAjWel9jnR3ZoTv0Osb8UCgUm5AQaSCMHWqWzsyV3KBcb13SAW-9IL1pAGd1HcSk40JSEjhoaBAi0ePvYh_5Dul6LvK0oJY1KI0ULo9O9HCut_y7aCTc93Th8m5g%3D%3D)

[2] [DeepCubeA](https://codeocean.com/capsule/5723040/tree/v1) Source Code.
