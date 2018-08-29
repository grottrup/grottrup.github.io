
## Using Markdown+Math Tex notation:

$k_{n+1} = n^2 + k_n^2 - k_{n-1}$

$$\frac{numerator}{denominator}$$

$$
\begin{matrix}
  a & b & c \\
  d & e & f \\
  g & h & i
\end{matrix}
$$

## Microcontroller Systems lesson #1

Machine code (10010101)

Symbolic machine code (ADD, INC etc)

High-level languages (C, C# etc)

A compiler makes high level languages into machine code

Different divices might each have their own architecture and different machine code for operations

Flash is the memory that will still be remembered when the voltage supply is cut

LSB (Least significant bit)
MSB (Most significant bit)

En mente er det danske ord for en carry

Von Neumann vs. Harvard architecture

En bus er en et bundt ledninger der går ud til CPUen og hukommelsen ( Det er den samme for Neumann... Neumann har én "landevej")

Harvard er måske mere moderne... Hver hukommelse for hver deres "landevej". Dette gør man kan gøre to ting sammetidig, men det koster en ekstra landevej.

AtmelMega2560 har en Harward architektur.

## Introductory digital electronics lesson #1

The frequency of a periodic waveform is the reciprocal of the period. The formulas relating frequency and period are:


### Presentation

* How to get a smooth analog curve?
    * E.g. a mechanic arm drawing the analog temperature
        * Analog pen
        * Analog sensor
        * Analog mechanics
* The risk of digital sampling is that you might miss some data
* Digital-to-analog converter
    * The Arduino has one for e.g. music
* The acceptable and dependable reading for whether it is a high or low signal
    * $V_{L(max)}$ $V_{L(min)}$ $V_{H(max)}$ $V_{H(min)}$ 
* Periodic pulse waveforms
    * $f = 1/T$ and $T = 1/f$
    * $T = 1/3.2GHz$
    * $T = 1/(3.2 * 10^9 Hz) = 300pS$
* Duty cycle
    * E.g. 30%
    * How do the signal change as a function of the time? f(t)
* Serial connection
    * When transfering data with a USB cable
* Where the inverter bubble matters when there a multiple legs
* Multiplexer/Demultiplexer... What kinda signal?
* SMD... Surface Mounted Devices... E.g.the small DIP chips with weird legs.

* Gate standard drawings...
    * NOT = INVERTER
    * Truth tables
    * NOT/INVERT is when there is a bar over the letter $\overline{A}$
    * Modern(?) notation is a box with a symbol, but some prefer the notation with the shapes
    * Using IC for not???
        * Logic IC... Component


### Lesson learnings

* Fig 1 - 24
* Code converter / encoder
* Mux Demux... Code/Decode
* Gates
* Clock

* Analog discovery for measuring
    * Can also measure digital signals, but only for 3.3V, so not that useful
    * Has an analog amps / voltage meter
    * It is really just a fancy multimeter

### Book notes - Digital Fundamentals

#### 1–1 Digital and Analog Quantities 

**digital-to-analog converter (DAC)**
**analog-to-digital converter (ADC)**


#### 1–2 Binary Digits, Logic Levels, and Digital Waveforms


#### 1–3 Basic Logic Functions

#### 1–4 Combinational and Sequential Logic Functions

#### 1–5 Introduction to Programmable Logic
#### 1–6 Fixed-Function Logic Devices
#### 1–7 Test and Measurement Instruments
#### 1–8 Introduction to Troubleshooting
