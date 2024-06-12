# Standford-DeeplearningLesson
AndrewLessonFromD eepLearning.ai

00.AI For Everyone
 https://www.coursera.org/account/accomplishments/certificate/5KL5QNE47DXE

01.Supervised Learning 
 [Supervised Machine Learning: Regression and Classification](https://www.coursera.org/learn/machine-learning/home/info)

  \01.practice  : 原题

  \02.home      : 我已经做好了的练习

  环境：使用Anaconda，import `AndrewPyEnvC1.yaml`的环境配置

02.Advanced Learning Algorithms

 [Advanced Learning Algorithms](https://www.coursera.org/learn/advanced-learning-algorithms/home/info)

  \01.practice  : 原题

  \02.home      : 我已经做好了的练习

  环境：使用Anaconda，import `AndrewPyEnvC2.yaml`的环境配置

03.Unsupervised Learning, Recommenders, Reinforcement Learning
 [Unsupervised Learning, Recommenders, Reinforcement Learning](https://www.coursera.org/learn/unsupervised-learning-recommenders-reinforcement-learning/home/info)

  \01.practice  : 原题

  \02.home      : 我已经做好了的练习；

  环境：由于需要使用一些Linux的环境，参考https://blog.csdn.net/amuro_ray027/article/details/136735280 进行Docker环境搭建
  然后使用文件夹下的`Dockerfile`进行image构建，在Dockerfile所在的文件夹下运行
  `docker build -t reinforcement-learning:v2 .`即可
  从Chrome启动127.0.0.1:10000，输入对应的`token`信息就可以启动Jupyter Notebook了，但是考虑到plotly和ipywidget的兼容性，建议启动Jupyterlab进行运行，才能保证所有的结果正确无误。
  