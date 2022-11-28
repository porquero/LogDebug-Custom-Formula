# LogDebug Custom Formula

Custom formula for EspoCRM for log debug data in entity, workflow or flowcharts formulas.

## Instalation

Add extension on EspoCRM administration

## Intructions for use it

* Modify config.php/config-internal.php file and change log level to DEBUG.
* Use LogDebug entity, workflow or flowcharts formulas.

## Example

```
$myVar = 1 + 2;
util\logDebug('test', $myVar);
```

### Result (in log file)

```
[2022-11-25 22:28:49] DEBUG: LogDebug > alias: test | data: [3] []
```
