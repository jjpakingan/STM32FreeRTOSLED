# FreeRTOS STM32 Project

**Author:** Jeff Pakingan

**Environment:**
- STM32CubeIDE
- FreeRTOS with CMSIS v2 API
- STM32 Blue Pill


**Project Description:**
- FreeRTOS in Preemptive Mode
- OS Abstraction Layer implementation
- Task notification using MessageQueue and Event Flags
- 4 tasks are running in Parallel
  - Task 1 - LED Toggle for 500ms
  - Task 2 - LED Toggle for 1000ms
  - Task 3 - Message Queue/Event Flags to send message to Task 4
  - Task 4 - Message Queue/Event Flags receive from Task 3


  Reference:
  https://www.keil.com/pack/doc/CMSIS/RTOS2/html/group__CMSIS__RTOS__EventFlags.html#details
  https://www.coursehero.com/file/p6ff6av/CMSIS-RTOS-thread-flags-example-Thread-1-void-ledOn-void-constant-argument-for/