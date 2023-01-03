cmake_minimum_required(VERSION 3.23)
project(ThreadPool)

set(CMAKE_CXX_STANDARD 14)

add_executable(ThreadPool main.cpp CountDownLatch.h noncopyable.h MutexLock.h Condition.h Thread.h Thread.cpp ThreadPool.h ThreadPool.cpp)
