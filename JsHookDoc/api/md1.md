# runtime

Provides access to current hook runtime information.

## runtime.appInfo

**Returns**: ApplicationInfo

Provides information about the current application.

## runtime.packageName

**Returns**: string

Returns the package name of the current application.

## runtime.processName

**Returns**: string

Returns the name of the current process.

## runtime.classLoader

**Returns**: ClassLoader

Returns the class loader of the current hook.

## runtime.isKernel

Checks if running in kernel mode.

**Returns**: boolean

Returns `true` if running in kernel mode, `false` otherwise.

## runtime.coreVersionCode

Gets the version code of the current JSHook.

**Returns**: int

Returns the version code of the current JSHook.

## runtime.modVersion

Gets the version of the current FiraMod.

**Returns**: string

Returns the version string of the current FiraMod.

## runtime.modVersionCode

Gets the version code of the current FiraMod.

**Returns**: int

Returns the version code of the current FiraMod.