# Flight Part 1: Setup for flight

#### Power source

* Single-phase 240V AC, minimum 4000W, from an EV, generator, or shore power.
* Make sure the source won’t shut down mid-flight: know where the breaker is, have enough fuel, and check the EV’s charge.
* Warning: if tether power is lost, the SL8 takes over and the aircraft RTLs automatically.

#### Environment

* No rain or precipitation.
* Avoid high or gusty wind, and remember wind is often stronger at higher altitudes.
* Check for obstacles that could snag the tether, such as trees, structures and equipment.

#### Aircraft

1. Turn on the Pilot Pro. Set D2 to 0%.
2. Place the aircraft 5–10m from the tether ground unit, with a clear radius of at least 5m.
3. Unfold the aircraft, latch the booms and unfold props.
4. Install the air unit on the right-side battery interface and connect the XT90.
5. Install a fully charged SL8.&#x20;
6. Confirm the parameter FF\_ASTRO\_TYPE is set to Flying Sun. This change requires rebooting the aircraft.

#### Tether

1. Attach the strain relief to the underside of the aircraft.
2. Connect the LP12 plug to the air unit receptacle, routing the cable clear of the props.
3. Pull out about 3m of extra cable. This sets the tether zero point.
4. Power on the aircraft and confirm the Pilot Pro is connected.
5. Connect the AC input cable to the tether ground unit, then to the power source.
6. Open the Flying Sun app and connect to the ground unit over BLE.
7. Tip: Use dual screen or overlay bubble to monitor tether and HV status while running AMC.

