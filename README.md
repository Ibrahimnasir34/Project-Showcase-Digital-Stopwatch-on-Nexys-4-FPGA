**Project Overview**
**Title:** Stopwatch on FPGA
**Team Members: **Noman Ijaz (21-CP-12), Muhammad Ibrahim (21-CP-26), Muhammad Hamza (21-CP-74)
**Supervisor:** Dr. Abdul Rehman Aslam

**Key Features**
**Time Display:** The stopwatch displays hours, minutes, seconds, and tenths of a second on four seven-segment displays.
**Control Functions:** Start, stop, and reset functions are implemented using the FPGA board’s push buttons.
**Precision Timekeeping**: Utilizes a 100 MHz clock signal for accurate timekeeping.
**Wrap-Around Feature**: The stopwatch wraps around at 99:59:59.9, resetting back to 00:00:00.0.
**Efficient Design:** The design is optimized for resource usage, ensuring smooth operation on the Nexys 4 FPGA.
**Design Methodology**
**Modular Approach:** The design includes the top module, stopwatch logic module, and seven-segment display driver module.
**Button Debouncing:** Implemented to ensure accurate start/stop functionality without noise.
**Clock Divider:** Converts the 100 MHz input clock to a 100 Hz signal for driving the counters.
**Challenges and Solutions**
**Debouncing Logic:** Used flip-flops to filter out noise from mechanical button presses.
**Binary to BCD Conversion:** Implemented arithmetic operations within the stopwatch module to convert binary values to BCD for display.
**Resource Optimization:** Ensured efficient usage of logic elements and I/O pins through modular design and Verilog coding practices.
