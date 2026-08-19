GBA-Overclock Tool
Non-Destructive hardware interface designed to intercept and manipulate 
the internal clock speed of the Gameboy Advance (GBA), for dynamic speed control or software testing purposes.

The overclock tool works by replacing and overriding the default system clock signal on the Game Boy Advance using a custom breakout
board. By intercepting the stock crystal oscillator circuit (natively running at 1.678*10^7 Hz), this board then connects the signal to its
internal array of oscillators to enable variable runtime execution speeds, making it ideal for testing homebrew software stability 
under non-standard clock cycles and analyzing system behavior under stress. 

To put it simply, this project attempts to port the variable speed option from emulators onto real hardware, while prioritizing hardware 
integrity.
