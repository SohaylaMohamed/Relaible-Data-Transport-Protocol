cmake_minimum_required(VERSION 3.15)
project(ClientSide)

set(CMAKE_CXX_STANDARD 14)

add_executable(ClientSide main.cpp ClientManager.cpp ClientManager.h Sender.cpp Sender.h Receiver.cpp Receiver.h Packet.h PacketHandler.cpp PacketHandler.h Utilities.cpp Utilities.h)