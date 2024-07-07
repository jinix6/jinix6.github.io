# app

Used to retrieve basic information about the current hooked application.

## app.isAppSystem()

Check if the app is a system app.

**Returns**: boolean

## app.isAppForeground()

Check if the app is in the foreground.

**Returns**: boolean

## app.exitApp()

Close the application.

## app.getAppInfo()

Get information about the application.

**Returns**: object

## app.openUrl(url)

Open the specified URL.

**Parameters**:

`url`: string - The URL to open.

## app.startActivity(activity)

Start an activity.

**Parameters**:

`activity`: Activity - The activity to start.

## app.getActivityList()

Get the list of activities in the stack.

**Returns**: List<Activity>

## app.finishActivity(activity)

Finish an activity.

**Parameters**:

`activity`: Activity - The activity to finish.

## app.finishToActivity(activity)

Finish back to a specific activity.

**Parameters**:

`activity`: Activity - The activity to finish back to.

## app.startHomeActivity()

Go back to the home screen.

## app.dpToPx(value)

Convert dp to pixels (px).

**Parameters**:

`value`: float - Value in dp.

**Returns**: int - Value in pixels (px).

## app.pxToDp(value)

Convert pixels (px) to dp.

**Parameters**:

`value`: float - Value in pixels (px).

**Returns**: int - Value in dp.

## app.getInternalAppDataPath()

Get the internal app data directory path.

**Returns**: string

## app.getExternalAppDataPath()

Get the external app data directory path.

**Returns**: string

## app.getExternalAppObbPath()

Get the external app OBB directory path.

**Returns**: string

## app.getExternalStoragePath()

Get the external storage directory path.

**Returns**: string