# Go-IM-project

项目简介：
为了巩固前期学习的Golang的基础知识，他是一个在线聊天项目，能够完成私聊、公聊、查询用户等功能。快速了解Golang写服务器的特点，顺带复习计算机网络的知识。

server中包含：server和user两种，user为个人用户，server为服务器。

OnilineMap：用来记录当前用户在线的情况。

channel：能够把消息广播给各个客户端。

user：两个go程，一个从channel中读取消息，一个负责从客户端发送消息。（读写分离）

架构图：项目架构.pdf




