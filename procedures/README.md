# Procedures

The Flying Sun is a complex system requiring precise configuration for optimal results. This article serves as a comprehensive resource to guide you through the setup and usage of the Flying Sun hardware and its accompanying software.

## **Flight Prep:**

{% embed url="https://youtu.be/wG1htYX7RK4" %}

### Setup Power Source

* Ensure power source provides single phase 240V AC with a minimum of 5kW power.
* Check power source shutdown condition, make sure it won't shut down midflight!
  * Make sure that you know locations of breaker if using shore power
  * Make sure you have sufficient fuel if using a generator
  * Make sure your vehicles state of charge is sufficient for the duration of flight you plan

{% hint style="warning" %}
Astro will RTL at 50% battery, which takes about 5-7 minutes if the tether loses power
{% endhint %}

### Setup Flying Sun 500

1. Turn on Pilot Pro and allow it to boot up.
2. Ensure [D2 nob](../system-overview.md#pilot-pro) is in the counterclockwise position and [S2 switch](../system-overview.md#pilot-pro) is in the down position.
3. Place Astro 5 to 10 meters / 16 to 32 feet away from Ground Unit.
4. Install Air Unit on Astro's [right side](../system-overview.md#air-unit) battery interface.
5. Connect Astro's XT-90 plug to XT-90 port on right side of Air Unit.
6. Confirm [SL8](https://freefly.gitbook.io/freefly-public/products/superlight-batteries) state of charge is above 90% and install on Astro.
   * Tether only allows HV to be enabled when SL8 is charged above 90%.



### Setup 3kW Tether

1. Connect power cable to tether ground unit.
2. Connect power cable to power source. (Electric Vehicle, Generator, or Shore Power)
3. Attach tether cable strain relief to strain relief loop on underside of Astro.
4. Connect tether cable XT-60 plug to Air Unit XT-60 port.
   * Check tether cable to ensure no possibility of prop strike on any portion of the cable
5. Pull out at least 3 meters/10 feet of additional tether cable.
6. Turn on FS500 by enabling SL8.
7. Open Flying Sun app on Pilot Pro.
8. Connect app to tether Gournd Unit via Bluetooth.
9. Enable dual screen. (AMC + Flying Sun App)
   * Dual screen allows pilot to utilize features on AMC while having access to tether console.



#### Check Environmental Conditions

{% embed url="https://youtu.be/V6AbcJb9_6U" %}

#### Check Environmental Conditions

* Rain
  * Do not fly in Rain. Water and High Voltage do not mix!
* High Winds
  * Do not fly in high winds. The tether can be whipped by the wind, potentially causing a crash

{% hint style="info" %}
Winds are often higher aloft. Be aware of your surroundings and any obstacles such as buildings that may block wind at ground level
{% endhint %}

* Obstacles adjacent to operation area
  * Trees, equipment and structures can cause tether entanglement

***



## **Take off**

{% embed url="https://youtu.be/wG1htYX7RK4?t=123" %}

{% hint style="info" %}
Flying sun is designed to be flown in position mode.
{% endhint %}

{% hint style="danger" %}
Make sure all persons are clear of drone and tether.
{% endhint %}

When ready for takeoff enable high voltage (HV) on flying sun app&#x20;

Take off in position mode or use auto take off feature in AMC.

Hovering for extended amount of time should be with tether cable taut





***



## **During Flight**&#x20;

{% embed url="https://youtu.be/wG1htYX7RK4?t=216" %}

### Monitor Tether Power:

Operators should monitor the power used by the tether in order to make sure it's within expected ranges

{% hint style="info" %}
Hovering without light should require less than 1100W
{% endhint %}

{% hint style="info" %}
Hovering with 100% light should require less than 2800W
{% endhint %}

Things that draw more power during flight:

* Ascending
* Reducing rate of descent&#x20;
* Turning up the lights&#x20;
* Hovering at high altitude (Increased payload of additional tether cable)
* High winds

{% hint style="warning" %}
Avoid climbing with lights on 100% if possible as that will draw close to the limit of the tether system. Tether ground unit may shut down if power draw exceeds the system's limit, please see [Safety](https://app.gitbook.com/o/-LYU75KLzw4BcaiMGVz2/s/-LaNHxABbg20hfA0zTDQ/~/changes/956/products/flying-sun-500/safety/~/comments) section for more info.
{% endhint %}

#### Pilot should never walk away during flight.

Always know where and how to turn off the power source for the tether.

Always keep a fire extinguisher (Class D) handy during operations.

#### Avoid hovering at tether zero point.

The Ground Unit actively keeps tension on the tether cable, tether zero point is the length of cable initially pulled out by the user while the tether is powered down. This point is where the tether will cease retracting cable.

{% hint style="warning" %}
The tether may oscillate when held at or close to the tether zero point. **This should be avoided.**
{% endhint %}

#### Over extension warning.

The Ground Unit is equipped with 110m (\~360ft) of tether cable.

The Ground Unit will sound a beeper alarm when tether extends over 90m (\~300ft).





***



## **Landing and pack up**

{% embed url="https://www.youtube.com/watch?v=Gwi6Fra7ysQ&feature=youtu.be" %}

1. Land in position mode.
2. Disable High Voltage in FS app on Pilot Pro after disarming.
3. Turn off Ground Unit breaker switch and backup power switch.
4. Disconnect main power cable from power source.
5. Disconnect tether XT-60 plug and strain relief clip from FS500.
6. Turn on Ground Unit backup power and connect to flying sun app.
7. Press take up button in FS app to retract the tether cable.
   * It can be helpful to release this prior to the plug assembly reaching the Ground Unit to avoid damage to the plug.

{% hint style="warning" %}
Please ensure the cable isn't bent, kinked or knotted anywhere, this can result in damage when retracted into the Ground Unit. Please see [Maintenance](../maintenance.md) section for more information.
{% endhint %}

{% hint style="success" %}
### General Tips:

* Avoid flying directly above a crowd of people.
* Maintain line of sight with the aircraft and tether cable.
* Control/limit access to tether ground unit.
* Notify other pilots to be aware of your tether.
* Be prepared to shut down power source of the tether.
* Avoid flying in high/gusty wind conditions if possible.
* Do not fly in rain.
{% endhint %}
