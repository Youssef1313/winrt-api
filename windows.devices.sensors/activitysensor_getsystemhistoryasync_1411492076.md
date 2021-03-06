---
-api-id: M:Windows.Devices.Sensors.ActivitySensor.GetSystemHistoryAsync(Windows.Foundation.DateTime,Windows.Foundation.TimeSpan)
-api-type: winrt method
---

<!-- Method syntax
public Windows.Foundation.IAsyncOperation<Windows.Foundation.Collections.IVectorView<Windows.Devices.Sensors.ActivitySensorReading>> GetSystemHistoryAsync(Windows.Foundation.DateTime fromTime, Windows.Foundation.TimeSpan duration)
-->

# Windows.Devices.Sensors.ActivitySensor.GetSystemHistoryAsync

## -description
Asynchronously gets sensor readings from a specific time and duration.

## -parameters
### -param fromTime
The time at which to get sensor readings.

### -param duration
The time span during which to get sensor readings.

## -returns
Asynchronously returns a list of [ActivitySensorReading](activitysensorreading.md) objects that represent info about the sensor.

## -remarks

## -examples

## -see-also
[GetSystemHistoryAsync(DateTime)](activitysensor_getsystemhistoryasync_1048912884.md)