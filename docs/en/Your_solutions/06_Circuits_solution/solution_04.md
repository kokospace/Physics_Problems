# Equivalent Resistance Calculation

All resistors in the circuit have the same resistance:

$$
R = 10\ \Omega
$$

We need to find the equivalent resistance between the left and right terminals.

## Step 1: Identify the Series Resistor on the Right

The resistor on the far right is connected in series with the entire network.

$$
R_{\text{right}} = 10\ \Omega
$$

So, first we simplify the network on the left, then add this resistor at the end.

## Step 2: Simplify the Top Branch

The top branch contains two resistors in series.

$$
R_{\text{top}} = 10 + 10
$$

$$
R_{\text{top}} = 20\ \Omega
$$

## Step 3: Simplify the Bottom Branch

The bottom branch begins with one resistor:

$$
10\ \Omega
$$

After that resistor, there are two resistors connected between the same two nodes.  
Therefore, these two resistors are in parallel.

$$
R_{\parallel} = \frac{10 \times 10}{10 + 10}
$$

$$
R_{\parallel} = \frac{100}{20}
$$

$$
R_{\parallel} = 5\ \Omega
$$

Now the bottom branch becomes:

$$
R_{\text{bottom}} = 10 + 5
$$

$$
R_{\text{bottom}} = 15\ \Omega
$$

## Step 4: Combine the Top and Bottom Branches

The top and bottom branches are connected between the same two nodes, so they are in parallel.

$$
R_{\text{network}} =
\frac{R_{\text{top}} R_{\text{bottom}}}
{R_{\text{top}} + R_{\text{bottom}}}
$$

Substitute the values:

$$
R_{\text{network}} =
\frac{20 \times 15}{20 + 15}
$$

$$
R_{\text{network}} =
\frac{300}{35}
$$

$$
R_{\text{network}} =
\frac{60}{7}\ \Omega
$$

$$
R_{\text{network}} \approx 8.57\ \Omega
$$

## Step 5: Add the Right Series Resistor

Now add the far-right resistor, which is in series with the simplified network.

$$
R_{\text{eq}} = R_{\text{network}} + R_{\text{right}}
$$

$$
R_{\text{eq}} = \frac{60}{7} + 10
$$

$$
R_{\text{eq}} = \frac{60}{7} + \frac{70}{7}
$$

$$
R_{\text{eq}} = \frac{130}{7}\ \Omega
$$

$$
R_{\text{eq}} \approx 18.57\ \Omega
$$

## Final Answer

$$
\boxed{R_{\text{eq}} = \frac{130}{7}\ \Omega \approx 18.57\ \Omega}
$$

Therefore, the equivalent resistance of the circuit is:

$$
\boxed{18.57\ \Omega}
$$
