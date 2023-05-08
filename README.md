Download Link: https://assignmentchef.com/product/solved-uwee538-homework-2-common-emitter-amplifier
<br>
For the following, use the figure and the simplified NPN model from Section 2.1.1 in AoE. <em>V<sub>CC</sub></em> = 5V, <em>C</em> =

1µF, and  = 100. Use the <em>npn</em> Ltspice component for your simulations.

<ol>

 <li>Select values for <em>R<sub>B1</sub></em> and <em>R<sub>B2 </sub></em>to achieve <em>V<sub>B</sub></em> = 1V and a high-pass corner frequency (<em>f<sub>3dB</sub></em>) of 10Hz. You may ignore base current for this step.</li>

 <li>Choose <em>R<sub>C</sub></em> and <em>R<sub>E</sub> </em>for a gain of −10V/V (at 10kHz) and a collector current of 1mA. What is the DC value of <em>V<sub>CE</sub></em>?</li>

 <li>Derive the transfer function for <em>V<sub>out</sub></em>/<em>V<sub>in</sub></em> and plot the frequency response (magnitude and phase) in MATLAB/Python.</li>

 <li>Perform an AC simulation of the circuit in Ltspice. Export the frequency response data for comparison to the ideal response from Part c (plot them together). Provide reasons for any discrepancies between the two.</li>

</ol>

<h1>Problem 2: Emitter follower</h1>

<h1>Figure 2a. Emitter follower                                      Figure 2b. Small-signal equivalent circuit</h1>

Use the <u>Ebers-Moll model </u>of the BJT and the figures to answer the following questions. <em>V<sub>CC</sub></em> = 5V, <em>I<sub>S</sub></em> = 10<sup>−16</sup>, and  = 100. When determining input/output resistances, connect a test voltage to the smallsignal circuit and determine the resistance as <em>r</em> = <em>v<sub>test</sub></em>/<em>i<sub>test</sub></em>. Use the <em>npn</em> Ltspice component for your simulations.

<ol>

 <li>Design the biasing of the emitter follower (i.e. determine <em>V<sub>B</sub></em> and <em>R<sub>E</sub></em>) such that the collector current is 1mA and the DC level of <em>V<sub>out</sub></em> is 1V. You can do this by hand or use a MATLAB/Python script.</li>

 <li>Use the small-signal model (Fig. 2b) to determine the input resistance of the circuit.</li>

 <li>Use the small-signal model (Fig. 2b) to determine the output resistance of the circuit.</li>

 <li>Verify your design in Ltspice and include all relevant SPICE schematics and results in your submission.</li>

</ol>
































