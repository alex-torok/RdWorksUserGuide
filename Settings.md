# Scan Parameters

### Independent Output

Scan each object in the layer one by one as opposed to scanning over the entire
layer.

If you have a layer with lots of spread out objects, enabling this setting can
save a lot of time executing the job.

**?** What does this setting do for BMP layers **?**

*Note:* In the gradient test file for **Output Direct**, the block gradient and
smooth gradient aren't properly output unless *Independent Output* is checked.
Try enabling/disabling **Independent Output** for the *Output Direct* layer
and looking at the preview window.

### Ramp Effect

**??**
Something with ramping the laser power up and down from *Min Power(%)* to *Max
Power(%)* at the start and stop of scan lines
**??**

## Bitmap Scan Settings

The below settings are only controllable if the target layer is operating on
an imported bitmap image. These settings can't do anything for vector layers.

### Output Direct

*Output direct* causes the laser power to adjust based on the blackness of pixel
it is scanning over. Pure white maps to *Min Power(%)* and pure black maps to
*Max Power(%)*

This setting can be useful to get varying depths when attempting 3d etching. It
is also good for getting smooth gradients when etching images.

*Note*: Enabling *Output Direct* disables the *Overstriking* scan parameter.

### Negative Engrave

*Negative Engrave* inverts the laser power for the scan. Instead of black parts
of an image causing the laser to turn on, the white parts will.

This can be used when etching an image onto a material that lightens with
engraving, such as slate rock.

### Optimized Scan

**??**
Something with adjusting the scan interval based on the image. Maybe it looks at
the resolution of the picture -- not sure.
**??**
