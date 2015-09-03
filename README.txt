TT()   -   Full-blown ToolTip Library

TT is based on AHK Objects and supports both, ANSI and UNICODE version.

TT is used to work with ToolTip controls. You can create standalone ToolTips but also ToolTips for Controls for your GUI.

On AutoHotkey_H you can use the function as it is, it has no dependencies
Original AutoHotkey will need _Struct and sizeof(): https://github.com/HotKeyIt/_Struct

Also you will need following function:

		Struct(Structure,pointer:=0,init:=0){
			return new _Struct(Structure,pointer,init)
		}

Documentation can be found here: 	https://github.com/HotKeyIt/TT/blob/master/TT.ahk
Or download documentation  here: 	https://github.com/HotKeyIt/TT/blob/master/TT.chm