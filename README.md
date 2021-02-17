# moondata

A PHP script to output HTML giving the current phase of the moon along with the dates of upcoming phases. This block of code is meant to be used as an include template for a Wview weather site.

## Set Up

1. Edit the time zone, latitude, and longitude values for your location.
2. Set up cron to run this script periodically, such as:

```cron
# Calculate current moon phase
0 */2 * * * /usr/local/bin/moondata > /usr/local/etc/wview/html/moon.incx
```

## Sample Output
With CSS, it displays like:

![Moon phase screen shot](screenshot.png)