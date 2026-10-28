# Flying Sun App

The FS500 features a dedicated 'Flying Sun app,' which comes pre-installed on the FS500 Pilot Pro. This app connects wirelessly to the tether ground unit to monitor and control the system, providing real-time status and tether information during flight

<figure><img src="../.gitbook/assets/image (1).png" alt="" width="375"><figcaption><p>FS500 App Interface</p></figcaption></figure>

### Monitoring system status

Operators must actively monitor the tether system status throughout the flight. Pay critical attention to the following parameters:

* Power Draw: Continuously monitor power consumption. Do not exceed the 3000W system limit. Exceeding this threshold may result in a system fault or power failure.
* Tether Extension: Monitor the deployed tether length. The tether ground unit will sound an audible alarm when the extension reaches 95m.

{% hint style="info" %}
Tether zero point is when extension length is at 0.0m, there will be more information about this later on.
{% endhint %}

{% hint style="danger" %}
Failure to monitor and respect system limits can lead to equipment failure or loss of the aircraft.
{% endhint %}

### Enable/Disable HV (High Voltage)

To engage or disengage the tether power system, use the Enable/Disable HV button in the app.

* To Enable: Pressing this button activates the system. The Ground Unit will supply 750V DC to the Air Unit, which then converts it to 25V DC to power the aircraft and lights.
* To Disable: Pressing the button again will shut down the high-voltage supply.

{% hint style="danger" %}
Please make sure all personnel are clear of tether and aircraft before enabling HV.&#x20;
{% endhint %}

### Take up (Retract)

The tether cable can be retracted for storage using either the Take Up button in the Flying Sun app or the touchscreen on the tether ground unit. To retract using Flying Sun app:

1. First, ensure the High Voltage (HV) is disabled.
2. HOLD down the Take Up button on the app to reel the cable into the ground unit.
3. RELEASE the Take Up button on the app to stop.

{% hint style="info" %}
The take up function is only available when the High Voltage (HV) is disabled
{% endhint %}

