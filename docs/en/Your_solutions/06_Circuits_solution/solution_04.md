# Equivalent Resistance Calculation

All resistors have the same resistance:

\[
R = 10\ \Omega
\]

We need to calculate the equivalent resistance between the left and right terminals.

## Step 1: Identify the Far-Right Resistor

The resistor on the far right is connected after the whole network, so it is in **series** with the rest of the circuit.

We will add it at the end.

\[
R_{\text{right}} = 10\ \Omega
\]

## Step 2: Simplify the Top Branch

The top branch has two resistors in series:

\[
R_{\text{top}} = R + R
\]

\[
R_{\text{top}} = 10 + 10 = 20\ \Omega
\]

## Step 3: Simplify the Bottom Branch

The bottom branch starts with one resistor:

\[
10\ \Omega
\]

After that, there are two resistors connected between the same two nodes, so they are in **parallel**:

\[
R_{\parallel} = \frac{10 \times 10}{10 + 10}
\]

\[
R_{\parallel} = \frac{100}{20} = 5\ \Omega
\]

So the bottom branch becomes:

\[
R_{\text{bottom}} = 10 + 5
\]

\[
R_{\text{bottom}} = 15\ \Omega
\]

## Step 4: Combine Top and Bottom Branches

The top and bottom branches are in parallel:

\[
R_{\text{network}} = \frac{R_{\text{top}}R_{\text{bottom}}}{R_{\text{top}} + R_{\text{bottom}}}
\]

\[
R_{\text{network}} = \frac{20 \times 15}{20 + 15}
\]

\[
R_{\text{network}} = \frac{300}{35}
\]

\[
R_{\text{network}} = \frac{60}{7}\ \Omega
\]

\[
R_{\text{network}} \approx 8.57\ \Omega
\]

## Step 5: Add the Far-Right Series Resistor

Now add the far-right resistor:

\[
R_{\text{eq}} = R_{\text{network}} + R_{\text{right}}
\]

\[
R_{\text{eq}} = \frac{60}{7} + 10
\]

\[
R_{\text{eq}} = \frac{60}{7} + \frac{70}{7}
\]

\[
R_{\text{eq}} = \frac{130}{7}\ \Omega
\]

\[
R_{\text{eq}} \approx 18.57\ \Omega
\]

## Final Answer

\[
\boxed{R_{\text{eq}} = \frac{130}{7}\ \Omega \approx 18.57\ \Omega}
\]

Therefore, the equivalent resistance of the circuit is approximately:

\[
\boxed{18.57\ \Omega}
\]
