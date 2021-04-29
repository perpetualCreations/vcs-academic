# Electricity Lesson
## REV 1.0, 2021-04-29

Electricity is the natural behavior of electron flow and electric charges.
Commonly experienced in daily life, when interacting with machines that rely on electrical phenomenon to function, human society relies on its existence to operate.

In this lesson, you will review the following concepts,

* [Properties of Current Flow](##vrc)
* [Ohm's Law](##ol)
* [Parts of a Basic Circuit](##pbc)
* [Types of Circuits and Circuit Analysis](#tcca)

This lesson includes an activity.
At the end, there will be a short writing prompt and set of mathematical problems for you to solve.

## <a name="vrc"></a>Properties of Current Flow
Voltage, resistance, and current are properties of current flow.
They can be attributed as follows,

* Voltage - pressure of current flow
* Current - volume of current flow
* Resistance - resistance against current flow

The units for voltage, resistance, and current, are volts, ohms, and amps, respectively. 

In subsequent sections, how these values are correlated to components in a circuit, and how they can predictably change, will be reviewed.

For an analogy of these properties, current flow can be metaphorized as a river, where the force of the river is voltage,
the amount of water running through it the current, and the force acting against the river water, resistance.

![image of water analogy](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/1/9/3/water-analogy.png)
Image credit: SparkFun Electronics, CC BY-SA 4.0, 3rd Party Image Source, not under GPLv3

## <a name="ol"></a>Law
Equation formula,

```
V=IR
```

...is known as Ohm's Law. It dictates the relationship between voltage (V), current (I), and resistance (R).

With algebra, you can solve for any of the three variables so long the other two are provided.
This will be heavily used in the section regarding circuit analysis.

Rearranging to solve for current and resistance,
```
V/R=I
V/I=R
```

Feel free to refer back to this section as reference.

## <a name="pbc"></a>Parts of a Basic Circuit
All circuits have a power source, for current flow to occur. In real world scenarios, the "power source" can be an out-of-scope power grid,
a component capable of generating current (i.e. alternator/dynamo, solar cell, thermocouple), or a battery.

As a generalization to reduce complexity, the next section uses theoretical batteries as an example, with a fixed current as a simple introduction.

Batteries are like wells of electrical energy, the water inside dumped into a stream of current.

Most common real world batteries work chemically, that is, they have positive and negative electrodes, with an electrolyte or other substance as a mechanism for electrochemically producing a current.
Technically, any energy storage device can work chemically. As an example, pumped-storage hydroelectricity is an energy storage technology that uses a pool of water at a high elevation.
To store energy, water is pumped up into the water reservoir, and to release it back into electrical current, the water in the reservoir is released down through gravity, into hydroelectric turbines, to produce current.
However, such technologies are beyond the scope of this lesson.

The first battery was conceived by Alessandro Volta, in 1799, called the voltaic pile, consisting of a primitive stack of zinc and copper plates, sandwiched with cardboard soaked in saline water.

![image of batteries](https://upload.wikimedia.org/wikipedia/commons/3/3b/Batteries.jpg)

Image credit: Wikimedia, Brianiac, Public Domain, 3rd Party Image Source, not under GPLv3

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/Battery_symbol2.svg/800px-Battery_symbol2.svg.png" alt="image of batteries in a circuit diagram" style="transform: rotate(90deg); width: 50%;">

Image credit: Wikimedia, Jacek FH, Public Domain, 3rd Party Image Source, not under GPLv3

Circuits also have a load, a source of current draw, where a component is using the current flow to perform work.
In this lesson's example, we will be using a resistive load, a device that applies resistance to a circuit.

Resistors, as their name implies, induce resistance, and usually release waste heat in result, as with any sort of electrical resistance.
In the real world, these components are usually marked with 4 or 5 stripes, color-coded to indicate their exact resistance value and manufacturing tolerances.

Resistors are like obstructions in a river stream, they slow the current down, reducing its force and throughput.

![image of resistors](https://upload.wikimedia.org/wikipedia/commons/thumb/7/75/Electronic-Axial-Lead-Resistors-Array.jpg/1280px-Electronic-Axial-Lead-Resistors-Array.jpg)

Image credit: Wikimedia, Evan-Amos, Public Domain, 3rd Party Image Source, not under GPLv3

![image of resistors in a circuit diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/2/25/Resistors.svg/1920px-Resistors.svg.png)

Image credit: Wikimedia, Justin Force, Public Domain, 3rd Party Image Source, not under GPLv3

## <a name="tcca"></a>Types of Circuits and Circuit Analysis
There are three types of circuits.

* A series circuit has one continuous path from the positive terminal of the source (battery) to the negative terminal of the source, with no branches.
* A parallel circuit has one continuous path from the positive terminal of the source (battery) to the negative terminal, with no drains (resistive loads), instead with branching paths running parallel to each other.
* A combination circuit is a composite of series and parallel circuit, with specialized techniques for analysis.

Diagram of a series circuit:

![image of series circuit](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0d/Series_circuit.svg/1920px-Series_circuit.svg.png)

Image credit: Wikimedia, Mets501, CC BY-SA 3.0, 3rd Party Image Source, not under GPLv3

Diagram of a parallel circuit:

![image of parallel circuit](https://www.allaboutcircuits.com/uploads/articles/simple-parallel-circuit-diagram.jpg)

Image credit: AllAboutCircuits, [Design Science License](https://www.gnu.org/licenses/dsl.html), 3rd Party Image Source, not under GPLv3

In a series circuit, the total resistance of the circuit is equal to each resistor in series.

```
Rt=R1+R2+R3…
```

In a parallel circuit, resistance totals become more complicated.

```
1/Rt=1/R1+1/R2+1/R3…
```

In a series circuit, current (I) is constant, voltage (V) is not.

In a parallel circuit, voltage (V) is constant, current (I) is not.

When calculating the values of a combination circuit, break the circuit down into components, composed of either series and parallel circuits.
Localize calculations in parts of the circuit, and expand the scope into the rest of the parts.

## Activity
Write a short text answer to the following prompt, "Explain the parts of a circuit."

Please solve the following scenarios.

* Solve for current, when voltage is 4 volts and resistance 2 ohms.
* Solve for voltage, when current is 1 amp and resistance is 1.5 ohms.
* Solve for resistance, when voltage is 3.3 volts and 0.5 amps.

If you have time remaining after finishing the activity, draw a parallel, series, or combination circuit.

Draw resistors in the circuit, and a battery, and assign the battery voltage and resistor resistances.

Solve for current in your custom circuit.

Please email your answers to instructor@dystopian.school.system.net.
