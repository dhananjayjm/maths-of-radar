:orphan:

.. _Range:

Range or distance measurement
===============================

The radar transmits a short radio pulse with very high pulse power. This pulse is focused in one direction only by the directivity of the antenna, and propagates in this given direction with the speed of light.

If in this direction is an obstacle, for example an airplane, then a part of the energy of the pulse is scattered in all directions. A very small portion is also reflected back to the radar. The radar antenna receives this energy and the radar evaluates the contained information.

The distance we can measure with a simple oscilloscope. On the oscilloscope moves synchronously with the transmitted pulse a luminous point and leaves a trail. The deflection starts with the transmitter pulse. The luminescent spot moves to scale on the oscilloscope with the radio wave. At this moment, in which the antenna receives the echo pulse, this pulse is also shown on the oscilloscope. The distance between the two shown pulses on the oscilloscope is a measure of the distance of the aircraft.

Since the propagation of radio waves happens at constant speed (the speed of light :math:`c_{0}`) this distance is determined from the runtime of the high-frequency transmitted signal. The actual range of a target from the radar is known as slant range. Slant range is the line of sight distance between the radar and the object illuminated. While ground range is the horizontal distance between the emitter and its target and its calculation requires knowledge of the target's elevation. Since the waves travel to a target and back, the round trip time is dividing by two in order to obtain the time the wave took to reach the target. Therefore the following formula arises for the slant range,

.. math::

    R = \frac{c_0~t}{2}

| :math:`c_{0}=` speed of light = :math:`3 \times 10^{8}~\text{m s}^{-1}`, 

| :math:`t=` measured runtime [s], 

| :math:`R=` slant range antenna - aim [m]

**Derivation of the equation**

**Range** is the distance from the radar site to the target measured along the line of sight.

.. math::

    v = \frac{s}{t} \\


    c_{0} = \frac{2R}{t}

The factor of two in the equation comes from the observation that the radar pulse must travel to the target and back before detection, or twice the range.

.. math::

    R = \frac{c_0~t}{2}

Where :math:`c_{0}=3 \times 10^{8}~\text{m s}^{-1}`, is the speed of light at which all electromagnetic waves propagate.

If the respective running **time** :math:`t` is known, then the **distance** :math:`R` between a target and the radar set can be calculated by using this equation.