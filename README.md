# FreeRTOS SMT32 LED Prototype Project

**Author:** Jeff Pakingan

**Environment:**
- STM32CubeIDE
- FreeRTOS with CMSIS v2 API
- STM32 Blue Pill


**Project Description:**
- FreeRTOS in Preemptive Mode
- OS Abstraction Layer implementation
- 4 tasks are running in Parallel
  - Task 1 - LED Toggle for 500ms
  - Task 2 - LED Toggle for 1000ms
  - Task 3 - Message Queue to send message to Task 4
  - Task 4 - Message Queue receive from Task 3
