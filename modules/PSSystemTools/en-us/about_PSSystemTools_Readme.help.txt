
NAME
    Test-32Bit
    
SYNOPSIS
    Determines whether the computer has a 32-bit processor architecture.
    
    
SYNTAX
    Test-32Bit [<CommonParameters>]
    
    
DESCRIPTION
    The Test-32Bit function returns TRUE if the computer has a 32-bit processor
    architecture and FALSE if it does not. The function does not have any parameters.
    
    64-bit machines will return true when you run this function in a process running in 32-bit mode
    

RELATED LINKS
    Test-64Bit 

REMARKS
    To see the examples, type: "get-help Test-32Bit -examples".
    For more information, type: "get-help Test-32Bit -detailed".
    For technical information, type: "get-help Test-32Bit -full".

NAME
    Get-USB
    
SYNOPSIS
    Gets USB devices attached to the system
    
    
SYNTAX
    Get-USB [[-computerName] <Object>] [<CommonParameters>]
    
    
DESCRIPTION
    Uses WMI to get the USB Devices attached to the system
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-USB -examples".
    For more information, type: "get-help Get-USB -detailed".
    For technical information, type: "get-help Get-USB -full".

NAME
    Get-OSVersion
    
SYNOPSIS
    Get the operating system Version
    
    
SYNTAX
    Get-OSVersion [[-computer] <Object>] [<CommonParameters>]
    
    
DESCRIPTION
    The Get-OSVersion function gets the version of the operating
    system on a local or remote computer.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-OSVersion -examples".
    For more information, type: "get-help Get-OSVersion -detailed".
    For technical information, type: "get-help Get-OSVersion -full".

NAME
    Get-MultiTouchMaximum
    
SYNOPSIS
    Gets the number of fingers that can be used on a multitouch device.
    
    
SYNTAX
    Get-MultiTouchMaximum [<CommonParameters>]
    
    
DESCRIPTION
    Gets the number of fingers that can be used on a multitouch device. This
    function does not have any parameters.
    

RELATED LINKS
     http://msdn.microsoft.com/en-us/library/ms724385(VS.85).aspx

REMARKS
    To see the examples, type: "get-help Get-MultiTouchMaximum -examples".
    For more information, type: "get-help Get-MultiTouchMaximum -detailed".
    For technical information, type: "get-help Get-MultiTouchMaximum -full".

NAME
    Get-WindowsEdition
    
SYNOPSIS
    Gets the operating system edition.
    
    
SYNTAX
    Get-WindowsEdition [<CommonParameters>]
    
    
DESCRIPTION
    The Get-WindowsEdition function gets the edition of the operating
    system on the local computer. This function has no parameters.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-WindowsEdition -examples".
    For more information, type: "get-help Get-WindowsEdition -detailed".
    For technical information, type: "get-help Get-WindowsEdition -full".

NAME
    Get-LogicalDiskInventory
    
SYNOPSIS
    Gets the local disks on the local and remote computers.
    
    
SYNTAX
    Get-LogicalDiskInventory [[-computername] <Object>] [<CommonParameters>]
    
    
DESCRIPTION
    The Get-LogicalDiskInventory function gets information about the local, 
    non-removable logical disks on the local computer and remote computers.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-LogicalDiskInventory -examples".
    For more information, type: "get-help Get-LogicalDiskInventory -detailed".
    For technical information, type: "get-help Get-LogicalDiskInventory -full".

NAME
    Import-IniFile
    
SYNOPSIS
    Imports settings from an Ini file
    
    
SYNTAX
    Import-IniFile [[-File] <String>] [<CommonParameters>]
    
    
DESCRIPTION
    Imports settings from an Ini file.
    Returns an object with a property for each section in the INI file
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Import-IniFile -examples".
    For more information, type: "get-help Import-IniFile -detailed".
    For technical information, type: "get-help Import-IniFile -full".

NAME
    Get-DisplaySetting
    
SYNOPSIS
    Gets the screen width and height.
    
    
SYNTAX
    Get-DisplaySetting [<CommonParameters>]
    
    
DESCRIPTION
    The Get-DisplaySetting function gets the width and height of the primary display monitor, in pixels. This function has no parameters.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-DisplaySetting -examples".
    For more information, type: "get-help Get-DisplaySetting -detailed".
    For technical information, type: "get-help Get-DisplaySetting -full".

NAME
    Get-Font
    
SYNOPSIS
    Gets the fonts currently loaded on the system
    
    
SYNTAX
    Get-Font [[-font] <Object>] [<CommonParameters>]
    
    
DESCRIPTION
    Uses the type System.Windows.Media.Fonts static property SystemFontFamilies,
    to retrieve all of the fonts loaded by the system.  If the Fonts type is not found,
    the PresentationCore assembly will be automatically loaded
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-Font -examples".
    For more information, type: "get-help Get-Font -detailed".
    For technical information, type: "get-help Get-Font -full".

NAME
    Get-BootStatus
    
SYNOPSIS
    Gets information about whether the system started normally.
    
    
SYNTAX
    Get-BootStatus [<CommonParameters>]
    
    
DESCRIPTION
    Gets information about whether the system started normally. 
    
    Return values are:
    
    -- Normal
    -- SafeMode
    -- SafeModeWithNetworking
    
    This function has no parameters.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-BootStatus -examples".
    For more information, type: "get-help Get-BootStatus -detailed".
    For technical information, type: "get-help Get-BootStatus -full".

NAME
    Get-SystemFont
    
SYNOPSIS
    Gets the fonts associated with different system items (e.g. captions, menus, icons)
    
    
SYNTAX
    Get-SystemFont [<CommonParameters>]
    
    
DESCRIPTION
    Uses the static properties of the type System.Windows.SystemFont
    to retrieve all of the fonts associated with different system items.
    If the System.Windows.SystemFont type is not found, the PresentationCore 
    assembly will be automatically loaded
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-SystemFont -examples".
    For more information, type: "get-help Get-SystemFont -detailed".
    For technical information, type: "get-help Get-SystemFont -full".

NAME
    Test-64Bit
    
SYNOPSIS
    Determines whether the computer has a 64-bit processor architecture.
    
    
SYNTAX
    Test-64Bit [<CommonParameters>]
    
    
DESCRIPTION
    The Test-64Bit function returns TRUE if the computer has a 64-bit processor
    architecture and FALSE if it does not. The function does not have any parameters.
    

RELATED LINKS
    Test-32Bit 

REMARKS
    To see the examples, type: "get-help Test-64Bit -examples".
    For more information, type: "get-help Test-64Bit -detailed".
    For technical information, type: "get-help Test-64Bit -full".

NAME
    Get-Processor
    
SYNOPSIS
    Gets processor information for local and remote computers.
    
    
SYNTAX
    Get-Processor [[-Computer] <Object>] [<CommonParameters>]
    
    
DESCRIPTION
    The Get-Processor function gets information about the processors
    on local and remote computers, including the processor architecture.
    

RELATED LINKS

REMARKS
    To see the examples, type: "get-help Get-Processor -examples".
    For more information, type: "get-help Get-Processor -detailed".
    For technical information, type: "get-help Get-Processor -full".




