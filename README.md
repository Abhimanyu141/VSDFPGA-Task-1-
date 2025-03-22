Summary (README)
This project involves designing a Verilog-based system to control an RGB LED using the VSDSquadron FPGA Mini board. The system takes a hardware clock input and generates color patterns on the RGB LED by utilizing an internal oscillator and frequency counter logic. The design is implemented using Verilog, with the output signals controlling the red, green, and blue channels of the LED.

Key Components:
Verilog Code: Defines the logic for controlling the RGB LED, including an internal oscillator and frequency counter to drive the LED driver with color patterns.

PCF File: Maps the Verilog-defined outputs (led_red, led_blue, led_green, testwire) and input (hw_clk) to the correct physical pins on the FPGA board.

Makefile: Provides the necessary commands to compile and flash the FPGA with the Verilog design.

Steps for Integration:
Verify Pin Assignments in the PCF file to ensure correct mapping to the FPGA pins.

Compile the Design using the provided Makefile (make clean, make build, sudo make flash).

Program the FPGA and observe the RGB LED behavior to ensure correct color outputs.

Goal:
The aim of this project is to demonstrate the ability to control an RGB LED on the FPGA board using Verilog, with the flexibility to produce different color outputs based on an internal oscillator-driven counter.

Final Deliverables:
Verilog Code for the RGB LED control logic.

PCF File for pin assignments.

Makefile for compiling and flashing the design.

Documentation with all integration steps and observations.



# VSDFPGA-Task-1-
