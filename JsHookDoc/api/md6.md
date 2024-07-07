# device

Used to retrieve basic information about the current device.

## device.isAdbEnabled()

Checks if ADB (Android Debug Bridge) is enabled on the device.

**Returns**: boolean - `true` if ADB is enabled, `false` otherwise.

## device.getSDKVersionName()

Gets the Android SDK version name of the device.

**Returns**: string - SDK version name (e.g., "Android 12").

## device.getSDKVersionCode()

Gets the Android SDK version code of the device.

**Returns**: int - SDK version code (e.g., 31 for Android 12).

## device.getAndroidID()

Gets the Android ID of the device.

**Returns**: string - Android ID.

## device.getMacAddress()

Gets the MAC address of the device.

**Returns**: string - MAC address.

## device.getManufacturer()

Gets the manufacturer of the device.

**Returns**: string - Manufacturer name (e.g., "Samsung", "Google").

## device.getModel()

Gets the model of the device.

**Returns**: string - Device model name.

## device.getABIs()

Gets the supported ABIs (Application Binary Interfaces) of the device.

**Returns**: string - Comma-separated list of ABIs.

## device.isTablet()

Checks if the device is a tablet.

**Returns**: boolean - `true` if the device is a tablet, `false` otherwise.

## device.isDevelopmentSettingsEnabled()

Checks if developer settings are enabled on the device.

**Returns**: boolean - `true` if developer settings are enabled, `false` otherwise.

## device.getScreenWidth()

Gets the width of the screen in pixels.

**Returns**: int - Screen width in pixels.

## device.getScreenHeight()

Gets the height of the screen in pixels.

**Returns**: int - Screen height in pixels.

## device.getScreenDensity()

Gets the screen density of the device.

**Returns**: float - Screen density.

## device.getScreenDensityDpi()

Gets the screen density DPI (dots per inch) of the device.

**Returns**: int - Screen density DPI.

## device.isLandscape()

Checks if the device is in landscape orientation.

**Returns**: boolean - `true` if in landscape orientation, `false` otherwise.

## device.isPortrait()

Checks if the device is in portrait orientation.

**Returns**: boolean - `true` if in portrait orientation, `false` otherwise.

## device.screenShot(activity)

Captures a screenshot of the device screen.

**Parameters**:

`activity`: Activity - Current activity context.

**Returns**: Bitmap - Captured screenshot as a Bitmap object.

## device.setClipboard(data)

Sets the content of the clipboard on the device.

**Parameters**:

`data`: string - Text to set in the clipboard.

## device.getClipboard()

Gets the content currently stored in the clipboard on the device.

**Returns**: string - Text content of the clipboard.