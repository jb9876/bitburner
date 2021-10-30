<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bitburner](./bitburner.md) &gt; [Bladeburner](./bitburner.bladeburner.md) &gt; [getActionRepGain](./bitburner.bladeburner.getactionrepgain.md)

## Bladeburner.getActionRepGain() method

You have to be employed in the Bladeburner division and be in BitNode-7 or have Source-File 7 in order to use this function.

Returns the average Bladeburner reputation gain for successfully completing the specified action. Note that this value is an ‘average’ and the real reputation gain may vary slightly from this value.

<b>Signature:</b>

```typescript
getActionRepGain(
    type: BladeburnerActTypes,
    name: BladeburnerGenActions | BladeburnerContracts | BladeburnerOperations | BladeburnerBlackOps,
    level: number,
  ): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  type | [BladeburnerActTypes](./bitburner.bladeburneracttypes.md) | Type of action. |
|  name | [BladeburnerGenActions](./bitburner.bladeburnergenactions.md) \| [BladeburnerContracts](./bitburner.bladeburnercontracts.md) \| [BladeburnerOperations](./bitburner.bladeburneroperations.md) \| [BladeburnerBlackOps](./bitburner.bladeburnerblackops.md) | Name of action. Must be an exact match. |
|  level | number | Optional action level at which to calculate the gain |

<b>Returns:</b>

number

Average Bladeburner reputation gain for successfully completing the specified action.

## Remarks

4 GB
