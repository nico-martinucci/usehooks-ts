This React Hook offers you an interface to set, enable, disable, toggle and read the dark theme mode.
The returned value (`isDarkMode`) is a boolean to let you be able to use with your logic.

It uses internally [`useLocalStorage()`](/react-hook/use-local-storage) to persist the value and listens the OS color scheme preferences.
