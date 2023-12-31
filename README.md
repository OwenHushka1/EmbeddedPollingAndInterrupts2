# EmbeddedPollingAndInterrupts
This is an embedded C project written for the STM32F429ZITx FPGA board. The goal of the project was to practice implementing polling and interrupts.
This project has a macro called USE_INTERRUPT_FOR_BUTTON which switches the program between using interrupts and using polling. 
This project polls for and generates interrupts for events triggered by the devices internal timer 2, timer 5 and the button peripheral. 
