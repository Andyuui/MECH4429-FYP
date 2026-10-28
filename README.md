# MECH4429-FYP

This project investigates whether a quadrotor can use a learned low-level controller to retain bounded position and altitude after one rotor completely loses thrust.

The control policy directly commands all four motors. Under rotor-failure conditions, the simulator enforces zero applied thrust on the failed rotor regardless of its commanded value.
