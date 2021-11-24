# Unity-Server

C#과 유니티를 활용한 MMO RPG 게임 서버 프로젝트입니다. <br>
이전 프로젝트인 [mmo-rpg-server-template](https://github.com/ohminkwon/mmo-rpg-server-template)를 활용하여 프로젝트를 시작합니다. <br>
[Visual Studio](https://visualstudio.microsoft.com/ko/)와 [Unity](https://unity.com/kr)를 활용합니다.

## 🖥️ 동작 화면
![example](./server.gif)

## 🎯Main Contents

- Multi Thread
  - optimizing compiler
  - memory barrier
  - cache principle
    - temporal locality
    - spacial locality
  - Locks and Synchronization
    - Interlock
    - Deadlock
    - Spinlock
    - ReaderWriterlock
    - Thread Local Storage (TLS)
- Network
  - Socket
  - Listener
  - Session
  - Connector
  - TCP & UDP
  - Recv & Send buffer
- Packet
  - Packet Serialization
  - Packet Generator  
- Job Queue
  - flow control
  - scheduling

## 📚 Refs
- https://github.com/martinkang/Study/blob/master/LinuxNetworkProgramming/TCP-Control_Method.md

- https://techdifferences.com/difference-between-flow-control-and-congestion-control.html